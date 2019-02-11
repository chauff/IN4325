# IN4325

This is an overview of the **Information Retrieval** (IR) course running in 2018/19 at TU Delft (Q3).

## Course description

Retrieving relevant information and making sense of it are two central activities in modern knowledge-driven societies. As the amount and variety of data increase at an unprecedented rate, access to relevant, usually unstructured information is becoming more and more challenging. The web is now the first stop for many (or most?) information seekers, and web search engines are our key to unlocking that vast and largely unstructured pile of information. 

**But how do search engines actually work?** This is what this course is about. In the **first half** of the course, we focus on **core IR** techniques such as indexing, retrieval models, evaluation metrics and so on. 

In the **second half** of the course we cover natural language processing (NLP) and natural language generation (NLG). While for many years, IR and NLP researchers stayed far away from each other, in recent years the two fields have moved closer together, with search engines using many NLP techniques to enhance the search experience--e.g. by providing automatically generated explanations of search result rankings and by enabling a _dialogue_ to take place between the search engine and user.

The split (core IR / applied NLP) will be made halfway through the course: the first eight lectures cover core IR techniques, the next eight lectures cover applied NLP techniques with applications to search in mind. 

## Course team

This distribution also fits the lecturer team of this course: [Associate Prof. Claudia Hauff](https://chauff.github.io/) teaches the core IR lectures, while [Assistant Prof. Nava Tintarov](http://navatintarev.com/) teaches the applied NLP lectures. The course team is completed by a number of PhDs and Postdocs (all from the [Web Information Systems group](http://www.wis.ewi.tudelft.nl/)) who support the course through guest lectures and project supervision and a TA who takes care of the peer reviews:

- Felipe Moraes (PhD student)
- Dimitrios Bountouridis (Postdoc)
- Gustavo Penha (PhD student)
- Arthur Camara (PhD student)
- Nirmal Roy (TA).

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

The group projects follow each other. During the first 5 course weeks, the group tackles the core IR project (reproducing a research paper essentially), during the second 5 weeks of the course the group tackles the applied NLP project (which can but does not have to be a follow-up of the IR project).

The group projects are tackled in teams of 2-3 students (this is a *tentative* number and subject to change, depending on the number of students signing up for the course).

At the end of each project phase we will conduct a short interview (10-15 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. We have two project phases, so each group will have one interview in week 5 (*tentatively*) and week 10 (*tentatively*).

### Peer reviews

Most lectures will be accompanied by **one required reading**, which is usually a scientific paper. For every required reading you are asked to write a *peer review*. The peer review is individual work.

Each peer review is graded as either (*excellent*, *sufficient* or *insufficient*). In order to pass the course, 9 of the 14 peer reviews have to be passed with at least *sufficient*.

## Final grade

In line with the study guide, the final grade consists of the following components:

- 60% group project (group work, individually graded)
- 30% literature survey (group work, individually graded)
- 10% peer reviews (individual work)

These components translate into the following setup:

1. The **core IR project** contributes 45% to the final grade (30% project, 15% literature survey)
2. The **applied NLP project** contributes 45% to the final grade (30% project, 15% liteature survey)
3. Teh **peer reviews** contribute 10% to the final grade.

## Course schedule

| Week | Thursday lecture                  | Friday lecture                    | Group project          | Peer reviews |
|------|-----------------------------------|-----------------------------------|------------------------|--------------|
| 3.1  | IR evaluation (C. Hauff)          | Retrieval models (C. Hauff)       |                        | 1            |
| 3.2  | IR indexing (C. Hauff)            | Query refinement (F. Moraes)      |                        | 2            |
| 3.3  | Interactive IR (C. Hauff)         | Personalization (C. Hauff)        |                        | 2            |
| 3.4  | Learning to rank (C. Hauff)       | Neural IR (A. Camara)             |                        | 2            |
| 3.5  | NLP introduction (N. Tintarev)    | POS (N. Tintarev)                 | core IR interviews     | 1            |
| 3.6  | Semantic similarity (N. Tintarev) | Summarization (N. Tintarev)       |                        | 2            |
| 3.7  | Sentiment analysis (N. Tintarev)  | Language generation (N. Tintarev) |                        | 2            |
| 3.8  | AI ethics (N. Tintarev)           | Word embeddings (N. Tintarev)     |                        | 2            |
| 3.9  |                                   |                                   |                        |              |
| 3.10 |                                   |                                   | applied NLP interviews |              |


