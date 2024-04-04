---
title: "2024-Spring-CSE291-DSC253-Advanced Data-Driven Text Mining"
collection: teaching
type: "Graduate Class"
permalink: /teaching/2024-spring-CSE291-TM
venue: "CSE, UCSD"
date: 2024-04-02
location: "La Jolla, CA"
---

**Class Time**: Tuesdays and Thursdays, 9:30 to 11:50 AM.  **Room**: CENTER 222.  **Piazza**: [piazza.com/ucsd/spring2024/cse291dsc253](https://piazza.com/ucsd/spring2024/cse291dsc253)


Online Lecturing for First Week
======

To offer waitlist students opportunities to learn more about this course, in the first week, we deliver the lecture over Zoom: [https://ucsd.zoom.us/j/98881116686](https://ucsd.zoom.us/j/98881116686). The lectures will be recorded. 

Overview
======

This course mainly focuses on introducing current methods and models that are useful in analyzing and mining real-world text data. It will put emphasis on unsupervised, weakly supervised, and distantly supervised methods for text mining problems, including information retrieval, open-domain information extraction, text summarization (both extractive and generative), and knowledge graph construction. Bootstrapping, comparative analysis, learning from seed words and existing knowledge bases will be the key methodologies.

There is no textbook required, but there are recommended readings for each lecture (at the end of the slides).

- You MUST enroll for 4 units
    - We need your time commitment for projects
    - Feel free to audit the course with 0 unit


Prerequisites
======

Knowledge about Machine Learning and Data Mining; Comfortable coding using Python, C/C++, or Java; Math and Stat skills.

TA and Office Hours
======

- Jingbo Shang
    - Office Hour: Wednesdays, 10 AM to 11 AM
    - Zoom link: [https://ucsd.zoom.us/my/jshang](https://ucsd.zoom.us/my/jshang)

- **TAs**:
    - Yu Wang (yuw164 AT ucsd.edu)
        - Office Hour: Thursdays 3 to 4 PM
        - Location: CSE 4109
    - Parjanya Prashant
        - Office Hour: Mondays 9 to 10 AM
        - Location: https://ucsd.zoom.us/j/94573427099


Note: all times are in **Pacific Time**.

Grading
======

- Homework: 30%. There will be two homework assignments. 15% each. 
- Text Mining Challenge: 30%.
- Project: 40%.
- You should complete all work individually, except for the Project.
- Late submissions are NOT accepted.

Lecture Schedule
======

**Recording Note**: Please download the recording video for the full length. Dropbox website will only show you the first one hour.

**HW Note**: All HWs due by the end of the day, Pacific Time. 

Week | Date        | Topic & Slides                                                  | Events
1    | 04/02 (Tue) | [Intro, Logistics, and Course Project](https://www.dropbox.com/scl/fo/yuej9ktwybceglwhf072j/h?rlkey=abv2spzi8jh462teus871dkop&dl=0) |
1    | 04/04 (Thu) | [Basics: Zipf's Law, Bags-of-words, and TF-IDF](https://www.dropbox.com/scl/fo/exrxk1sf9tfluh479obt4/h?rlkey=377l1qyuama4vyrpxye9vamsu&dl=0) | HW1 out
2    | 04/09 (Tue) | Word Embedding: word2vec and GloVe |
2    | 04/11 (Thu) | Language Models: from N-Gram to Neural LMs |
3    | 04/16 (Tue) | Information Retrieval: from BM25 to Learning to Rank | Project Proposal Due (End of the Day)
3    | 04/18 (Thu) | Sentiment Analysis and Document Classification |
4    | 04/23 (Tue) | Topic Modeling: PLSA, LDA, and HMM | HW1 Due, DM challenge roll-out
4    | 04/25 (Thu) | Phrase Mining: from Unigrams to Multi-word Phrases | HW2 out
5    | 04/30 (Tue) | Entity Set Expansion: from Seed Words to Sets |
5    | 05/02 (Thu) | Entity Recognition: from Supervised to Data-Driven |
6    | 05/07 (Tue) | Distant Supervision for Relation Extraction |
6    | 05/09 (Thu) | Text-Rich Network: a Collaboration between Texts and Networks |
7    | 05/14 (Tue) | Topic Taxonomy Construction |
7    | 05/16 (Thu) | Weakly Supervised Text Classification |
8    | 05/21 (Tue) | Learning with Noisy Data | HW2 due
8    | 05/23 (Thu) | Label Bias in Weak Supervision & Few-shot NER | DM challenge due
9    | 05/28 (Tue) | Large Language Models | 
9    | 05/30 (Thu) | Project Presentations                                           |
10   | 06/04 (Tue) | Project Presentations                                           |
10   | 06/06 (Thu) | Project Presentations                                           |

Homework (30%)
======

- **HW1.** Text Classification with Different Techniques.
    - Due: April 23
- **HW2.** Phrase Mining Applications and Future Work. 
    - Due: May 21

Data Mining Challenge (30%)
======

It is a individual-based text mining competition with quantitative evaluation. 
The challenge runs **from April 23 2023 0:00:01 AM to May 23, 2023 4:59:59 PM PT**. Note that the time displayed on Kaggle is in UTC, not PT.

- Challenge Statement, Dataset, and Details: TBD
- Kaggle challenge link: TBD
- [Survey to map Kaggle account name to student names](https://docs.google.com/forms/d/e/1FAIpQLSdHf-65yxD9aiKcDEz0ql1Knm84gHqAwLx34p1Bdw8prvDBzQ/viewform?usp=sf_link)

Project (40%)
======

**Overview**
- Team-Based Open-Ended Project
    - 1 to 4 members per team. More members, higher expectation.
    - 3 to 4 members are recommended, given the limited presentation slots.

**Final Deliverables**
- Project Proposal (5%) [instruction](https://www.dropbox.com/s/vtct1ihynpouqcx/CSE291_Text_Mining___Project_Proposal.pdf?dl=0)
    - Define your own research problem and justify its importance
    - Be ambitious! We could aim for ACL/EMNLP conference!
- Research Paper (20%)
    - **Report due on Jun 9**, End of the day, Pacific Time. 
    - Write a 5 to 9 pages report (research-paper like following ACL template). The pages here do not include references.
    - Come up with your hypothesis and find some datasets for verification
    - Design your own models or try a large variety of existing models
    - Submit your codes and datasets; Github repos are welcome
    - Up to 5% bonus for working demos/apps towards the total course grades
- Presentation (20%)
    - The orders will be decided randomly after the teams are formed.
    - The slides must be ready 2 days before the presentation date. So other students can have the access and think about questions.
    - The presentation follows a typical conference style: 20 mins for each team including Q&A
- Question Asking and Handling (5%)
    - Asking questions is an important part of research. You are strongly encouraged to ask 
    questions to other teams. It will be a part of your presentation grade.
    - Handling questions is also an important skill for researchers. 
