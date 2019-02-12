# Core IR project

There are three expected outputs:

1. **Project proposal** (mandatory, but ungraded - you will receive feedback).
2. **Intermediate project report** (mandatory, but ungraded - you will receive feedback).
3. **Final project report** (mandatory, graded).

You can choose between two types of projects: reproducing a human-in-the-loop IR paper or investigating a research idea of your own.

## 1. Reproducing a human-in-the-loop IR paper

You first choose a published paper that describes an IR experiment that involves actual users. We have a list of papers that are well suited for this project below, but of course you can also suggest to reproduce another one.
You then implement and execute the experiments described in the paper, analyze your results and discuss them in light of the original paper's results. 
Note that reproducibility does not mean to create an exact replica of the original paper (that would be replicability), instead [reproducibility](https://www.acm.org/publications/policies/artifact-review-badging) asks the question whether the idea is reproducible by a different team, a slightly different experimental setup and independently developed artifacts. 
[This interesting paper](https://pdfs.semanticscholar.org/b95a/11620929f1c4760587ac99a8d6b4d8cbc547.pdf) on algorithm reproducibility (in particular Table 2!) may give you inspirations for what to look out for in terms of reproducibility.

*Why should you choose this project type?* Because human-in-the-loop IR experiments require you to understand and apply the whole breadth of IR: starting from finding the right search system to use (or implement from scratch), to the right document collection, implementation and evaluation of user logs.

Replication can be a lot of fun and yes, [it sometimes looks like this](https://twitter.com/DevilleSy/status/958761021421903872)!

### List of human-in-the-loop IR papers

*These papers have different lengths (some are 4 pages, some are 10+ pages). While it is feasible to attempt to reproduce a 4 page paper, for the 10+ page papers, you have to make a selection of the paper aspects to reproduce; use the proposal to argue for your decisions.*

- [QWERTY: The Effects of Typing on Web Search Behavior](http://marksanderson.org/publications/my_papers/CHIIR2018-Kevin.pdf)
- 


## 2. Investigating a research idea of your own choice

You can also propose a research project that covers a *core IR topic* of your own choice in consultation with the instructor (it can be a novel idea or involve reproducing an existing paper). One possibility is the participation in a benchmark task. The most popular benchmarks are hosted at [TREC](http://trec.nist.gov/) (and we do have many TREC corpora available). Alternatively, take a look at recent conference proceedings of major IR conferences:

- WSDM: International Conference on Web Search and Data Mining
- SIGIR: International Conference on Research and Development in Information Retrieval
- CIKM: Conference on Information and Knowledge Management
- CHIIR: Conference on Human Information Interaction and Retrieval
- ECIR: European Conference on Information Retrieval.

*Why should you choose this project type?* Because not all IR topics are covered in the lectures in depth and you can investigate them further by choosing them as your research project.

## Restrictions

Based on prior experience we put the following restrictions on your choice of project, no matter if you reproduce a paper or follow your own research idea:

- **You can only conduct a project on neural IR if you have succesfully completed the Deep Learning course beforehand.**
- Your project needs to have a **major IR component** (implementing a retrieval model, a query suggestions approach, a collaborative search engine interface, etc.).
- The project makes use of an actual search engine.
- The project focuses on **textual data** (not video/audio/genomics/.... data).

We have a first deadline in week 3.2, so you will get early feedback on the suitability of your proposal.

## Report formats

### Project proposal

The proposal should contain between 300 and 400 words. Your proposal should address the following points:

1. Problem description: which problem will you tackle and what is interesting about the problem? If you reproduce a paper make sure to reference the original paper.
2. Resources: which data and tools will you be using (this includes also existing implementations of algorithms
3. Methodology: if you choose to reproduce a paper, tell us which part of the paper (if not all) you will reproduce; if you choose your own research idea, tell us what type of algorithm/approach you are proposing and what your baseline(s) will be
4. Background readings: list at least 5 related papers that you will read to add context to your research
5. Evaluation: how will you evaluate your algorithm/approach? Which evaluation metrics will you use?

**Submission**: every group uploads their proposal on Brightspace. The proposal should be in PDF format and should contain the group name and the list of group members (name, student IDs).

**Feedback**: the course team will provide feedback on the project proposal within a few days.

### Intermediate and final project report

The **final** group project report should be **7-8 pages** long in the [SIGCHI proceedings format](https://sigchi.org/templates/) (available as LaTeX and Word templates). The **intermediate** project report is likely to be shorter (it is due a week before the final deadline), that is fine, submit whatever you have by then.

We suggest the following report structure:

- Title, authors
- Abstract
- Introduction: problem statement, motivation for the problem, overall plan to tackle the problem
- Background: what important works does this project build on
- Approach: what methods/algorithms did you use
- Experiments: describe your experiments, the results and discuss them
- Conclusions: describe what you learnt/found and what avenues for future work you see
- References

The final report should also contain a link to a repository (or several) that contain the software you created, the scripts you used to analyze your data, etc.

Submission: every group uploads their intermediate and final group project reports on Brightspace. The reports should be in PDF format. Note that after submission a plagiarism check is executed by Turnitin - please make sure to follow the academic rules of writing ([you can read them up here one more time](https://www.tudelft.nl/library/actuele-themas/copyright/c/plagiarism/)).

The final project report is graded in combination with the project interview. The interview will be an academic discussion about the executed project.

## Interviews

The 15 minute interview per group will be scheduled on either **March 14** or **March 15**. A Doodle will be released to pick your interview timeslot.