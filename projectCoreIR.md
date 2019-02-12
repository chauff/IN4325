# Core IR project

You can choose between two types of projects.

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

## Report

Format, etc.