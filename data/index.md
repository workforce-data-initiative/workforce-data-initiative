---
title: Open Skills API
redirect_from: /data/
---

The Open Skills Project is a public-private partnership lead by the University of Chicago focused on providing a dynamic, up-to-date, locally-relevant, and normalized taxonomy of skills and jobs that builds on and expands on the Department of Labor's O*NET data resources. It's aim is to improve our understanding of the labor market and reduce frictions in the workforce data ecosystem by enabling a more granualr common language of skills among industry, academia, government, and nonprofit organizations.


<img src="https://docs.google.com/drawings/d/19DTSTlxkOdTgieTWhnTNLAZtxn_ie63DV-vEGW_TP_E/pub?w=960&amp;h=720">

For more information on each specification, see below:

## Open Skills API

- [Overview][d]
- [Full Specification][spec-d]

## Open Skills Data Collaborative Working Group

## Open Skills Research Working Group

The Open Skills Research Working Group is dedicated to improving machine learning algorithms for translating workforce data into actionable insights about the dynamics of skills and jobs in the American economy. The Group is a made up of researchers from a variety of backgrounds with a main focus on natural language processing and large scale machine learning.

### What Has Been Done


Currently we have a machine learning pipeline, in Airflow and as Python scripts, that provides classes to preprocess data with NLP transforms, ingest known skills and job titles, label skills, job titles within corpora, generate special representations of skills and job titles and, finally, save off version controlled instances of data and outputs flowing through the pipeline stages.


### What We Are Working on Now


We are working on skill tagging, using NLP and other strategies, to identify known and unknown skills present in our partner data and other open sources. We use neural embeddings supplemented with more traditional NLP techniques for additional flexibility, which is especially important as new skills emerge over time.


We are improving job title, skill normalization research by making it easier to automatically extract skills, job titles as their canonical names from unlabeled text. We're particularly focused on generating suitable neural embeddings for these canonical normalization tasks and building skill and job title classifiers. Skill tagging, the initial identification of skills from unannotated text, also falls into this area of work. For skill, job title labeling, we are exploring active learning techniques to help the community generate quality labeled data at scale that is available for all.


### Research Papers Used
- [Concept-Based Information Retrieval using Explicit Semantic Analysis](http://www.cs.technion.ac.il/~gabr/publications/papers/Egozi2011CBI.pdf)
- [Bringing Order to the Job Market: Efficient Job Offer Categorization in E-Recruitment](http://www.ai.univ-paris8.fr/~cataldi/papers/sigir2015.pdf)
- [Semantic Similarity Strategies for Job Title Classification](https://arxiv.org/pdf/1609.06268v1.pdf)
- [An Empirical Evaluation of doc2vec with Practical Insights into Document Embedding Generation](https://arxiv.org/abs/1607.05368v1)
- [Distributed Representations of Words and Phrases and their Compositionality](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)


If you are interested in learning more about the research technical group, email us at info@dataatwork.org

## Open Skills Developer Working Group

{%include markdown-link-refs.html %}

