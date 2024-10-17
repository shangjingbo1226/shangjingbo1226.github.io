---
title: "2024-Fall-CSE291-DSC253-Advanced Data-Driven Text Mining"
collection: teaching
type: "Graduate Class"
permalink: /teaching/2024-fall-CSE291-DSC253-TM
venue: "CSE & HDSI, UCSD"
date: 2024-09-26
location: "La Jolla, CA"
---

**Class Time**: Tuesdays and Thursdays, 8:00 to 9:20 AM.  **Room**: PCYNH 122.  **Piazza**: [piazza.com/ucsd/fall2024/cse291dsc253](https://piazza.com/ucsd/fall2024/cse291dsc253)


Online Lecturing for First Week
======

To offer waitlist students opportunities to learn more about this course, we deliver the first two lectures over Zoom: [https://ucsd.zoom.us/j/98881116686](https://ucsd.zoom.us/j/98881116686). The lectures will be recorded. 

Overview
======

This course mainly focuses on introducing current methods and models that are useful in analyzing and mining real-world text data. It will put emphasis on unsupervised, weakly supervised, and distantly supervised methods for text mining problems, including information retrieval, open-domain information extraction, text summarization (both extractive and generative), and knowledge graph construction. Bootstrapping, comparative analysis, learning from seed words and existing knowledge bases will be the key methodologies.

There is no textbook required, but there are recommended readings for each lecture (at the end of the slides).

- You **MUST enroll for 4 units**
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
    - Zi Lin (zil061 AT ucsd.edu)
        - Office Hour: Wednesdays, 1 to 2 PM
        - Location: [https://ucsd.zoom.us/j/96282267255?pwd=ar8XzmnTpiAEFxvaIhaBGPG1NmaSRt.1](https://ucsd.zoom.us/j/96282267255?pwd=ar8XzmnTpiAEFxvaIhaBGPG1NmaSRt.1)
    - Weitang Liu (wel022 AT ucsd.edu)
        - Office Hour: Fridays, 1 to 2 PM
        - Location: CSE B275.


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
0    | 09/26 (Thu) | [Intro, Logistics, and Course Project](https://www.dropbox.com/scl/fo/6y609qa8dy2h1kl1j2rm5/ADYrb3Yl6RmrN46wcWD9S9k?rlkey=5fznuq20vduxne42yyrakkh85&dl=0) |
1    | 10/01 (Tue) | [Basics: Zipf's Law, Bags-of-words, and TF-IDF](https://www.dropbox.com/scl/fo/lka07lp13zqjautotlkq7/AFx01Bm0LKt2fSIgpv1-Uzw?rlkey=lksd0co3myuz6vi21sddxuliw&dl=0) | HW1 out
1    | 10/03 (Thu) | [Word Embedding: word2vec and GloVe](https://www.dropbox.com/scl/fo/wg2aadj8gw42twi6akur9/AER1Bdybcv-oGHLBb4f5XCE?rlkey=nd2ttg8pcz3iemr6krgyds69n&dl=0) |
2    | 10/08 (Tue) | [Language Models: from N-Gram to Neural LMs](https://www.dropbox.com/scl/fo/rv94mgonb9jh6y95kg45m/AJlsMosOO7PcegyfSzkKbh0?rlkey=4qkcecj4b7fjagxkbcdcjfooy&dl=0) |
2    | 10/10 (Thu) | [Information Retrieval: from BM25 to Learning to Rank](https://www.dropbox.com/scl/fo/jxqq1b69bb8xhxz9nee6f/AAtDhuciqrZpY-OujH9WNGs?rlkey=o1n4jsgkmkwm6ndvc4ws9nt7f&dl=0) | Project Proposal Due (End of the Day)
3    | 10/15 (Tue) | [Sentiment Analysis and Document Classification](https://www.dropbox.com/scl/fo/f67zmfgqebgb38r3b03ra/AC_p4Gu0K32K_X8m-0Sz3A4?rlkey=ket5dorfnntk2cjljr3tjjpvz&dl=0) |
3    | 10/17 (Thu) | [Topic Modeling: PLSA, LDA, and HMM](https://www.dropbox.com/scl/fo/k73zklt4raya3zfuthklm/AIsJqGR0zrqPtVV5pE5HYw4?rlkey=xi8i6fz502sqdmz1k9kjbks0d&dl=0) | HW1 Due, DM challenge roll-out
4    | 10/22 (Tue) | Phrase Mining: from Unigrams to Multi-word Phrases | HW2 out
4    | 10/24 (Thu) | Entity Set Expansion: from Seed Words to Sets |
5    | 10/29 (Tue) | Entity Recognition: from Supervised to Data-Driven |
5    | 10/31 (Thu) | Distant Supervision for Relation Extraction |
6    | 11/05 (Tue) | Text-Rich Network: a Collaboration between Texts and Networks |
6    | 11/07 (Thu) | Topic Taxonomy Construction |
7    | 11/12 (Tue) | Weakly Supervised Text Classification |
7    | 11/14 (Thu) | Learning with Noisy Data | HW2 due
8    | 11/19 (Tue) | Label Bias in Weak Supervision & Few-shot NER | DM challenge due
8    | 11/21 (Thu) | Large Language Models | 
9    | 11/26 (Tue) | Project Presentations                                           |
9    | 11/28 (Thu) | No Class (Thanksgiving Day)                                     |
10   | 12/03 (Tue) | Project Presentations                                           |
10   | 12/05 (Thu) | Project Presentations                                           |

Homework (30%)
======

- **HW1.** [Text Classification with Different Techniques](https://www.dropbox.com/s/m0l9kt39mggc7by/HW-1.zip?dl=1).
    - Due: Oct 17
- **HW2.** Phrase Mining Applications and Future Work. 
    - Due: Nov 14

Data Mining Challenge (30%)
======

It is a individual-based text mining competition with quantitative evaluation. 
The challenge runs **from Oct 17 2024 0:00:01 AM to Nov 19, 2024 4:59:59 PM PT**. Note that the time displayed on Kaggle is in UTC, not PT.

- Challenge Statement, Dataset, and Details: TBD
- Kaggle challenge link: TBD
- Survey to map Kaggle account name to student names: TBD

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
    - **Report due on Dec 8**, End of the day, Pacific Time. 
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
