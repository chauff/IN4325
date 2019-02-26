# Core IR lectures <!-- omit in toc -->

The following sections contain the materials for the eight core IR lectures. The core IR papers to review each week are listed here as well.

## Table of contents <!-- omit in toc -->

- [IR resources](#ir-resources)
  - [Books](#books)
  - [Software](#software)
  - [Datasets](#datasets)
- [Lecture 1: evaluation (week 3.1)](#lecture-1-evaluation-week-31)
  - [Recommended readings](#recommended-readings)
- [Lecture 2: classic retrieval models (week 3.1)](#lecture-2-classic-retrieval-models-week-31)
  - [Recommended readings](#recommended-readings-1)
  - [:warning: Paper P1 to review](#warning-paper-p1-to-review)
- [Lecture 3: indexing (week 3.2)](#lecture-3-indexing-week-32)
  - [Recommended readings](#recommended-readings-2)
  - [:warning: Paper P2 to review](#warning-paper-p2-to-review)
- [Lecture 4: query refinement (week 3.2)](#lecture-4-query-refinement-week-32)
  - [Recommended readings](#recommended-readings-3)
  - [:warning: Paper P3 to review](#warning-paper-p3-to-review)
- [Lecture 5: interactive IR (week 3.3)](#lecture-5-interactive-ir-week-33)
  - [Recommended readings](#recommended-readings-4)
  - [:warning: Paper P4 to review](#warning-paper-p4-to-review)
- [Lecture 6: personalization (week 3.3)](#lecture-6-personalization-week-33)
  - [Recommended readings](#recommended-readings-5)
  - [:warning: Paper P5 to review](#warning-paper-p5-to-review)
- [Lecture 7: learning to rank (week 3.4)](#lecture-7-learning-to-rank-week-34)
  - [Recommended readings](#recommended-readings-6)
  - [:warning: Paper P6 to review](#warning-paper-p6-to-review)
- [Lecture 8: neural IR (week 3.4)](#lecture-8-neural-ir-week-34)
  - [Recommended readings](#recommended-readings-7)
  - [:warning: Paper P7 to review](#warning-paper-p7-to-review)

## IR resources

### Books
- *Introduction to Information Retrieval* by Manning, Raghavan and Schütze, University Press, 2008. Available online: [https://nlp.stanford.edu/IR-book/information-retrieval-book.html](https://nlp.stanford.edu/IR-book/information-retrieval-book.html).
- *Information Retrieval: Implementing and Evaluating Search Engines* by Büttcher, Clarke, and Cormack. The MIT Press, 2010.
- *Search Engines: Information Retrieval in Practice* by B. Croft, D. Metzler, T. Strohman, Addison-Wesley, 2009. Available online: [http://ciir.cs.umass.edu/irbook/](http://ciir.cs.umass.edu/irbook/).

### Software

A number of open-source retrieval toolkits exist. They have different strengths and weaknesses. Which ones are applicable to your project depend to some extent in your *taste* of programming languages and the kind of retrieval models you are after:

- The [Lemur project](https://www.lemurproject.org/) is written in C++/Java and contains a number of important libraries commonly used by academic IR researchers, including  `Indri`, `Galago` and `RankLib`. One of the most often employed toolkits for academic research.
- The [Terrier IR platform](http://terrier.org/) is written in Java. Also heavily used in academia.
- [Anserini](https://github.com/castorini/Anserini) is built on top of Lucene and written in Java.
- [Elasticsearch](https://www.elastic.co/products/elasticsearch) is an open-source toolkit heavily used in industry. Written in Java and building on top of Lucene.
- [Whoosh](https://pypi.org/project/Whoosh/#description) is a search engine written in Python.
- [SearchX](https://github.com/felipemoraes/searchx) is a collaborative search system developed at TU Delft, written in JavaScript/Node.js.
- So far there is only one widely used toolkit that provides neural IR approaches: [MatchZoo](https://github.com/NTMC-Community/MatchZoo) (though be aware, it has its issues).

For evaluation purposes, [trec_eval](https://github.com/usnistgov/trec_eval) is commonly used.

### Datasets

- [TREC collections](http://trec.nist.gov/data.html) (*check with us whether we have the one you want*)
- [AOL query log](http://www.cim.mcgill.ca/~dudek/206/Logs/AOL-user-ct-collection/)
- [Recent question answering datasets](https://github.com/chauff/conversationalIR)


## Lecture 1: evaluation (week 3.1)

This lecture covers the basics of evaluation, a vital topic in IR - a research field driven forward by empirical work. For the core IR project, you need to have detailed knowledge of at least a small number of metrics, why they are used for a specific task, how to test whether treatment and control (or baseline vs. experimental approach) differ significantly, etc.

The lectures slides (PDF) are available [here](slides/coreIR-evaluation.pdf).

### Recommended readings

- Chapter 8 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
Chapter 8 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).
- A good [tutorial](http://ir.cis.udel.edu/ICTIR13tutorial/) on statistical significance testing with an R worksheet by Ben Carterette.
- A detailed read on test collections: *Test Collection Based Evaluation of Information Retrieval Systems* by Mark Sanderson ([PDF](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.646.8451&rep=rep1&type=pdf)).
- A great survey on interactive IR evaluation: *Methods for Evaluating Interactive Information Retrieval Systems with Users* by Diane Kelly ([PDF](https://ils.unc.edu/courses/2019_spring/inls509_001/papers/FnTIR-Press-Kelly.pdf)).
- A recent [A/B testing tutorial](https://exp-platform.com/2017abtestingtutorial/) by Pavel Dmitriev.


## Lecture 2: classic retrieval models (week 3.1)

This lecture covers the most well-known retrieval models in IR - starting from the boolean model and ending at the language modeling approach to IR. More advanced retrieval models (learning to rank and neural approaches to IR) will be covered in lectures 7 and 8 of this course.

The lectures slides (PDF) are available [here](slides/coreIR-retrievalModels.pdf).

### Recommended readings

- Chapters 11.1-11.3 and 12.1-12.3 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
- Chapter 7.1-7.3 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).
- A [critical review](http://times.cs.uiuc.edu/czhai/pub/slmir-now.pdf) of Language Models for IR by ChengXiang Zhai.
- Victor Lavrenko (one of the language modeling pioneers in IR) has a lot of useful [lecture videos](https://www.youtube.com/user/victorlavrenko/videos) on YouTube about language models and more general IR and machine learning concepts.

### :warning: Paper P1 to review

[The influence of basic tokenization on biomedical document retrieval](https://www.researchgate.net/profile/Wessel_Kraaij/publication/221299722_The_influence_of_basic_tokenization_on_biomedical_document_retrieval/links/0912f508eb1efc3828000000/The-influence-of-basic-tokenization-on-biomedical-document-retrieval.pdf).


## Lecture 3: indexing (week 3.2)

This lecture covers the basics of IR indexing - an area where it is worthwhile to brush up on your existing data structure knowledge.

The lectures slides (PDF) are available [here](slides/coreIR-indexing.pdf).

### Recommended readings

- Chapters 2, 4 and 5 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
- Chapter 5 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).

### :warning: Paper P2 to review

[The Importance of Prior Probabilities for Entry Page Search](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.15.1033&rep=rep1&type=pdf).



## Lecture 4: query refinement (week 3.2)

This lecture covers a number of query refinement techniques, a hot research area, especially in web search where users typically do not enter more than two or three terms to express their information need. 

Query refinement has many facets, we focused here mostly on pseudo-relevance feedback and how to incorporate it in a meaningful manner in a retrieval model.

The lectures slides (PDF) are available [here](slides/coreIR-queryRefinement.pdf).

### Recommended readings

- Chapter 9 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
- Chapters 6.1-6.2 and 7.3 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).
- A [survey](https://www.iro.umontreal.ca/~nie/IFT6255/carpineto-Survey-QE.pdf) on automatic query expansion is available from Carpineto and Romano.
- A [survey on query autocompletion](https://www.nowpublishers.com/article/Details/INR-055) by Cai & de Rijke.

### :warning: Paper P3 to review

[Document Reordering is Good, Especially for e-Commerce](http://www.cs.otago.ac.nz/homepages/andrew/papers/2017-7.pdf).

## Lecture 5: interactive IR (week 3.3)

This lecture covers interactive information retrieval, in particular the modeling of the search process. The lecture shows off our move towards predictive (mathematical) models and their usage to generate hypotheses which are then (in)validated in user experiments.

The slides  are [online](https://docs.google.com/presentation/d/e/2PACX-1vQj-MAdwO6pEyoAB4bMFqdsgldNNDQrqRZaf7tyOPsK62Px8688N_GHMlIc21WLM7W-u1VigSoRbOd8/pub?start=false&loop=false&delayms=3000) - currently from the 2017/18 course edition. The slides will be updated (as needed) after the lecture.

### Recommended readings

- A [tutorial](http://zuccon.net/publications/azzopardi-zuccon-2017-tutorial-economics.pdf) on economic models for search (set into a larger HCI context).

### :warning: Paper P4 to review

[Incorporating Query Expansion and Quality Indicators in Searching Microblog Posts](https://pdfs.semanticscholar.org/bfbd/8b113cf0ba2eb7301efbfbc51df2ea74bbb8.pdf).


## Lecture 6: personalization (week 3.3)

This lecture is about personalization in search, with a brief glimpse at the web at the very end. 

The slides  are [online](https://docs.google.com/presentation/d/e/2PACX-1vQ-sXMd4Ggt5YdAGHrZYh52p5ufZsxzqxKhlp_V1l60MUDRS8HfzEr5iAbNTh8ucTIC2x0q1UYeklk2/pub?start=false&loop=false&delayms=3000) - currently from the 2017/18 course edition. The slides will be updated (as needed) after the lecture.

### Recommended readings

There is no specific list of recommended readings (beyond the ones linked at the bottom of most slides); no recent personalized search survey exists. However, a look at [Google Scholar](https://scholar.google.nl/) will show you many interesting papers (and patents) on the topic.

However, it is worth pointing out a [survey on Adversarial Web Search](https://www.nowpublishers.com/article/Details/INR-021). It does not fit the brief of this lecture, but it covers a lot of ground showing how to combat adversary in web search.

### :warning: Paper P5 to review

[Two Scrolls or One Click: A Cost Model for Browsing Search Results](http://eprints.qut.edu.au/95667/1/ecir2016cost_model.pdf).


## Lecture 7: learning to rank (week 3.4)

The lecture is concerned with learning to rank for IR (also known as LTR or L2R), a machine-learning approach towards the document ranking problem that can be applied to many other types of ranking problems as well.

The slides  are [online](https://docs.google.com/presentation/d/e/2PACX-1vTwo37wjtBJi7MBnEDA6wzgybymAvKagc28OoI94UFuwohAN3WBMmnSxAipoBdap44JhPbyUKiE9Y0L/pub?start=false&loop=false&delayms=3000) - currently from the 2017/18 course edition. The slides will be updated (as needed) after the lecture.

### Recommended readings

- The [Learning to Rank for IR tutorial](https://www.nowpublishers.com/article/Details/INR-016) by Tie-Yan Liu provides a global overview of many L2R approaches, and their underlying motivations and heuristics.

### :warning: Paper P6 to review

[Enhancing Patent Retrieval by Citation Analysis](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.96.6135&rep=rep1&type=pdf).


## Lecture 8: neural IR (week 3.4)

This lecture provides an overview of recent developments in deep learning as they apply to IR. It is self-contained and briefly introduces the basics of neural networks before focusing on IR-specific developments.

The slides  are [online](https://docs.google.com/presentation/d/e/2PACX-1vRwuQ_a3Am7pyJWdqOGiWsCXqbfppRwQo2AM3nByclxanLvLAxe2s9zOWlXJ79zARP1Ke9KIpZefH-c/pub?start=false&loop=false&delayms=3000) - currently from the 2017/18 course edition. The slides will be updated (as needed) after the lecture.

### Recommended readings

There are a number of deep learning courses that provide good insights (most popular are the Stanford [computer vision](http://cs231n.stanford.edu/) and [NLP](http://web.stanford.edu/class/cs224n/) ones). Specific to IR, there are fewer resources, the three standouts are:

- A 100+ page [introduction](https://www.microsoft.com/en-us/research/uploads/prod/2017/06/fntir2018-neuralir-mitra.pdf) to neural nets and neural IR models by Bhaskar Mitra and Nick Craswell.
- An up-to-date [neural IR tutorial](http://nn4ir.com/ecir2018/) (in the form of elaborate slide decks) created by our colleagues at the University of Amsterdam, which has been given a few times by now at various IR conferences.
- This [neural IR survey](https://link.springer.com/article/10.1007/s10791-017-9321-y) by Onal et al. is denser and requires more IR knowledge to make sense of it. It has a good overview of promising future directions.

### :warning: Paper P7 to review

[Query Expansion with Locally-Trained Word Embeddings](http://www.aclweb.org/anthology/P16-1035).

