# Core IR lectures <!-- omit in toc -->

```diff
! The core IR page is now up-to-date for the 2019/20 edition.
```

## Table of contents <!-- omit in toc -->

- [IR resources](#ir-resources)
  - [Books](#books)
  - [Software](#software)
  - [Datasets](#datasets)
- [Lecture 9: evaluation (week 3.5)](#lecture-9-evaluation-week-35)
  - [Recommended readings](#recommended-readings)
- [Lecture 10: classic retrieval models (week 3.5)](#lecture-10-classic-retrieval-models-week-35)
  - [Recommended readings](#recommended-readings-1)
- [:warning: Paper P5 to review](#warning-paper-p5-to-review)
- [Lecture 11: indexing (week 3.6)](#lecture-11-indexing-week-36)
  - [Recommended readings](#recommended-readings-2)
- [Lecture 12: query refinement (week 3.6)](#lecture-12-query-refinement-week-36)
  - [Recommended readings](#recommended-readings-3)
- [:warning: Paper P6 to review](#warning-paper-p6-to-review)
- [Lecture 13: personalization (week 3.7)](#lecture-13-personalization-week-37)
  - [Recommended readings](#recommended-readings-4)
- [Lecture 14: interactive IR (week 3.7)](#lecture-14-interactive-ir-week-37)
  - [Recommended readings](#recommended-readings-5)
- [:warning: Paper P7 to review](#warning-paper-p7-to-review)
- [Lecture 15: learning to rank (week 3.8)](#lecture-15-learning-to-rank-week-38)
  - [Recommended readings](#recommended-readings-6)
- [Lecture 16: neural IR (week 3.8)](#lecture-16-neural-ir-week-38)
  - [Recommended readings](#recommended-readings-7)
- [:warning: Paper P8 to review](#warning-paper-p8-to-review)



## IR resources

### Books
- *Introduction to Information Retrieval* by Manning, Raghavan and Schütze, University Press, 2008. Available online: [https://nlp.stanford.edu/IR-book/information-retrieval-book.html](https://nlp.stanford.edu/IR-book/information-retrieval-book.html).
- *Information Retrieval: Implementing and Evaluating Search Engines* by Büttcher, Clarke, and Cormack. The MIT Press, 2010.
- *Search Engines: Information Retrieval in Practice* by B. Croft, D. Metzler, T. Strohman, Addison-Wesley, 2009. Available online: [http://ciir.cs.umass.edu/irbook/](http://ciir.cs.umass.edu/irbook/).

### Software

A number of open-source retrieval toolkits exist. They have different strengths and weaknesses. Which ones are applicable to your project depend to some extent in your *taste* of programming languages and the kind of retrieval models you are after:

- The [Terrier IR platform](http://terrier.org/) is written in Java. It is heavily used in academia.
- [Anserini](https://github.com/castorini/Anserini) is built on top of Lucene and written in Java. It has recently emerged as a good and easy-to-use alternative to Terrier.
- The [Lemur project](https://www.lemurproject.org/) is written in C++/Java and contains a number of important libraries commonly used by academic IR researchers, including  `Indri`, `Galago` and `RankLib`. One of the most often employed toolkits for academic research due to the manner in which retrieval components can be altered/extended.
- [Macaw](https://github.com/microsoft/macaw) is a recently open-sourced conversational information seeking platform (good for user experiments; hard to set up on a Mac though). It was developed by IR researchers from Microsoft.
- [Pisa](https://github.com/pisa-engine/pisa).
- [JASS](https://codedocs.xyz/andrewtrotman/JASSv2/index.html).
- [Elasticsearch](https://www.elastic.co/products/elasticsearch) is an open-source toolkit heavily used in industry. Written in Java and building on top of Lucene.
- [Whoosh](https://pypi.org/project/Whoosh/#description) is a search engine written in Python.
- [SearchX](https://github.com/felipemoraes/searchx) is a (collaborative) search system developed at TU Delft, written in JavaScript/Node.js.
- So far there is only one widely used toolkit that provides neural IR approaches: [MatchZoo](https://github.com/NTMC-Community/MatchZoo).

For evaluation purposes, [trec_eval](https://github.com/usnistgov/trec_eval) is commonly used.

### Datasets

- In IR, an often employed corpus for user studies is [Robust04](https://trec.nist.gov/data/robust/04.guidelines.html): about 500K news documents and 250 search topics with relevance judgments. If you want to  use it, get in touch with us and we give you access to this corpus.
- [WT10g](http://ir.dcs.gla.ac.uk/test_collections/wt10g.html): a 1.7 million web document from 2000 with 100 topics and relevance judgments
- [TREC tracks and datasets](https://trec.nist.gov/data.html): TREC has a long history of offering diverse information retrieval tracks. Take a look at the tracks and their respective datasets (some of which are available online).
- [AOL query log](http://www.cim.mcgill.ca/~dudek/206/Logs/AOL-user-ct-collection/) is a large-scale query log from 2006. It can be useful to analyse query patterns for instance.
- [Recent question answering datasets](https://github.com/chauff/conversationalIR)
- [MS MARCO](https://microsoft.github.io/msmarco/): large-scale passage and document retrieval
- [QANTA](https://pinafore.github.io/qanta-leaderboard/): a question-answering dataset
- [HotpotQA](https://hotpotqa.github.io/): a question-answering dataset
- [Natural Questions](https://ai.google.com/research/NaturalQuestions): Google's most recent question answering dataset.

## Lecture 9: evaluation (week 3.5)

This lecture covers the basics of evaluation, a vital topic in IR - a research field driven forward by empirical work. For the core IR project, you need to have detailed knowledge of at least a small number of metrics, *why* they are used for a specific task, *how* to test whether treatment and control (or baseline vs. experimental approach) differ significantly, etc.

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-evaluation-2020.pdf).

### Recommended readings

- Chapter 8 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
Chapter 8 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).
- A good [tutorial](http://ir.cis.udel.edu/ICTIR13tutorial/) on statistical significance testing with an R worksheet by Ben Carterette.
- A detailed read on test collections: *Test Collection Based Evaluation of Information Retrieval Systems* by Mark Sanderson ([PDF](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.646.8451&rep=rep1&type=pdf)).
- A great survey on interactive IR evaluation: *Methods for Evaluating Interactive Information Retrieval Systems with Users* by Diane Kelly ([PDF](https://ils.unc.edu/courses/2019_spring/inls509_001/papers/FnTIR-Press-Kelly.pdf)).
- A recent [A/B testing tutorial](https://exp-platform.com/2017abtestingtutorial/) by Pavel Dmitriev.


## Lecture 10: classic retrieval models (week 3.5)

This lecture covers the most well-known retrieval models in IR - starting from the boolean model and ending at the language modeling approach to IR. More advanced retrieval models (learning to rank and neural approaches to IR) will be covered in the last two lectures of this course.

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-retrievalModels-2020.pdf).

### Recommended readings

- Chapters 11.1-11.3 and 12.1-12.3 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
- Chapter 7.1-7.3 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).
- A [critical review](http://times.cs.uiuc.edu/czhai/pub/slmir-now.pdf) of Language Models for IR by ChengXiang Zhai.
- Victor Lavrenko (one of the language modeling pioneers in IR) has a lot of useful [lecture videos](https://www.youtube.com/user/victorlavrenko/videos) on YouTube about language models and more general IR and machine learning concepts.

## :warning: Paper P5 to review

[The Importance of Prior Probabilities for Entry Page Search](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.15.1033&rep=rep1&type=pdf).

## Lecture 11: indexing (week 3.6)

This lecture covers the basics of IR indexing - an area where it is worthwhile to brush up on your existing data structure knowledge.

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-indexing-2020.pdf).

### Recommended readings

- Chapters 2, 3, 4 and 5 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
- Chapter 5 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).

## Lecture 12: query refinement (week 3.6)

This lecture covers a number of query refinement techniques, a hot research area, especially in web search where users typically do not enter more than two or three terms to express their information need. 

Query refinement has many facets, we focused here mostly on pseudo-relevance feedback and how to incorporate it in a meaningful manner in a retrieval model.

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-queryRefinement-2020.pdf). 


### Recommended readings

- Chapter 9 of Manning's et al. Introduction to Information Retrieval book ([PDF](https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf)).
- Chapters 6.1-6.2 and 7.3 of Croft's et al. Search Engines - Information Retrieval in Practice book ([PDF](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf)).
- A [survey](https://www.iro.umontreal.ca/~nie/IFT6255/carpineto-Survey-QE.pdf) on automatic query expansion is available from Carpineto and Romano.
- A [survey on query autocompletion](https://www.nowpublishers.com/article/Details/INR-055) by Cai & de Rijke.

## :warning: Paper P6 to review

[Document Reordering is Good, Especially for e-Commerce](http://www.cs.otago.ac.nz/homepages/andrew/papers/2017-7.pdf).


## Lecture 13: personalization (week 3.7)

This lecture is about personalization in search, with a glimpse of two classic hyperlink-based document ranking algorithms.

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-personalization-2020.pdf). The screencasts are split into four parts: [1](https://drive.google.com/open?id=1lL68YtJoQQVKWp7Z2ZedRMgojQp1AKfA) [2](https://drive.google.com/open?id=1qp3P5Kc5-cNxiA593M1_-6TXEwsb3Yfs) [3](https://drive.google.com/open?id=1m9eoyaR39nO54Z6g5C5uuEPhf2pZmSDv) [4](https://drive.google.com/open?id=1NkW5krwIXdm1balr1h2nKKqZmevy23kD). *They will remain online for about a week*.

### Recommended readings

There is no specific list of recommended readings (beyond the ones linked at the bottom of most slides); no recent personalized search survey exists. However, a look at [Google Scholar](https://scholar.google.nl/) (query for *personalized search*) will show you many interesting and recent papers (as well as patents) on the topic. 

It is worth pointing out a [survey on Adversarial Web Search](https://www.nowpublishers.com/article/Details/INR-021). It does not fit the brief of this lecture, but it covers a lot of ground showing how to combat adversary in web search.

## Lecture 14: interactive IR (week 3.7)

This lecture covers interactive information retrieval, in particular the modeling of the search process. The lecture shows off our move towards predictive (mathematical) models and their usage to generate hypotheses which are then (in)validated in user experiments.

*This lecture is given by Dr. David Maxwell.*

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-interactiveIR-2020.pdf). The screencasts are split into three parts: [1](https://drive.google.com/open?id=10gax4ai179VNOETUWsMAx8TaCkR6sl2_) [2](https://drive.google.com/open?id=11spL1t096_AiGxi_W3y9z-FcS7khVFLL) [3](https://drive.google.com/open?id=1yQAC97FFer656ZZUUF4QaTAj94KVwGZO). *They will remain online for about a week*.

### Recommended readings

- A [tutorial](http://zuccon.net/publications/azzopardi-zuccon-2017-tutorial-economics.pdf) on economic models for search (set into a larger HCI context).
- A [book](https://www.morganclaypool.com/doi/abs/10.2200/S00174ED1V01Y200901ICR003) on exploratory search beyond the query-response paradigm. 

## :warning: Paper P7 to review

[Two Scrolls or One Click: A Cost Model for Browsing Search Results](http://eprints.qut.edu.au/95667/1/ecir2016cost_model.pdf).


## Lecture 15: learning to rank (week 3.8)

The lecture is concerned with learning to rank for IR (also known as LTR or L2R), a machine-learning approach towards the document ranking problem that can be applied to many other types of ranking problems as well.

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-L2R-2020.pdf). The screencasts are split into three parts: [1](https://drive.google.com/open?id=1p7ea5sXjoT_aMjbegsw3y0vZT9FB075S) [2](https://drive.google.com/open?id=1MX4XD48YytEZV7bRgsGAcSGxdDLHKt6V) [3](https://drive.google.com/open?id=1WkvAQfq0dGITuuMgE4KKCigEH4mU3YC2). *They will remain online for about a week*.

### Recommended readings

- The [Learning to Rank for IR tutorial](https://www.nowpublishers.com/article/Details/INR-016) by Tie-Yan Liu provides a global overview of many L2R approaches, and their underlying motivations and heuristics.
- Major L2R algorithms have been implemented in TensorFlow, check out this [TF-Ranking GitHub repo](https://github.com/tensorflow/ranking) which contains a link to a tutorial recently given at SIGIR about the software (and L2R more generally).
- Our colleagues at UvA (who run one of the premier IR labs in the world) do a lot of research on [online learning to rank](https://ilps.github.io/webconf2020-tutorial-unbiased-ltr/WWW2020handout.pdf) (tutorial held at WWW2020).
  
## Lecture 16: neural IR (week 3.8)

This lecture provides an overview of recent developments in deep learning as they apply to IR. It builds upon the embeddings material introduced in the applied NLP part and discusses the basics of neural networks before focusing on IR-specific developments.

*The lecture is given by Arthur Câmara.*

:bangbang: The 2019/2020 lecture slides in PDF format are available [here](slides/coreIR-neural-2020.pdf). The screencasts are split into three parts: [1](https://drive.google.com/open?id=1Du55PTnbVx9hqjtk706k_hit4GzF7KtD) [2](https://drive.google.com/open?id=1x_SgEZX0KsqrElL-rDKO0X6vI31YukSe) [3](https://drive.google.com/open?id=1OvEzzVhPzqXM48bKaPccnUBjQ7zRCyLJ). *They will remain online for about a week*.


### Recommended readings

There are a number of deep learning courses that provide good insights (most popular are the Stanford [computer vision](http://cs231n.stanford.edu/) and [NLP](http://web.stanford.edu/class/cs224n/) ones). Specific to IR, there are fewer resources, the three standouts are:

- A 100+ page [introduction](https://www.microsoft.com/en-us/research/uploads/prod/2017/06/fntir2018-neuralir-mitra.pdf) to neural nets and neural IR models by Bhaskar Mitra and Nick Craswell.
- An up-to-date [neural IR tutorial](http://nn4ir.com/ecir2018/) (in the form of elaborate slide decks) created by our colleagues at the University of Amsterdam, which has been given a few times by now at various IR conferences.
- This [neural IR survey](https://link.springer.com/article/10.1007/s10791-017-9321-y) by Onal et al. is denser and requires more IR knowledge to make sense of it. It has a good overview of promising future directions.
- [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html) page offers an annotated (with code) walkthrough of the Transformer paper - the paper that makes BERT possible. And BERT has become **the** new mainstay of NLP/IR research.
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) is another good resource to better understand the Transformer paper.
- [Embeddings in NaturalLanguage Processing](http://josecamachocollados.com/book_embNLP_draft.pdf) (free draft release in PDF format)

## :warning: Paper P8 to review

[Query Expansion with Locally-Trained Word Embeddings](http://www.aclweb.org/anthology/P16-1035).
