---
title: "2025-Winter-MGTA415-Analyzing Unstructured Data"
collection: teaching
type: "Graduate Class"
permalink: /teaching/2025-winter-MGTA415-Unstructured-Data
venue: "Rady Management School, UCSD"
date: 2025-01-06
location: "La Jolla, CA"
---

**Class Time**: Mondays, 2 to 4:50PM.  **Room**: OTRSN 1E107 (1st week over Zoom).  **Piazza**: [piazza.com/ucsd/winter2025/mgta415](https://piazza.com/ucsd/winter2025/mgta415)


Online Lecturing
======

To offer waitlist students opportunities to learn more about this course, in the first week, we deliver the lecture over Zoom: [https://ucsd.zoom.us/j/95861287987](https://ucsd.zoom.us/j/95861287987). The lecture will be recorded. 


Overview
======

This course mainly focuses on introducing current methods and models that are useful in analyzing and mining real-world unstructured text data.

As the starting points, we will review basic machine learning models like linear regression and logistic regression. Then, we will cover traditional text preprocessing techniques, including tokenization, POS tagging, parsing, etc, using popular Python libraries as examples. After that, we will talk about more text analysis problems like text classification (e.g., sentiment analysis), information retrieval, topic modeling, word embedding, language models, etc.

This course will mainly focus on high-level understandings of these concepts and also provide the students handles to implement their own text analysis models (e.g., how to use 3rd-party libs, and how to set hyper-parameters).

After the midterm exam, we will take about more advanced text mining problems, such as phrase mining, named entity recognition, and taxonomy construction. We will go beyond the traditional supervised methods and put some emphasis on unsupervised, weakly supervised, and distantly supervised methods. Bootstrapping, comparative analysis, learning from seed words and existing knowledge bases will be the key methodologies to know. We will also explain ChatGPT without any formula and offer high-level insights about how to better utilize ChatGPT.

We will have a take-home midterm, a few homework assignments, a Kaggle-like competition, and a final (team-based) project. These four parts will have roughly the same weights.

There is no textbook required, but there are recommended readings for each lecture (at the end of the slides).

If you don't have much experience in data mining, machine learning, etc. Here are some recommended textbooks to review.

- The classical data mining textbook "[Data Mining: Concepts and Techniques](https://books.google.com/books/about/Data_Mining_Concepts_and_Techniques.html?id=pQws07tdpjoC&source=kp_book_description)" by Jiawei Han et al.
- The classical data mining/machine learning book "[Pattern Recognition and Machine Learning](https://books.google.com/books/about/Pattern_Recognition_and_Machine_Learning.html?id=HL4HrgEACAAJ&source=kp_book_description)" by Christopher M. Bishop
- The new "[Dive into Deep Learning](https://d2l.ai/)" book by Aston Zhang et al.


Prerequisites
======

- Math, Stats, and Coding
- For Coding
    - We will mainly use Python
    - Sometimes, we will need to run some tools developed in C/C++ and Java
- It’s a bonus if you already have knowledge about machine learning and data mining

Teaching Assistant
======

- Siqi Wang
- Feng Yao
- Jinya Jiang

Office Hours
======

- Jingbo Shang
    - Office Hour: Wednesdays, 9 to 11 AM
    - Zoom link: [https://ucsd.zoom.us/my/jshang](https://ucsd.zoom.us/my/jshang)
- Siqi Wang
    - Office Hour: Thursdays, 9 to 10 AM
    - Zoom link: [https://ucsd.zoom.us/j/3781427002](https://ucsd.zoom.us/j/3781427002)
- Feng Yao
    - Office Hour: Tuesdays, 9 to 10 AM
    - Zoom link: [https://ucsd.zoom.us/my/fengyao](https://ucsd.zoom.us/my/fengyao)
- Jinya Jiang
    - Office Hour: Wednesdays 10 to 11 AM
    - Zoom link: [https://ucsd.zoom.us/j/2427132936](https://ucsd.zoom.us/j/2427132936)

Note: all times are in **Pacific Time**.

Grading
======

- Homework: 8% each. 
- Midterm: 26%.
- Data Mining Challenge: 25%.
- Project: 25%.
- You should complete all work individually, except for the Project.
- Late submissions are NOT accepted.

Lecture Schedule
======

**Recording Note**: Please check out Canvas for recordings.

**HW Note**: All HWs due by the end of the day on the due date, i.e., 11:59 PM PT. 

Week | Date        | Topic & Slides                                              | Events
1    | 01/06 (Mon) | [Intro and Text Preprocessing](https://www.dropbox.com/scl/fo/69mqjaddkd2ckdjjdncl0/AH8lKFP5-2A5KRvLKMWWeMo?rlkey=raofwqnsvq2f10l2dgxo3g2sw&dl=0) | HW1 out
2    | 01/13 (Mon) | [Machine Learning Concepts and Basics](https://www.dropbox.com/scl/fo/go93bqeu1evefrv41coyy/AC8awIhayeIUWylq_O3rdzY?rlkey=4ayyqt8mffcs281f4t545g2w3&dl=0) | 
3    | 01/20 (Mon) | MLK Day (no class)  | 
4    | 01/27 (Mon) | [Text Classification using Bag-of-Words](https://www.dropbox.com/scl/fo/pdi58wcic0ders28ntzzk/AKmqe6zQJa9T1BoOOQ98kwE?rlkey=f53vrhtb5mxfk32ehiuezt0wy&dl=0) | DM Challenge out
5    | 02/03 (Mon) | [Word Embedding & Language Models: from N-Gram to Neural LMs](https://www.dropbox.com/scl/fo/93xzr0xhbf02cjffc88lh/ANLi2oORffiFJ-Vk3SfZ2oQ?rlkey=6hzpa09d6wo2dqhz0j2bexxl0&dl=0) | HW1 due, HW2 out
6    | 02/10 (Mon) | [Information Retrieval & Topic Modeling](https://www.dropbox.com/scl/fo/9ksov491hrhz8zhorwe1e/ADb3gdwESbakXw2OYQ4BU4g?rlkey=ha8aqmjn7c9nr6dlccwh9s1o1&dl=0) |
7    | 02/17 (Mon) | Presidents' Day (no class) | HW2 due, Midterm Exam Week 
8    | 02/24 (Mon) | Phrase Mining and its applications | HW3 out, DM challenge due
9    | 03/03 (Mon) | Image Classification | 
10   | 03/10 (Mon) | Weakly Supervised Text Classification | HW3 due

Homework (24%)
======

- **[HW1: Text Pre-processing and Classification](https://www.dropbox.com/s/z20d12ddfgzcqa0/HW1.zip?dl=0) (8%).** This homework mainly focuses on the impact of the pre-processing on the classification results.
- **[HW2: Word Embedding and Language Models](https://www.dropbox.com/scl/fo/6fkpjd8d4jqcihy6xlalu/AIjr8gV-SxPvYAGyaK2M82I?rlkey=7e14wpsihffe05wdwh1tkdv2l&dl=0) (8%).** This homework mainly focuses on trying out the word embedding and n-gram language models. 
- **HW3: Phrase Mining and Image Classification (8%).** This homework mainly focuses on applying phrase mining to a given set of documents and also try out some image classification model.

Midterm (26%)
======

It is an open-book, take-home exam, which covers all lectures given before the Midterm. Most of the questions will be open-ended. Some of them might be slightly more difficult than homework. The exam will be available to start in a 24-hour window. Once started, **the exam has a timer for 3 hours**.

- **Start**: Feb 18, 12 PM PT
- **End**: Feb 19, 12 PM PT
- Midterm problems: will be posted in Canvas.

Data Mining Challenge (25%)
======

It is a individual-based data mining competition with quantitative evaluation. The challenge runs **from Feb 1 to Feb 28**. Note that the time displayed on Kaggle is in UTC, not PT.

- Challenge Statement, Dataset, and Details: TBD.
- Kaggle challenge link: TBD.

Project (25%)
======

- Team-Based Open-Ended Project
    - 1 to 4 members per team. More members, higher expectation.
    - Define your own research problem and justify its importance
    - Final Deliverables: Research Paper-like Report
        - Report **due on Mar 16**, End of the day, Pacific Time. 
        - Write a 5 to 9 pages report (research-paper like following ACL template). The pages here do not include references.
        - Come up with your hypothesis and find some datasets for verification
        - Design your own models or try a large variety of existing models
        - Submit your codes and datasets; Github repos are welcome
        - Up to 5% bonus for working demos/apps towards the total course grades
