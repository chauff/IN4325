# Applied NLP Lectures <!-- omit in toc -->
**In progress**

The following sections contain the materials for the eight applied NLP lectures. The applied NLP papers to review each week are listed here as well.

## Table of contents <!-- omit in toc -->

- [NLP resources](#nlp-resources)
  - [Books](#books)
  - [Software](#software)
  - [Open Source Natural Language Processing Tools](#open-source-natural-language-processing-tools)
  - [Datasets](#datasets)
- [Lecture 1: NLP Introduction](#lecture-1-nlp-introduction)
  - [Recommended readings](#recommended-readings)
- [Lecture 2: Syntax](#lecture-2-syntax)
  - [Recommended readings](#recommended-readings)
  - [Recommended resources:](#recommended-resources)
  - [:warning: Paper P1 to review](#warning-paper-p1-to-review)
- [Lecture 3: Semantics](#lecture-3-semantics)
  - [Recommended readings](#recommended-readings)
  - [Recommended resources:](#recommended-resources)
- [Lecture 4: Evaluation NLP](#lecture-4-evaluation-nlp)
  - [Recommended readings](#recommended-readings)
  - [Recommended resources:](#recommended-resources)
  - [:warning: Paper P2 to review](#warning-paper-p2-to-review)
- [Lecture 5: ML for NLP](#lecture-5-ml-for-nlp)
  - [Recommended readings](#recommended-readings)
  - [Recommended resources:](#recommended-resources)
- [Lecture 6: Natural Language Generation](#lecture-6-natural-language-generation)
  - [Recommended readings](#recommended-readings)
  - [Recommended resources](#recommended-resources)
  - [:warning: Paper P3 to review](#warning-paper-p3-to-review)
- [Lecture 7: NLP annotations](#lecture-7-nlp-annotations)
  - [Recommended readings](#recommended-readings)
- [Lecture 8: Word embeddings](#lecture-8-word-embeddings)
  - [Recommended readings](#recommended-readings)
  - [:warning: Paper P4 to review](#warning-paper-p4-to-review)

## NLP resources

### Books
Speech and Language Processing (3rd ed.) by Dan Jurafsky and James H. Martin. [Available online](https://web.stanford.edu/~jurafsky/slp3).

Natural language processing by Jacob Eisenstein [Also available online](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)

### Software

A number of open-source retrieval toolkits exist. They have different strengths and weaknesses. Which ones are applicable to your project depend to some extent in your *taste* of programming languages and the kind of NLP task you are working on:

### Open Source Natural Language Processing Tools

   - [NLTK](http://www.nltk.org/)
   - [Apache OpenNLP](http://opennlp.apache.org/)
   
   Also in Dutch:
   - [SentiStrength](http://sentistrength.wlv.ac.uk/)
   - [Polyglot](https://polyglot.readthedocs.io/en/latest/)
   - [Clips](https://github.com/clips/pattern)

### Datasets
  - [Movie reviews](http://ai.stanford.edu/~amaas/data/sentiment/)
  - [Stanford sentiment treebank](nlp.stanford.edu/sentiment/code.html)
  - [Sentiment on Twitter](http://help.sentiment140.com/for-students/)
  - [Various text datasets, UCI](https://archive.ics.uci.edu/ml/datasets.html?format=&task=&att=&area=&numAtt=&numIns=&type=text&sort=nameUp&view=table)
- [Stance detection](https://github.com/FakeNewsChallenge/fnc-1)

## Lecture 1: NLP Introduction
Natural Language processing describes computational methods that allow computers to "understand" human communication. This lecture explains what NLP can do, and describes common NLP applications. It describes the kind of tasks that are solved by NLP, and the kind of components/sub-tasks that make it possible for us to solve these tasks.

<img src="img/intro.jpg" width="300px" align="middle">

Last year's lectures slides (PDF) are available [here](slides/NLP_Lecture1_Introduction.pdf). The slides will be updated (as needed) after the lecture.

### Recommended readings

## Lecture 2: Syntax
While human language is very flexible, it does follow certain rules, principles, and processes that govern the structure of sentences. We can use that structure to improve machine understanding of human language, and solve many NLP tasks. Therefore this lecture focuses on syntax, or the structure of sentences.

The lectures slides (PDF) are available [here](slides/NLP_Lecture2_Syntax.pdf). The slides will be updated (as needed) after the lecture.

** NLP project proposal: due March 22.**

### Recommended readings
[Large Language Models in Machine Translation ("Stupid Backoff")](http://www.aclweb.org/anthology/D07-1090.pdf)
[NLP book - Part-of-speech tagging:](https://web.stanford.edu/~jurafsky/slp3/10.pdf)

[Stanford parser FAQ:](https://nlp.stanford.edu/software/parser-faq.html)
[Sentiment analysis:](http://www.aclweb.org/anthology/P02-1053.pdf)
### Recommended resources:

[The Dutch translation of the Linguistic Inquiry and Word Count (LIWC) 2007 dictionary:](https://benjamins.com/#catalog/journals/dujal.6.1.04boo/details)

[NLTK Dutch PoS:](http://www.nltk.org/book/ch07.html)

### :warning: Paper P1 to review
[Offspring from reproduction problems: What replication failure teaches us](https://www.aclweb.org/anthology/P13-1166)

Fokkens, Antske, et al. "Offspring from reproduction problems: What replication failure teaches us." Proceedings of the 51st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). Vol. 1. 2013.

Review P1: handed out February 14, due **February 21**.

## Lecture 3: Semantics
What does it mean, what does it all mean? Unlike controlled languages, natural language is full of ambiguities. Words have multiple meanings, and words are related to each other in different ways. This lecture looks at semantics, or **meaning** in language.

<img src="img/semantics.jpg" width="300px" align="middle">

The lectures slides (PDF) are available [here](slides/NLP_Lecture3_Semantics.pdf). 
### Recommended readings
[Similarity for news recommender systems](http://navatintarev.com/papers/TintarevMasthoffAH2006.pdf)

[Determining the sentiment of opinions](https://dl.acm.org/citation.cfm?id=1220555)

[Mining and summarizing customer reviews.](https://dl.acm.org/citation.cfm?id=1014073)

### Recommended resources:

[NLTK similarity](http://nltk.github.com/api/nltk.corpus.reader.html?highlight=similarity%23nltk.corpus.reader.WordNetCorpusReader.res_similarity)

[Wordnet::similarity](http://wn-similarity.sourceforge.net/)

[DutchSemCor](http://wordpress.let.vupr.nl/dutchsemcor/)



## Lecture 4: Evaluation NLP

How do we know if our NLP methods are working well? What are the methods used in NLP, and what are the metrics? How do we interpret these are when are they suitable? This lecture looks at evaluation, and assessing the performance of NLP systems.

The lectures slides (PDF) are available [here](slides/NLP_Lecture4_evaluation.pdf). 
<img src="img/evaluation.jpg" width="300px" align="middle">

### Recommended readings
[Ehud Reiter on NLG evaluation](https://ehudreiter.com/2017/05/03/metrics-nlg-evaluation/)

[Why Most Published Research Findings Are False](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1182327/)

[More offline evaluation metrics from NIST](https://www.nist.gov/sites/default/files/documents/itl/iad/mig/NISTMetricsMaTr10_v1-1_public.pdf)

[The Pyramid method: Nenkova, Ani, Rebecca Passonneau, and Kathleen McKeown. "The pyramid method: Incorporating human content selection variation in summarization evaluation." ACM Transactions on Speech and Language Processing (TSLP) 4.2 (2007): 4.](www.cs.columbia.edu/nlp/papers/2007/nenkova_al_07.pdf)

### Recommended resources:

[ASIYA: Open toolkit for evaluating text using automatic metrics](http://asiya.lsi.upc.edu/demo/asiya_online.php)

### :warning: Paper P2 to review
[Best practices for the human evaluation of automatically generated text](https://www.inlg2019.com/assets/papers/98_Paper.pdf)

Best practices for the human evaluation of automatically generated text. Chris van der Lee, Albert Gatt, Emiel van Miltenburg, Sander Wubben and Emiel Krahmer 

Review P2: handed out February 21, due **February 28**.


## Lecture 5: ML for NLP
How do we apply what we know about classifiers and regression to NLP problems? What are commonpitfalls and mistakes? Which kind of biases in the data and analysis should we look out for as ethical data scientists? This lecture focuses on applying classical machine learning techniques to natural language processing.
<img src="img/overfitting.jpg" width="300px" align="middle">

The lectures slides (PDF) are available [here](slides/NLP_Lecture5_ML.pdf). 

### Recommended readings
  - [Article on the Bias-Variance tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html)
  
  - Jurafsky, Dan. [Speech & language processing](https://web.stanford.edu/~jurafsky/slp3/)
  
      - Chapter 6 Naive-Bayes
      - Chapter 7 logistic regression

  - Bing Liu. [Sentiment analysis and Opinion Mining](stp.lingfil.uu.se/~santinim/sais/2014/bingliu.pdf)
    
    - Chapter 10 (fake reviews)
  
    - [Related paper on fake review detection.](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM13/paper/view/6006/6380)

### Recommended resources:

   [Scikit-learn, machine learning in Python](https://scikit-learn.org/stable/)
   
   [NLTK machine learning (more limited for ML)](http://www.nltk.org/book/ch06.html)



## Lecture 6: Natural Language Generation
So far we've only looked at how to improve computational **understanding** natural language. However in conversational systems (like, but not limited to chatbots), we also might want a computer to communicate with us. There is an area of research that focuses on going from abstract, often rich and complex, representations to natural language that people can understand. In this lecture we will introduce this area of research, which is called Natural Language Generation.

The lectures slides (PDF) are available [here](slides/NLP_Lecture6_NLG.pdf). 

**NLP intermediate project report: due April 5.**

### Recommended resources

[simplenlg realizer](https://github.com/simplenlg/simplenlg)

Academic Reference: A Gatt and E Reiter (2009). [SimpleNLG: A realisation engine for practical applications.](aclweb.org/anthology/W/W09/W09-0613.pdf) Proceedings of ENLG-2009

### :warning: Paper P3 to review
[Thumbs up?: sentiment classification using machine learning techniques](https://dl.acm.org/citation.cfm?doid=1118693.1118704)

Pang, Bo, Lillian Lee, and Shivakumar Vaithyanathan. "Thumbs up?: sentiment classification using machine learning techniques." Proceedings of the ACL-02 conference on Empirical methods in natural language processing-Volume 10. Association for Computational Linguistics, 2002.

Review P3: handed out February 28, due **March 6**.

## Lecture 7: Bias in NLP
The results that we get in many NLP tasks are dependent on the quality and properties of the underlying data. In many (most) cases this is as important as applying the right machine learning techniques. In addition, a lot of the annotation is noisy or simply subjective. In this lecture we discuss the challenges and some of the state-of-the-art solutions.

The lectures slides (PDF) are available [here](slides/NLP_Lecture7_bias.pdf) 

**NLP final project report: due April 10.**

### Recommended readings


## Lecture 8: Word embeddings
The theory of distributional semantics effectively builds on the principle "A word is known by the company it keeps". In this lecture we will have an introduction to how to learn abstract word vectors that can help us compute the semantic (meaning) distance between different words. We will look at different ways these kinds of vectors can be used, and also talk about some of their limitations.

The lectures slides (PDF) are available [here](slides/NLP8_Embeddings.pdf) 

**NLP project interviews: April 11 and April 12.**

### Recommended readings

### :warning: Paper P4 to review

[Exploiting 'subjective' annotations](https://dl.acm.org/citation.cfm?id=1611631)

Reidsma, Dennis. "Exploiting 'subjective' annotations." Proceedings of the Workshop on Human Judgements in Computational Linguistics. Association for Computational Linguistics, 2008.

Review 4: handed out March 6, due **March 13**.
