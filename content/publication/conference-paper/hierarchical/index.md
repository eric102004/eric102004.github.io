---
title: 'Hierarchical Representations in Dense Passage Retrieval for Question-Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Philipp Ennen
  - Federica Freddi
  - admin
  - Po-Nien Kung
  - RenChu Wang
  - Chien-Yi Yang
  - Da-shan Shiu
  - Alberto Bernacchia

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''

date: '2023-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the Sixth Fact Extraction and VERification Workshop (FEVER) at EACL 2023"
publication_short: "The FEVER workshop at EACL 2023"

abstract: "An approach to improve question-answering performance is to retrieve accompanying information that contains factual evidence matching the question. These retrieved documents are then fed into a reader that generates an answer. A commonly applied retriever is dense passage retrieval. In this retriever, the output of a transformer neural network is used to query a knowledge database for matching documents. Inspired by the observation that different layers of a transformer network provide rich representations with different levels of abstraction, we hypothesize that useful queries can be generated not only at the output layer, but at every layer of a transformer network, and that the hidden representations of different layers may combine to improve the fetched documents for reader performance. Our novel approach integrates retrieval into each layer of a transformer network, exploiting the hierarchical representations of the input question. We show that our technique outperforms prior work on downstream tasks such as question answering, demonstrating the effectiveness of our approach."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2023.fever-1.2.pdf'
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
url_video: 'https://aclanthology.org/2023.fever-1.2.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
#---

#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}

#Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
---
