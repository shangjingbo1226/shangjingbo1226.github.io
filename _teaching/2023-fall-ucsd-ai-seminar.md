---
title: "UCSD CSE AI Seminar, Fall 2023"
collection: teaching
type: "Seminar & Graduate Course"
permalink: /teaching/2023-fall-ucsd-ai-seminar
venue: "CSE, UCSD"
date: 2023-10-02
location: "La Jolla, CA"
author_profile: false
---

**Time**: Mondays, 12:30PM to 1:30PM.  **Room**: CSE 1202.  **Zoom Streaming**: [https://ucsd.zoom.us/j/92652773524](https://ucsd.zoom.us/j/92652773524).

Overview
======

UCSD CSE AI Seminar focuses on discussing the state-of-the-art methods in AI-related fields. We invite distinguished researchers to talk about their most recent works. For graduate students who want to earn course credits by attending this seminar, please enroll into CSE 259. 


Talk Schedule
======

**Recording Note**: Please download the recording video for the full length. Dropbox website will only show you the first one hour.

Week | Date  | Talk Info | Speaker | Affiliation 
1    | 10/02 | [Build an Ecosystem, Not a Monolith](#week1) [[slides](https://www.dropbox.com/scl/fi/3ckrrgfr52w0j03jivkuo/1-Colin-Raffel-Build-an-Ecosystem-Not-a-Monolith.pdf?rlkey=j380upb014seebhb8xgwcm38j&dl=0)] [[recording](https://www.dropbox.com/scl/fi/zt9rybncchqlwv9vhujc8/1-Colin-Raffel-Build-an-Ecosystem-Not-a-Monolith.mp4?rlkey=ixqmlz375umavgepoog61pvur&dl=0)]| Colin Raffel | University of Toronto and Hugging Face
2    | 10/09 | [Language agents: a critical evolutionary step of AI](#week2) [[slides](https://www.dropbox.com/scl/fi/3kdv2fv09c8nfv0r9zvob/2-Yu-Su-Language-Agents.pdf?rlkey=qenoklm5tnksdfkotfjtmukgb&dl=0)] [[recording](https://www.dropbox.com/scl/fi/hy3x93xjjr063qgdr5uos/2-Yu-Su-Language-Agents.mp4?rlkey=9gx7vulnai2t52pwodqimmyao&dl=0)] | Yu Su | Ohio State University | 
3    | 10/16 | [Learning from Weak Supervision: Label Noise or Bias?](#week3) [[slides](https://www.dropbox.com/scl/fi/w5ln2qk6malfj8o6s6760/3-Jingbo-Shang-Label-Noise-or-Bias.pdf?rlkey=hv0kkipvmo2tyso10egfgkh07&dl=0)] [[recording](https://www.dropbox.com/scl/fi/c9doo7p5ek16s9bhjqnm8/3-Jingbo-Shang-Label-Noise-or-Bias.mp4?rlkey=s6ru15aop24imzdo32bssywin&dl=0)] | Jingbo Shang | UC San Diego
4    | 10/23 | [Why Does Sharpness-Aware Minimization Generalize Better Than SGD?](#week4) [[slides](https://www.dropbox.com/scl/fi/hd9sdj4zvjtrzoi9r04vi/4-Quanquan-Gu-Why-Does-Sharpness-Aware-Minimization-Generalize-Better-Than-SGD.pdf?rlkey=san8njlg6p639i3hzkt9v5se1&dl=0)] [[recording](https://www.dropbox.com/scl/fi/st3a02gaytdqkldr6tzto/4-Quanquan-Gu-Why-Does-Sharpness-Aware-Minimization-Generalize-Better-Than-SGD.mp4?rlkey=738mk2sujt6mw68124e4ysq22&dl=0)] | Quanquan Gu | UCLA
5    | 10/30 | [Reinforcement Learning with Large Datasets: a Path to Resourceful Autonomous Agents](#week5) [[slides](https://www.dropbox.com/scl/fi/fbl1k9hyhp6vuok41npyo/5-Sergey-Levine-Reinforcement-Learning-with-Large-Datasets-a-Path-to-Resourceful-Autonomous-Agents.pdf?rlkey=enzxo9lk3xdlvvdn5y4fxezy5&dl=0)] [[recording](https://www.dropbox.com/scl/fi/u54gy0528p7dml45ul7fb/5-Sergey-Levine-Reinforcement-Learning-with-Large-Datasets-a-Path-to-Resourceful-Autonomous-Agents.mp4?rlkey=t5b8rjp3c75t1uwv0ulp4q8po&dl=0)] | Sergey Levine | UC Berkeley
6    | 11/06 | [Scaling Data-Constrained Language Model](#week6) [slides] [recording] | Alexander Rush | Cornell
7    | 11/13 | [Reflex or Reflect: When Do Language Tasks Need Slow Reasoning?](#week7) [slides] [recording] | Xiang Ren | USC
8    | 11/20 | [Possible Impossibilities and Impossible Possibilities](#week8) [slides] [recording] | Yejin Choi | University of Washington
9    | 11/27 | [Title TBD](#week9) [slides] [recording]| Taylor Berg-Kickpatrick | UC San Diego
10   | 12/04 | [Title TBD](#week10) [slides] [recording]| Leon Bergen | UC San Diego

## Week 1: Build an Ecosystem, Not a Monolith {#week1}

### Abstract

Currently, the preeminent paradigm for building artificial intelligence is the development of large, general-purpose models that aim to be able to perform all tasks at (super)human level. In this talk, I will argue that an ecosystem of specialist models would likely be dramatically more efficient and could be significantly more effective. Such an ecosystem could be built collaboratively by a distributed community and be continually expanded and improved. In this talk, I will outline some of the technical challenges involved in creating model ecosystems, including automatically selecting which models to use for a particular task, merging models to combine their capabilities, and efficiently communicating changes to a model.
Bio: Colin Raffel is an associate professor at the University of Toronto and a faculty researcher at Hugging Face. His work aims to make it easy to get computers to do new things.

### Speaker Bio

Colin Raffel is an associate professor at the University of Toronto and a faculty researcher at Hugging Face. His work aims to make it easy to get computers to do new things.

## Week 2: Language agents: a critical evolutionary step of AI {#week2}

### Abstract

A heated ongoing discussion in AI is language agents that, powered by large language models (LLMs), can follow instructions to autonomously carry out complex tasks in real-world environments. However, the concept of agent has been introduced into AI for decades, so what's different this time around? I argue that a fundamental change is the capability of using language as a vehicle for both thought and communication, a trait that was unique to humans. Language was immensely critical for the evolution of biological intelligence, and now artificial intelligence seems to be following a similar evolutionary path.

In this talk, I will first describe a possible conceptual framework for language agents and touch on important topics such as memory, tool use, grounding, and reasoning. I will then briefly introduce several of our recent work on language agents, including 1) Mind2Web, that aims to develop generalist language agents for real-world website, 2) LLM-Planner, that leverages LLMs for robot planning to interact with physical environments, and 3) Pangu, a generic neurosymbolic framework for developing language agents for different environments, which features a symbolic agent and a neural LM working in a concerted fashion.

### Speaker Bio

Yu Su is a Distinguished Assistant Professor of Engineering at the Ohio State University. He obtained his Ph.D. from University of California, Santa Barbara and his bachelor's degree from Tsinghua University. He co-directs the OSU NLP group and serves in leadership roles in multiple national AI institutes. He has broad interests in developing artificial intelligence, with a primary interest in the role of language as a vehicle of thought and communication. His research has received Outstanding Paper Awards from ACL and COLING and his work at Microsoft has led to a new conversational interface for Microsoft Outlook.

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

## Week 5: Reinforcement Learning with Large Datasets: a Path to Resourceful Autonomous Agents {#week5}

### Abstract

How can we build autonomous agents that benefit from large-scale (pre-)training while still exhibiting emergent and flexible behavior? In this talk, I will discuss recent innovations in terms of algorithms, models, and large scale applications that can bring us closer to uniting the power of large datasets with the flexibility of reinforcement learning, to make it possible to train systems that can generalize as broadly as large-scale supervised systems while solving new problems in new ways. I will discuss the algorithmic foundations of offline reinforcement learning, discuss applications in robotics, language modeling, and image generation, and present some recent large-scale robotic learning efforts that provide us with a preview of what such future autonomous systems might look like.

### Speaker Bio

Sergey Levine received a BS and MS in Computer Science from Stanford University in 2009, and a Ph.D. in Computer Science from Stanford University in 2014. He joined the faculty of the Department of Electrical Engineering and Computer Sciences at UC Berkeley in fall 2016. His work focuses on machine learning for decision making and control, with an emphasis on deep learning and reinforcement learning algorithms. Applications of his work include autonomous robots and vehicles, as well as applications in other decision-making domains. His research includes developing algorithms for end-to-end training of deep neural network policies that combine perception and control, scalable algorithms for inverse reinforcement learning, deep reinforcement learning algorithms, and more.

## Week 6: Scaling and Aligning Open Language Models {#week6}

### Abstract

I will discuss two recent works related to the development of practical open-source Language Models. 1) Scaling - Extrapolating scaling trends suggest that training dataset size for LLMs may soon be limited by the amount of text data available on the internet. We run a set of empirical experiments varying the extent of data repetition and compute budget, and we propose an empirical scaling law for compute optimality that accounts for the decreasing value of repeated tokens and excess parameters. 2) Aligning - Model distillation has proven a promising technique for improving small open-source language models, but the resulting models are unwieldy to use in conversational settings.  We show a simple method for "aligning" language models to user intents through distilled direct preference alignment. 

### Speaker Bio

Alexander "Sasha" Rush is an Associate Professor at Cornell Tech and a researcher at Hugging Face. His interest is in language modeling, specifically in controllable text generation, efficient inference, and robustness. He has written several popular open-source projects including tools for NLP, puzzles to learn deep learning, and virtual conference software. His projects have received awards at NLP, visualization, and hardware conferences, an NSF Career Award, and Sloan Fellowship. Recently he helped launch COLM, a new conference on language modeling.

## Week 7: Reflex or Reflect: When Do Language Tasks Need Slow Reasoning? {#week7}

### Abstract

Large language models, such as GPT-3, excel at generating reflexive responses that mimic human-like language, but they fall short when it comes to complex reasoning that requires slower thinking, deeper reflection and a nuanced interpretation of language. This talk will share two lines of efforts in approaching the above problem. In the first part, I will introduce RICA and RobustRL, two benchmarks that expose language models to logical robustness challenges in language inference. The second part presents our exploration on transferring the Chain-of-Thoughts ability to smaller language models while enhancing model's logical consistency. We show that a smaller, distilled LM can yield dramatically better task accuracy and rationale-prediction consistency.

### Speaker Bio

Xiang Ren is an associate professor and Viterbi Early Career Chair at the USC Computer Science Department, a Research Team Leader at USC ISI, and the director of the Intelligence and Knowledge Discovery (INK) Lab at USC. Priorly, he spent time as a research scholar at the Stanford University and received his Ph.D. in Computer Science from the University of Illinois Urbana-Champaign. Ren's research seeks to build generalizable natural language processing (NLP) systems which can handle a wide variety of language tasks and situations. He works on new algorithms and datasets to make NLP systems cheaper to develop and maintain, arm machine models with common sense, and improve model's transparency and reliability to build user trust. His research work has received several best paper awards in top NLP and AI conference venues. Ren has been awarded a NSF CAREER Award, multiple faculty research awards from Google, Facebook, Amazon, JP Morgan and Sony, and the 2018 ACM SIGKDD Doctoral Dissertation Award.

## Week 8: Possible Impossibilities and Impossible Possibilities {#week8}

### Abstract

In this talk, I will question if there can be possible impossibilities of large language models  (i.e., the fundamental limits of transformers, if any) and the impossible possibilities of language models (i.e., seemingly impossible alternative paths beyond scale, if at all). 

### Speaker Bio

Yejin Choi is Wissner-Slivka Professor and a MacArthur Fellow at the Paul G. Allen School of Computer Science & Engineering at the University of Washington. She is also a senior director at AI2 overseeing the project Mosaic and a Distinguished Research Fellow at the Institute for Ethics in AI at the University of Oxford. Her research investigates if (and how) AI systems can learn commonsense knowledge and reasoning, if machines can (and should) learn moral reasoning, and various other problems in NLP, AI, and Vision including neuro-symbolic integration, language grounding with vision and interactions, and AI for social good. She is a co-recipient of 2 Test of Time Awards (at ACL 2021 and ICCV 2021), 7 Best/Outstanding Paper Awards (at ACL 2023, NAACL 2022, ICML 2022, NeurIPS 2021, AAAI 2019, and ICCV 2013), the Borg Early Career Award (BECA) in 2018, the inaugural Alexa Prize Challenge in 2017, and IEEE AI's 10 to Watch in 2016.


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