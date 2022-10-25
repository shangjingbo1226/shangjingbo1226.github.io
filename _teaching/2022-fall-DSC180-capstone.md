---
title: "2022-Fall-DSC180B14-Capstone: Weakly Supervised NLP"
collection: teaching
type: "Undergraduate Class"
permalink: /teaching/2022-fall-DSC180B14-capstone
venue: "HDSI, UCSD"
date: 2022-09-28
location: "La Jolla, CA"
---

**Class Time**: Wednesdays, 11 to 11:50 AM Pacific Time.  **Room**: [https://ucsd.zoom.us/j/91491702947](https://ucsd.zoom.us/j/91491702947).

Overview
======

This capstone section talks about text mining and natural language processing with a focus on (extremely) weakly supervsed methods. We will explore cutting-edge research papers in these areas together and try to replicate some experiments for a deeper, better understanding. 

We will mostly have discussions in a Q&A form, instead of traditional lectures. The discussions will be online over Zoom. 

Papers to Read
======

* [Contextualized Weak Supervision for Text Classification](https://www.dropbox.com/s/9pn0pg9pm5raj86/%5BACL%2720%5DContextualized%20Weak%20Supervision%20for%20Text%20Classification.pdf?dl=1) <br/>
Dheeraj Mekala and Jingbo Shang. **ACL** 2020. [[code](https://github.com/dheeraj7596/ConWea)]

* [X-Class: Text Classification with Extremely Weak Supervision](https://arxiv.org/abs/2010.12794) <br/>
Zihan Wang, Dheeraj Mekala and Jingbo Shang. **NAACL** 2021. [[code](https://github.com/ZihanWangKi/XClass)]


**Tips**
1. These two papers are both working on weakly supervised text classification. Please read them one by one. 
2. The Github README files also provide useful information.
3. PDFs of these papers can be found online for free.


Schedule
======

Week | Date  | Discussion Focus
1    | 09/28 | General Overview (a short lecture by Jingbo Shang)
2    | 10/05 | [Introduction & Motivation](#week2)
3    | 10/12 | [Datasets and Experiment Design](#week3)
4    | 10/19 | [Experimental Results - Analysis](#week4)
5    | 10/26 | [Experimental Results - Replication](#week5)
6    | 11/02 | [Case Studies](#week6)
7    | 11/09 | [Application Brainstorming](#week7)
8    | 11/16 | [Possible Extension](#week8)
9    | 11/23 | [Report Writing Discussion](#week9)
10   | 11/30 | [Elevator Pitch](#week10)


Discussion Questions
======

### Week 2: Introduction & Motivation {#week2}

1. Why do we want to study weakly supervised text classification? What's the advantage of weak supervision over full supervision?
2. What's the major problem when someone is going to build a fully supervised text classifier for a new corpus? Is there any human effort?
3. What's the motivation of ConWea? Compared with traditional weak supervision (e.g., counting keywords via string match), which parts do you believe are novel?
4. What's the motivation of X-Class? Compared with ConWea and traditional weak supervision, what are the major invotations in X-Class?


### Week 3: Datasets and Experiment Design {#week3}

1. How many datasets are used in the papers? How many domains and classification scenarios are covered?
2. Why do we want to use such a diverse set of datasets? How this is related to the claims in the papers?
3. Why does ConWea have slightly different evaluation settings than X-Class? Is the experiment design related to the claims in the paper?


### Week 4: Experimental Results - Analysis {#week4}

1. Please outline the claims in these two papers.
2. How can we understand each table and figure? What are the takeaways? One or two sentences per table/figure should be enough.
3. For each claim, where are the experimental results supporting it?


### Week 5: Experimental Results - Replication {#week5}

We will aim to reproduce some baseline methods used in ConWea: (1) IR-TF-IDF and (2) Word2Vec.
We are skipping the neural network models since DSMLP doesn't have enough GPU memory to support BERT model training.

Quoting from the ConWea paper's Section 6.2, we have 
1. **IR-TF-IDF** treats the seed word set for each class as a query. The relevance of a document to a label is computed by aggregated TF-IDF values of its respective seed words. The label with the highest relevance is assigned to each document.
2. **Word2Vec** first learns word vector representations (Mikolov et al., 2013) for all terms in the corpus and derive label representations by aggregating the vectors of its respective seed words. Finally, each document is labeled with the most similar label based on cosine similarity.

We have explained these two methods in the discussion session too. If you still have quesitons after revisisting the recording, please email me. 

Here are some tips:
- In IR-TF-IDF, it is basically counting. The Python library [TfidfVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) might be useuful. The IDF calculation is also straightforward after tokenization, so please feel free to implement it yourself (e.g., using for-loop and dictionary) in Python.
- In Word2Vec, you are asked to train word2vec embedding based on the input documents in each dataset. You may find [gesim](https://radimrehurek.com/gensim/models/word2vec.html) package useful.
- For the seed words, please refer to the ConWea repo. 

At the minimum, you are expected to show:
1. A table of your replicated results, including the two methods mentioned above and the micro-F1 and macro-F1 scores. Specifically, we will focus on the two coarse-grained datasets in ConWea: (1) NYT-coarse and (2) 20News-coarse. Please feel free to include the fine-grained datasets. 
2. The implementation details of your replication. It will be the best to include some concrete steps, formulas, and package information. 
3. The well-documented code repo of your replication. 
4. Any takeaways, challenges encountered, and thoughts are encouraged to be included in the report.

**Note:** If you found the performance is worse than the paper's reported values, please pay attention to pre-processing and other tuning effort --- think about tokenization, stopwords, stemming, lemmatization, different TF-IDF variants, hyper-parameters in word2vec, etc. Please keep in mind that In the paper, we tried our best to tune the baselines to make them strong. Therefore, in this replication practice, we don't have to exactly re-produce the performance. As long as your implementation is on the right track, it is okay to be slightly worse than the reported numbers. 


### Week 6: Case Studies {#week6}

1. Why do we need case studies in addition to the quantitative results?
2. How case studies further the claims in the papers?
3. Do you have any interesting findings from either the case studies presented in the papers or the results you got from Week 5?


### Week 7: Application Brainstorming {#week7}

1. What kind of applications do you think could be benefited from weakly supervised text classification? Why?
2. Try to think broadly for more domains/languages.
3. Based on your proposed applications, can we apply ConWea/X-Class directly?
2. Do you think there is some necessary adaption? If yes, how? If no, why?


### Week 8: Possible Extension {#week8}

1. What are the drawbacks of these two papers? Do you see any limitations?
2. Can we do better in order to address these limitations?


### Week 9: Report Writing Discussion {#week9}

1. Do you have any questions about the final report writing?
2. How to prepare informative Figures and Tables?
3. How to properly cite previous work?
4. How to make the proposal look more promising?


### Week 10: Elevator Pitch {#week10}

We will have a timed rehearsal for the evevator pitch. 