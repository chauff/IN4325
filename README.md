# IN4325 <!-- omit in toc -->

This is an overview of the **Information Retrieval** (IR) course running in 2018/19 at TU Delft (Q3).

## Table of contents <!-- omit in toc -->
- [Course description](#course-description)
- [Course team](#course-team)
- [ECs](#ecs)
- [Learning objectives](#learning-objectives)
- [Assessment](#assessment)
  - [Group projects](#group-projects)
  - [Weekly reviews](#weekly-reviews)
- [Final grade](#final-grade)
- [Weekly support hours](#weekly-support-hours)
- [Course schedule](#course-schedule)
- [Deadlines](#deadlines)

## Course description

Retrieving relevant information and making sense of it are two central activities in modern knowledge-driven societies. As the amount and variety of data increase at an unprecedented rate, access to relevant, usually unstructured information is becoming more and more challenging. The web is now the first stop for many (or most?) information seekers, and web search engines are our key to unlocking that vast and largely unstructured pile of information. 

**But how do search engines actually work?** This is what this course is about. In the **first half** of the course, we focus on **core IR** techniques such as indexing, retrieval models, evaluation metrics and so on. 

In the **second half** of the course we cover natural language processing (NLP) and natural language generation (NLG). While for many years, IR and NLP researchers stayed far away from each other, in recent years the two fields have moved closer together, with search engines using many NLP techniques to enhance the search experience--e.g. by providing automatically generated explanations of search result rankings and by enabling a _dialogue_ to take place between the search engine and user.

The split (core IR / applied NLP) will be made halfway through the course: the first eight lectures cover core IR techniques, the next eight lectures cover applied NLP techniques with applications to search in mind. 

## Course team

This distribution also fits the lecturer team of this course: [Associate Prof. Claudia Hauff](https://chauff.github.io/) teaches the core IR lectures, while [Assistant Prof. Nava Tintarov](http://navatintarev.com/) teaches the applied NLP lectures. The course team is completed by a number of PhDs and Postdocs (all from the [Web Information Systems group](http://www.wis.ewi.tudelft.nl/)) who support the course through guest lectures and project supervision and a TA who takes care of the peer reviews:

- Oana Inel (Postdoc)
- Dimitrios Bountouridis (Postdoc)
- Gustavo Penha (PhD student)
- Arthur Camara (PhD student)
- Shabnam Najafian (PhD student)
- Felipe Moraes (PhD student)
- Nirmal Roy (TA)

Claudia and Nava are the responsible instructors of this course and can jointly be reached at **in4325-ewi@tudelft.nl**.

## ECs

This is a **5 EC course**, with **140 hours** of course work in total. We expect you to spread the load evenly across the 10 weeks with 14 hours of work per week. 

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

## Assessment

This course has no final exam, instead the grade is largely determined through three components: 

1. a group project core IR (which includes a small literature survey)
2. a group project applied NLP (which includes a small literature survey)
3. individual peer-review activities.

### Group projects

The group projects follow each other. During the first 5 course weeks, the group tackles the [core IR project](projectCoreIR.md) (reproducing a research paper essentially), during the second 5 weeks of the course the group tackles the applied NLP project (which can but does not have to be a follow-up of the IR project).

The group projects are tackled in teams of 2-3 students (this is a *tentative* number and subject to change, depending on the number of students signing up for the course).

At the end of each project phase we will conduct a short interview (10-15 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. We have two project phases, so each group will have one interview in week 5 (*tentatively*) and week 10 (*tentatively*).

You are expected to work within the same group for both project parts.

### Weekly reviews

Most lectures will be accompanied by **one required reading**, which is usually a scientific paper. For every required reading you are asked to write a *review*. This weekly review activity (also known as *active reading*) is individual work.

Each review is graded as either (*excellent*, *sufficient* or *insufficient*). In order to pass the course, 9 of the 14 peer reviews have to be passed with at least *sufficient*. The review template can be found [here](reviewForm.md).

## Final grade

1. The **core IR project** contributes 45% to the final grade.

2. The **applied NLP project** contributes 45% to the final grade.
   
3. The **peer reviews** contribute 10% to the final grade. 

In order to pass this course, you need (1) to receive a 5.8 grade or higher, (2) complete both projects with at least a grade of 5.0 and (3) receive a *sufficient* for at least 9 of the 14 peer reviews.

## Weekly support hours

We do not have fixed lab hours. Due to the heavy emphasis on project work in this course, we offer weekly support hours: 

- **core IR**: during weeks 3.2 to 3.5 between 9am and 11:30am at least two staff members will be available to help groups with their IR project (maybe more, depending on the need). We will release a Doodle to allow groups to sign up for 15 minute timeslots.
- **applied NLP**: tbd.

## Course schedule

The lecture locations have been taken from [TUD's timetable site](https://mytimetable.tudelft.nl/) on February 11, 2019.
**Check your timetable for the latest location of each lecture, we are getting to know the campus in this course!**

| Week | Thursday lecture                  | Friday lecture                    | Group project          | Peer reviews |
|------|-----------------------------------|-----------------------------------|------------------------|--------------|
| 3.1  | IR evaluation (`EWI hall Pi`, C. Hauff)          | Retrieval models (`EWI hall Pi`, C. Hauff)       |   Project group settled                     | 1            |
| 3.2  | IR indexing (`Aula CZ C`, C. Hauff)            | Query refinement (`EWI hall Pi`, F. Moraes)      |   Core IR project settled                     | 2            |
| 3.3  | Interactive IR (`Aula CZ C`, C. Hauff)         | Personalization (`EWI hall Pi`, C. Hauff)        |                        | 2            |
| 3.4  | Learning to rank (`Aula CZ C`, C. Hauff)       | Neural IR (`DUWO CZ`, A. Camara)             |                        | 2            |
| 3.5  | NLP introduction (`Aula CZ C`, N. Tintarev)    | Text analysis (`3mE-CZ B`, N. Tintarev)                 | core IR report due / interviews     | 1            |
| 3.6  | Semantics (`Aula CZ C`, N. Tintarev) | Evaluation NLP (`3mE-CZ B`, N. Tintarev)       |                        | 2            |
| 3.7  | ML for NLP (`Aula CZ C`, N. Tintarev)  | Language generation (`3mE-CZ B`, N. Tintarev) |                        | 2            |
| 3.8  | AI ethics (??, N. Tintarev)           | Word embeddings (`3mE-CZ B`, N. Tintarev)     |                        | 2            |
| 3.9  |                                   |                                   |                        |              |
| 3.10 |                                   |                                   | applied NLP interviews |              |

## Deadlines

This course has several deadlines, here we list them all in one place. Every deadlines requires a submission on Brightspace. Deadlines cannot be extended.

- *
3.2
3.3
3.4
3.5

