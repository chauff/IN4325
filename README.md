<img src="img/wordcloud.jpg" width="300px" align="middle">

# IN4325 <!-- omit in toc -->

This repository contains the materials of the **MSc Information Retrieval** course running in 2018/19 at TU Delft (Q3). The project setup is suitable for up to 100 students.

## Table of contents <!-- omit in toc -->
- [Important links](#important-links)
- [Course description](#course-description)
- [Course team](#course-team)
- [ECs](#ecs)
- [Learning objectives](#learning-objectives)
- [:dart: Assessment](#dart-assessment)
  - [Group projects](#group-projects)
  - [Weekly reviews](#weekly-reviews)
- [Final grade](#final-grade)
- [:hourglass: Weekly support hours and interview](#hourglass-weekly-support-hours-and-interview)
  - [Core IR](#core-ir)
  - [Applied NLP](#applied-nlp)
- [:clock130: Course schedule](#clock130-course-schedule)
- [Deadlines](#deadlines)

## Important links

- [Core IR lectures](lecturesCoreIR.md)
- [Core IR project](projectCoreIR.md)
- [Applied NLP lectures](lecturesAppliedNLP.md)
- [Applied NLP project](projectAppliedNLP.md)
- Signing up on Slack: [https://join.slack.com/t/in43252019/signup](https://join.slack.com/t/in43252019/signup)
- Signing up for support and the group interview: [https://queue.ewi.tudelft.nl/](https://queue.ewi.tudelft.nl/)

## Course description

<img style="float:right;" src="img/library.png" width="200px">

Retrieving relevant information and making sense of it are two central activities in modern knowledge-driven societies. As the amount and variety of data increase at an unprecedented rate, access to relevant, usually unstructured information is becoming more and more challenging. The web is now the first stop for many (or most?) information seekers, and web search engines are our key to unlocking that vast and largely unstructured pile of information. 

**But how do search engines actually work?** This is what this course is about. In the **first module** of the course, we focus on **core IR** techniques such as indexing, retrieval models, evaluation metrics and so on. 

In the **second module** of the course we cover natural language processing (NLP) and natural language generation (NLG). While for many years, IR and NLP researchers stayed far away from each other, in recent years the two fields have moved closer together, with search engines using many NLP techniques to enhance the search experience--e.g. by providing automatically generated explanations of search result rankings and by enabling a _dialogue_ to take place between the search engine and user.

The split (core IR / applied NLP) will be made halfway through the course: the first eight lectures cover core IR techniques, the remaining eight lectures cover applied NLP techniques with applications to search in mind. 

## Course team

This distribution also fits the lecturer team of this course: [Associate Prof. Claudia Hauff](https://chauff.github.io/) teaches the core IR lectures, while [Assistant Prof. Nava Tintarev](http://navatintarev.com/) teaches the applied NLP lectures. The course team is completed by a number of PhDs and Postdocs (all from the [Web Information Systems group](http://www.wis.ewi.tudelft.nl/)) who support the course through guest lectures and project supervision and a TA who focuses on the grading of the paper reviews:

- Oana Inel (Postdoc)
- Dimitrios Bountouridis (Postdoc)
- Gustavo Penha (PhD student)
- Arthur Camara (PhD student)
- Shabnam Najafian (PhD student)
- Felipe Moraes (PhD student)
- Nirmal Roy (TA)

Claudia and Nava are the responsible instructors of this course and can jointly be reached at **in4325-ewi@tudelft.nl**.

The whole course team can also be found on a dedicated [Slack channel](https://join.slack.com/t/in43252019/signup) - join it to get quick feedback on questions/issues. You have to use your `@student.tudelft.nl` email address to join!

## ECs

This is a **5 EC course**, with **140 hours** of course work in total. We expect you to spread the load evenly across the 9 course weeks.

## Learning objectives

- Describe the different **information retrieval models**, and compare their strengths and weaknesses.
- Describe and implement different **indexing techniques**.
- Describe and analyze **querying techniques** with respect to their most suited application domains.
- Analyze the effectiveness of an information retrieval system through proper use of **evaluation metrics**.
- **Design and implement/improve a search system**, possibly using advanced social and semantic search functionalities. Support and defend the relevance and correctness the choices with regards to the adopted information retrieval model, indexing technique, and querying technique.
- Describe common **natural language generation models**, and analyse their application in different domains.
- Design and develop **natural language processing** applications.
- **Evaluate** natural language processing applications in different task contexts.
- Illustrate suitable application scenarios for advanced natural language processing topics such as **natural language queries** and **summarization**.

## :dart: Assessment

This course has no final exam, instead the grade is largely determined through three components: 

1. a group project core IR.
2. a group project applied NLP.
3. individual review activities.

**All assessment items (reviews, projects reports) have to be submitted via Brightspace.**

### Group projects

The group projects follow each other. During the first 5 course weeks, the group tackles the [core IR project](projectCoreIR.md) (reproducing a research paper essentially), during the second 5 weeks of the course the group tackles the [applied NLP project](projectAppliedNLP.md).

Group size:
- Core IR (2-3)
- Applied NLP (3-4)

The differences in group sizes will be taken into account during grading. 

At the end of each project phase we will conduct a short interview (15 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. We have two project phases (core IR and applied NLP), so each group will have one interview in week 5 and week 9 (*tentatively*).

### Weekly reviews

Most lectures are accompanied by **one required reading**, which is usually a scientific paper. For every required reading you are asked to write a *review*. These review activities are individual work.

Each review is graded as either *excellent*, *sufficient* or *insufficient*. In order to pass the course, 9 of the 14 offered review opportunities have to be passed with at least *sufficient*. Use the provided [review template](reviewForm.md) and follow its instructions. Reviews are submitted via Brightspace.

## Final grade

<img src="img/grading.png" width="400px">

Each of the two project phases is worth 45% of the final grade, consisting of the following parts:
- Report writing, background & context:  10%
- Report technical correctness: 10%
- Report results & discussion: 10%
- Interview (understanding, insights): 15%

The paper review is worth 10% of the final grade. We take the 9 best review grades you have achieved (which at minimum should be 9x *sufficient* and at best can be 9x *excellent*) and convert them into points: 1 point per *sufficient* and 2 points per *excellent*. 18 points (i.e. 9x *excellent*) is a grade of 10, 9 points (i.e. 9x *sufficient*) is a grade of 6. Points between 9 and 18 are converted to grades in a linear fashion.

In order to pass this course, you need to fullfil **all** of the following:
1. Receive an overall grade of 5.8 or higher (in alignment with TU Delft's exam regulations). 
2. Complete both project phases with at least a grade of 5.0.
3. Receive a *sufficient* for at least 9 of the 14 reviews.



## :hourglass: Weekly support hours and interview

We do not have fixed lab hours. Due to the heavy emphasis on project work in this course, we offer weekly support hours: 

### Core IR 
During weeks 3.2 to 3.5 between 9am and 11:30am at least three staff members will be available to help groups with their IR project. You can sign up for 15 minute timeslots on TU Delft's queue system: head to https://queue.ewi.tudelft.nl/ and look for `IN4325`. You should see something along those lines:

<img src="img/queue.png" width="600px">

Click on the day you want to get support and then *enroll* for a particular timeslot. Per group, please pick only one timeslot per week. The support hours are offered in building 28, please come to the waiting area near room E04.100 (Claudia Hauff's office). As you can see in the image, the 
**core IR interviews** on March 14/15 are also scheduled this way. *Once again: one timeslot per group!*

### Applied NLP
During weeks 3.6 to 3.8 between 9am and 11:30am at least two staff members will be available to help groups with their NLP projects. You can sign up for 15 minute timeslots on TU Delft's queue system: https://queue.ewi.tudelft.nl/

The support hours are offered in building 28, please come to the waiting area near room W04.900 (Nava Tintarev's office).
**NLP interviews** on April 11/12 are also scheduled this way. *Once again: one timeslot per group!*

## :clock130: Course schedule

The lecture locations have been taken from [TUD's timetable site](https://mytimetable.tudelft.nl/) on February 11, 2019.
**Check your timetable for the latest location of each lecture, we are getting to know the campus in this course!** :bike: :bike: :bike:

| Week | Thursday lecture                  | Friday lecture                    | Group project          | No. of reviews |
|------|-----------------------------------|-----------------------------------|------------------------|--------------|
| 3.1  | IR evaluation (`EWI hall Pi`, C. Hauff)          | Retrieval models (`EWI hall Pi`, C. Hauff)       |   Project group settled                     | 1            |
| 3.2  | IR indexing (`Aula CZ C`, C. Hauff)            | Query refinement (`EWI hall Pi`, F. Moraes)      |   Core IR project settled                     | 2            |
| 3.3  | Interactive IR (`Aula CZ C`, C. Hauff)         | Personalization (`EWI hall Pi`, C. Hauff)        |                        | 2            |
| 3.4  | Learning to rank (`Aula CZ C`, C. Hauff)       | Neural IR (`DUWO CZ`, A. Camara)             |             Intermediate core IR report due           | 2            |
| 3.5  | NLP introduction (`Aula CZ C`, N. Tintarev)    | Text analysis (`3mE-CZ B`, N. Tintarev)                 | Final core IR report due / interviews. Project group settled (NLP)| 1            |
| 3.6  | Semantics (`Aula CZ C`, N. Tintarev) | Evaluation NLP (`3mE-CZ B`, N. Tintarev)       |      Applied NLP project settled                  | 2            |
| 3.7  | ML for NLP (`Aula CZ C`, N. Tintarev)  | Language generation (`3mE-CZ B`, N. Tintarev) |                        | 2            |
| 3.8  | NLP annotations (`Aula CZ C`, O. Inel)           | Word embeddings (`CT-CZ E`, N. Tintarev)     |   Intermediate applied NLP report due                     | 2            |
| 3.9  |                                   |                                   |               applied NLP report due/interviews         |              |
| 3.10 |                                   |                                   |  |              |

We start off in weeks 3.1 to 3.4 with the [core IR module](lecturesCoreIR.md), alongside which the [core IR group project](projectCoreIR.md) runs. In week 3.5 we switch to the [applied NLP module](lecturesAppliedNLP.md), alongside which the [applied NLP group project](projectAppliedNLP.md) runs.

## Deadlines

This course has a number of smaller (the paper reviews :small_blue_diamond:) and larger (anything to do with the group projects :small_orange_diamond:) deadlines. They are listed here in order of **due date**. The deadlines are always at 23:59 CET (i.e. local time) of the respective deadline day. We rely on Brigthspace for submission. Brightspace submissions close automatically, be sure to not be late.

Reminder of the rules:
- You need to pass 9 out of 14 reviews with a grade of *sufficient*.
- The project proposal and intermediate report submissions are required, but are **not** graded. The proposal has to be signed off by an instructor (does it fit the project goals? is the scope sufficient?). The intermediate proposal can be a last chance for feedback. Submit whatever you have at that point.

**Core IR lecture weeks (the final deadline is in week 3.5):**

:small_blue_diamond: Review P1: handed out February 15, **due February 22**.

:small_orange_diamond: Core IR project proposal: **due February 22**.

:small_blue_diamond: Review P2: handed out February 21, **due February 28**.

:small_blue_diamond: Review P3: handed out February 22, **due March 1**.

:small_blue_diamond: Review P4: handed out February 28, **due March 7**.

:small_blue_diamond: Review P5: handed out March 1, **due March 8**.

:small_orange_diamond: Core IR intermediate project report: **due March 8**.

:small_orange_diamond: Core IR final project report: **due March 13**.

:small_blue_diamond: Review P6: handed out March 7, **due March 14**.

:small_blue_diamond: Review P7: handed out March 8, **due March 15**.

:small_orange_diamond:: Core IR project interviews: **March 14** and **March 15**.


**Applied NLP lecture weeks (the final deadline is in week 3.9):**

:small_blue_diamond: Review P8: handed out March 15, **due March 22**.

:small_orange_diamond: NLP project proposal: **due March 22**.

:small_blue_diamond: Review P9: handed out March 21, **due March 28**.

:small_blue_diamond: Review P10: handed out March 22, **due March 29**.

:small_blue_diamond: Review P11: handed out March 28, **due April 4**.

:small_blue_diamond: Review P12: handed out March 29, **due April 5**.

:small_orange_diamond: NLP intermediate project report: **due April 5**.

:small_orange_diamond: NLP final project report: **due April 10**.

:small_blue_diamond: Review P13: handed out April 4, **due April 11**.

:small_blue_diamond: Review P14: handed out April 5, **due April 12**.

:small_orange_diamond: NLP project interviews: **April 11** and **April 12**.
