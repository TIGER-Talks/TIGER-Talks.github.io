---
title: Dense Retrieval with Apache Solr Neural Search
draft: false

event: "TIGER Talk: Dense Retrieval with Apache Solr Neural Search"

location: RMIT University & Online
address:
  street: 124 La Trobe St
  city: Melbourne
  region: VIC
  postcode: '3000'
  country: Australia

speaker: Alessandro Benedetti
speaker_url: "https://x.com/alexbenedetti"
summary: Alessandro Benedetti presents his talk on Dense Retrieval with Apache Solr Neural Search.
abstract: 'Neural Search is an industry derivation from the academic field of Neural information Retrieval. More and more frequently, we hear about how Artificial Intelligence (AI) permeates every aspect of our lives and this includes also software engineering and Information Retrieval. In particular, the advent of Deep Learning introduced the use of deep neural networks to solve complex problems that could not be solved simply by an algorithm. Deep Learning can be used to produce a vector representation of both the query and the documents in a corpus of information. Search, in general, comprises of performing four primary steps: - generate a representation of the query that describes the information need - generate a representation of the document that captures the information contained in it - match the query and the document representations from the corpus of information - assign a score to each matched document in order to establish a meaningful document ranking by relevance in the results With the Neural Search module, Apache Solr is introducing support for neural network based techniques that can improve these four aspects of search. This talk explores the first official contribution of Neural Search capabilities available from Apache Solr 9.0(may 2022): Approximate K-Nearest Neighbor Vector Search for matching and ranking. You will learn: - how Approximate Nearest Neighbor (ANN) approaches work, with a focus on Hierarchical Navigable Small World Graph (HNSW) - how the Apache Lucene implementation works - how the Apache Solr implementation works, with the new field type and query parser introduced - how to run KNN queries and how to use it to rerank a first stage pass Join us as we explore this new Apache Solr feature!'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-06-22T12:00:00+11:00'
date_end: '2022-06-22T13:00:00+11:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-06-22T12:00:00+11:00'

authors: [admin]
tags: [Talk, Neural Search, Dense Retrieval, Apache Solr]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

url_code: ''
url_pdf: 'https://ecir2022.org/uploads/sease_KNNsearch.pdf'
url_slides: 'https://www.slideshare.net/SeaseLtd/dense-retrieval-with-apache-solr-neural-searchpdf-252320449'
url_video: 'https://youtu.be/aG3x4ztDZRE'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

{{< youtube aG3x4ztDZRE >}}
