---
title: "UCSD CSE AI Seminar, Fall 2023"
collection: teaching
type: "Graduate Class"
permalink: /teaching/2023-fall-ucsd-ai-seminar
venue: "CSE, UCSD"
date: 2023-10-02
location: "La Jolla, CA"
author_profile: false
---

**Class Time**: Mondays, 12:30PM to 1:30PM.  **Room**: CSE 1202.  **Zoom Streaming**: [https://ucsd.zoom.us/j/92652773524](https://ucsd.zoom.us/j/92652773524).

Overview
======

UCSD CSE AI Seminar focuses on discussing the state-of-the-art methods in AI-related fields. We invite distinguished researchers to talk about their most recent works. For graduate students who want to earn course credits by attending this seminar, please enroll into CSE 259. 


Lecture Schedule
======

**Recording Note**: Please download the recording video for the full length. Dropbox website will only show you the first one hour.

Week | Date  | Talk Info | Speaker | Affiliation 
1    | 10/02 | [Build an Ecosystem, Not a Monolith](#week1) [slides] [recording]| Colin Raffel | University of Toronto and Hugging Face
2    | 10/09 | [Title TBD](#week2) [slides] [recording]| Yu Su | Ohio State University | 
3    | 10/16 | [Learning from Weak Supervision: Label Noise or Bias?](#week3) [slides] [recording] | Jingbo Shang | UC San Diego
4    | 10/23 | [Why Does Sharpness-Aware Minimization Generalize Better Than SGD?](#week4) [slides] [recording] | Quanquan Gu | UCLA
5    | 10/30 | [Title TBD](#week5) [slides] [recording] | Sergey Levine | UC Berkeley
6    | 11/06 | [Scaling Data-Constrained Language Model](#week6) [slides] [recording] | Alexander Rush | Cornell
7    | 11/13 | [Title TBD](#week7) [slides] [recording] | Xian Ren | USC
8    | 11/20 | [Title TBD](#week8) [slides] [recording] | Yejin Choi | University of Washington
9    | 11/27 | [Title TBD](#week9) [slides] [recording]| Taylor Berg-Kickpatrick | UC San Diego
10   | 12/04 | [Title TBD](#week10) [slides] [recording]| Alex Tamkin | UC San Diego

## Week 1: Build an Ecosystem, Not a Monolith {#week1}

### Abstract

Currently, the preeminent paradigm for building artificial intelligence is the development of large, general-purpose models that aim to be able to perform all tasks at (super)human level. In this talk, I will argue that an ecosystem of specialist models would likely be dramatically more efficient and could be significantly more effective. Such an ecosystem could be built collaboratively by a distributed community and be continually expanded and improved. In this talk, I will outline some of the technical challenges involved in creating model ecosystems, including automatically selecting which models to use for a particular task, merging models to combine their capabilities, and efficiently communicating changes to a model.
Bio: Colin Raffel is an associate professor at the University of Toronto and a faculty researcher at Hugging Face. His work aims to make it easy to get computers to do new things.

### Speaker Bio

Colin Raffel is an associate professor at the University of Toronto and a faculty researcher at Hugging Face. His work aims to make it easy to get computers to do new things.

## Week 2: TBD {#week2}

### Abstract

TBD

### Speaker Bio

TBD


## Week 3: Learning from Weak Supervision: Label Noise or Bias? {#week3}

### Abstract

Recent advances in weakly supervised text classification mostly focus on designing sophisticated methods to turn high-level human heuristics into quality pseudo-labels. In this talk, we will first review a few popular methods to generate and select high-quality pseudo-labels, and then we will show that the simplest method based on seed matching, was greatly underestimated. We will show that the limited performance of seed matching is largely due to the label bias injected by the simple seed-match rule, which prevents the classifier from learning reliable confidence for selecting high-quality pseudo-labels. Interestingly, simply deleting the seed words present in the matched input texts can mitigate the label bias and help learn better confidence. Subsequently, the performance achieved by seed matching can be improved significantly, making it on par with or even better than the state-of-the-art. Furthermore, to handle the case when the seed words are not made known, we propose to simply delete the word tokens in the input text randomly with a high deletion ratio. Remarkably, seed matching equipped with this random deletion method can often achieve even better performance than that with seed deletion.

### Speaker Bio

Jingbo Shang is an Assistant Professor at the Computer Science and Engineering Department and Halicioglu Data Science Institute at the University of California, San Diego. His research focuses on data mining, natural language processing, and machine learning methods with minimum human effort and their applications. He obtained his Ph.D. from the University of Illinois at Urbana-Champaign in 2019 and his B.E. from Shanghai Jiao Tong University in 2014. His research has been recognized by many prestigious awards, including SIGKDD Dissertation Award Runner-up in 2020, Google Research Scholar in 2021, and NSF CAREER award in 2023.

## Week 4: Why Does Sharpness-Aware Minimization Generalize Better Than SGD? {#week4}

### Abstract

The challenge of overfitting, in which the model memorizes the training data and fails to generalize to test data, has become increasingly significant in the training of large neural networks. To tackle this challenge, Sharpness-Aware Minimization (SAM) has emerged as a promising training method, which can improve the generalization of neural networks even in the presence of label noise. However, a deep understanding of how SAM works, especially in the setting of nonlinear neural networks and classification tasks, remains largely missing. In this talk, I will show why SAM generalizes better than Stochastic Gradient Descent (SGD) for certain data model and two-layer convolutional ReLU networks. Our theoretical analysis explains the benefits of SAM, particularly its ability to prevent noise learning in the early stages, which enables the learning of weak features more effectively. Experiments on both synthetic and real data sets corroborate our theory.

This talk is based on joint work with Zixiang Chen, Junkai Zhang, Yiwen Kou, Xiangning Chen and Cho-Jui Hsieh.

### Speaker Bio

Quanquan Gu is an Associate Professor of Computer Science at UCLA. His research is in the area of artificial intelligence and machine learning, with a focus on developing and analyzing nonconvex optimization algorithms for machine learning to understand large-scale, dynamic, complex, and heterogeneous data and building the theoretical foundations of deep learning and reinforcement learning. He received his Ph.D. degree in Computer Science from the University of Illinois at Urbana-Champaign in 2014. He is a recipient of the Sloan Research Fellowship, NSF CAREER Award, Simons Berkeley Research Fellowship among other industrial research awards.

## Week 5: TBD {#week5}

### Abstract

TBD

### Speaker Bio

TBD

## Week 6: Scaling Data-Constrained Language Model {#week6}

### Abstract

Extrapolating scaling trends suggest that training dataset size for LLMs may soon be limited by the amount of text data available on the internet. In this talk we investigate scaling language models in data-constrained regimes. Specifically, we run a set of empirical experiments varying the extent of data repetition and compute budget. From these experiments we propose and empirically validate a scaling law for compute optimality that accounts for the decreasing value of repeated tokens and excess parameters. Finally, we discuss and experiment with approaches for mitigating data scarcity.

### Speaker Bio

Alexander "Sasha" Rush is an Associate Professor at Cornell Tech and a researcher at Hugging Face. His research interest is in the study of language models with applications in controllable text generation, efficient inference, and applications in summarization and information extraction. In addition to research, he has written several popular open-source software projects supporting NLP research, programming for deep learning, and virtual academic conferences. His projects have received paper and demo awards at major NLP, visualization, and hardware conferences, an NSF Career Award and Sloan Fellowship. He tweets at @srush_nlp. 

## Week 7: TBD {#week7}

### Abstract

TBD

### Speaker Bio

TBD

## Week 8: TBD {#week8}

### Abstract

TBD

### Speaker Bio

TBD


## Week 9: TBD {#week9}

### Abstract

TBD

### Speaker Bio

TBD


## Week 10: TBD {#week10}

### Abstract

TBD

### Speaker Bio

TBD