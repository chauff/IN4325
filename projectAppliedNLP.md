# Applied NLP project

There are three expected outputs:

1. **Project proposal** (mandatory, but ungraded - you will receive feedback).
2. **Intermediate project report** (mandatory, but ungraded - you will receive feedback).
3. **Final project report** (mandatory, graded).

**Group projects are conducted in groups of 3-4 students. Please enroll together with your team members in group on Brightspace - we have predefined 30 different groups, take your pick!**

You can choose between two types of projects: reproducing an NLP paper or investigating a research idea of your own.

## 1. Reproducing an NLP paper
You first choose a published paper that describes an NLP experiment. We have a list of papers that are well suited for this project below, but of course you can also suggest to reproduce another one.
You then implement and execute the experiments described in the paper, analyze your results and discuss them in light of the original paper’s results.
Note that **reproducibility does not mean to create an exact replica of the original paper** (that would be replicability), instead [reproducibility](https://www.acm.org/publications/policies/artifact-review-badging) asks the question whether the idea is reproducible by a different team, a slightly different experimental setup and independently developed artifacts. 
[This interesting paper](https://pdfs.semanticscholar.org/b95a/11620929f1c4760587ac99a8d6b4d8cbc547.pdf) on algorithm reproducibility (in particular Table 2!) may give you inspirations for what to look out for in terms of reproducibility.

*Why should you choose this project type?* Because replicating experiments requires you to understand and apply the whole breadth of NLP - starting from finding the toolkit to use (or implement from scratch if you desire!), to the right document collection, implementation, metrics, and evaluation. It will give you a sense of how different choices for the above (toolkit, data, implementation, evaluation) influence your result.

### List of recommended NLP papers

The page for most topics has several additional references. You can use these papers as a starting point to see who they cite and who references them (in Google Scholar, click on ‘citations’).

   * [“Fake news” and stance detection](http://www.fakenewschallenge.org/)     
      - [Ferreira & Vlachos (2016)](http://aclweb.org/anthology/N/N16/N16-1138.pdf)  
      - [Augenstein et al. (2016)](https://arxiv.org/abs/1606.05464)

   * [Sentiment analysis on movies](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews)

      - Pang and L. Lee. 2005. Seeing stars: Exploiting class relationships for sentiment categorization with respect to rating scales. In ACL, pages 115–124.

   * [Irony detection:](https://competitions.codalab.org/competitions/17468)

     -   [Monday mornings are my fave :) #not Exploring the Automatic Recognition of Irony in English tweets.]( http://www.aclweb.org/anthology/C16-1257)

   * [Click-bait challenge](http://www.clickbait-challenge.org/)
        - [Detecting Clickbait in Online Social Media: You Won't Believe How We Did It](https://arxiv.org/abs/1710.06699)


## 2. Investigating a research idea of your own choice
You can also propose a research project within NLP of your own choice in consultation with the instructor (it can be a novel idea or involve reproducing an existing paper). To get inspired, take a look at recent conference proceedings at the major NLP conferences and competitions:

   * [CL, NAACL, ACL](http://aclweb.org/anthology/)
   * [INLG/ENLG](http://aclweb.org/anthology/siggen.html)
   * [SemEval: Hyperpartisan News Detection](https://pan.webis.de/semeval19/semeval19-web/index.html)
   * [Digital Text Forensics](https://pan.webis.de/clef19/pan19-web/index.html) e.g., Bots and Gender Profiling, Celebrity Profiling, Cross-Domain Authorship Attribution, Style Change Detection

Why should you choose this project type? Because not all NLP topics are covered in depth in the lectures and you can investigate them further by choosing them as your research project.

## Restrictions

Based on prior experience we put the following restrictions on your choice of project, no matter if you reproduce a paper or follow your own research idea:

- **You can only conduct a project on neural NLP if you have successfully completed the Deep Learning course beforehand.**
- The main focus of your project is *NLP*. If you build a classifier, the features you study should be motivated by linguistic theory/previous findings in NLP.
- If you use off the shelf solutions: be aware of the defaults and motivate why they are suitable for your problem.
- Not all data is created equal -- what kind of biases might come from the dataset you are using?
- The project focuses on **textual data** (not video/audio/genomics/.... data).

We have a first deadline in week 3.6, so you will get early feedback on the suitability of your proposal.

## Report formats
(These are the same as for core IR.)

### Project proposal

The proposal should contain between 300 and 400 words. Your proposal should address the following points:

1. Problem description: which problem will you tackle and what is interesting about the problem? If you reproduce a paper make sure to reference the original paper.
2. Resources: which data and tools will you be using (this includes also existing implementations of algorithms
3. Methodology: if you choose to reproduce a paper, tell us which part of the paper (if not all) you will reproduce; if you choose your own research idea, tell us what type of algorithm/approach you are proposing and what your baseline(s) will be
4. Background readings: list at least 5 related papers that you will read to add context to your research
5. Evaluation: how will you evaluate your algorithm/approach? Which evaluation metrics will you use?

**Submission**: every group uploads their proposal on Brightspace (one per group). The proposal should be in PDF format and should contain the group name and the list of group members (name, student IDs).

**Feedback**: the course team will provide feedback on the project proposal within a few days.

### Intermediate and final project report

The **final** group project report should be **7-8 pages** long in the [SIGCHI proceedings format](https://sigchi.org/templates/) (available as LaTeX and Word templates). The **intermediate** project report is likely to be shorter (it is due a week before the final deadline), that is fine, submit whatever you have by then.

We suggest the following report structure:

- Title, authors
- Abstract
- Introduction: problem statement, motivation for the problem, overall plan to tackle the problem
- Background: what important works does this project build on
- Approach: what methods/algorithms did you use (justify why these are suitable)
- Experiments: describe your evaluation/experiments (justify experimental methodology), the results and discuss them (comparisons and critical discussion will be considered in the grading)
- Conclusions: describe what you learnt/found and what avenues for future work you see
- References

The final report should also contain a link to a repository (or several) that contain the (reasonably well documented) software you created, the scripts you used to analyze your data, etc.

**Submission:** every group uploads their intermediate and final group project reports on Brightspace (one per group). The reports should be in PDF format. Note that after submission a plagiarism check is executed by Turnitin - please make sure to follow the academic rules of writing ([you can read them up here one more time](https://www.tudelft.nl/library/actuele-themas/copyright/c/plagiarism/)).

The final project report is graded in combination with the project interview. The interview will be an academic discussion about the executed project.

## Interviews

The 15 minute interviews per group will be scheduled on **April 11** and **April 12**. 
