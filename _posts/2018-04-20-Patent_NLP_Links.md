---
title: "Patent NLP Papers"  
tags: [Data science, NLP, Resources]  
---

I'm going to be doing some work with NLP for patents. This is a collection of research notes and relevant links. 

Ways to group
* Technology classification (USPTO / WIPO)
* Citations (But 70% of patents not cited, 5 citations is very high)
* Machine learning prediction
* Machine learning clustering

## Links
### Patent Similarity
* [Vector space model - Kuhn, Younge](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2709238)
  * From https://www.patrf.org/technology/
  * [Slides](https://patentpdw.files.wordpress.com/2017/10/3-younge-and-kuhn.pdf)
* [Jaccard similarity - Arts, Cassiman, Gomez](https://onlinelibrary.wiley.com/doi/full/10.1002/smj.2699)
* [Functional tree comparison - Cascini, Zini](https://link.springer.com/chapter/10.1007/978-0-387-09697-1_3)
* [Metric learning approach - Fonseca](https://www.researchgate.net/publication/294054799_Metric_Learning_for_Patent_Similarity)
* [Citation link approach - Chen, Lee, Liu, Wu](https://pdfs.semanticscholar.org/dc95/133e4c13bfe4a99660b325c3a6349e22bf77.pdf)
* [Another citation link approach - Rodriguez et al (paywall)](https://link.springer.com/article/10.1007%2Fs11192-015-1531-8)
* [Hybrid category + text - Zhang et al (paywall)](https://www.sciencedirect.com/science/article/pii/S1751157715302169)
* [Knowledge / Concept extraction](https://ac.els-cdn.com/S1877705815043490/1-s2.0-S1877705815043490-main.pdf?_tid=80b89b4c-e74c-4cd1-81e8-38cc102668cd&acdnat=1524509229_6ef0d3119367364dd9736ec3b2ecfbd4)
* [Part of speech / Claim parsing](https://arxiv.org/pdf/1605.01744.pdf)

### Patent Generation
* [Grammar matching (stories -> patents)](http://lav.io/2014/05/transform-any-text-into-a-patent-application/)

### General NLP
* [Deciding if NLP is feasible](https://www.searchtechnologies.com/nlp-project-feasibility-flowchart)
* [Overview of NLP embedding](https://www.searchtechnologies.com/blog/natural-language-processing-techniques)
* [Embed / Encode / Attend / Predict for document classification (spacy)](https://explosion.ai/blog/deep-learning-formula-nlp)
* [Package for keyword search](https://medium.com/@vi3k6i5/search-millions-of-documents-for-thousands-of-keywords-in-a-flash-b39e5d1e126a)

### NLP Workflow
* [Pre-processing: NLTK vs Spacy](https://blog.thedataincubator.com/2016/04/nltk-vs-spacy-natural-language-processing-in-python/)
* [Pre-processing: More NLTK vs Spacy](https://www.quora.com/What-are-the-advantages-of-Spacy-vs-NLTK)
* [Pre-processing: Counting package for big data](https://rare-technologies.com/counting-efficiently-with-bounter-pt-1-hashtable/)
* [Topic Modeling: Word2Vec Explanation](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)
* [Topic Modeling: Matrix interpretations of Word2Vec](https://rare-technologies.com/making-sense-of-word2vec/)
* [Topic Modeling: Word2Vec Pre-trained Vectors](http://ahogrammer.com/2017/01/20/the-list-of-pretrained-word-embeddings/)
* [Evaluation: Topic coherence](http://aclweb.org/anthology/D/D12/D12-1087.pdf)
* [Debugging: Memory usage trackers](https://www.pluralsight.com/blog/tutorials/how-to-profile-memory-usage-in-python)

## Companies
* [Ambercite](https://www.ambercite.com/ambercite-ai/)
* [Teqmine](https://teqmine.com/patent-similarity/)
