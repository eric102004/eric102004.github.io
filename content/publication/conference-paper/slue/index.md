---
title: 'SLUE Phase-2: A Benchmark Suite of Diverse Spoken Language Understanding Tasks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Suwon Shon
  - Siddhant Arora
  - admin
  - Ankita Pasad
  - Felix Wu
  - Roshan Sharma
  - Wei-Lun Wu
  - Hung-Yi Lee
  - Karen Livescu
  - Shinji Watanabe

# Author notes (optional)
author_notes:
  - ''
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''

date: '2023-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (ACL 2023)"
publication_short: "ACL 2023"

abstract: "Spoken language understanding (SLU) tasks have been studied for many decades in the speech research community, but have not received as much attention as lower-level tasks like speech and speaker recognition. In this work, we introduce several new annotated SLU benchmark tasks based on freely available speech data, which complement existing benchmarks and address gaps in the SLU evaluation landscape. We contribute four tasks : question answering and summarization involve inference over longer speech sequences; named entity localization addresses the speech-specific task of locating the targeted content in the signal; dialog act classification identifies the function of a given speech utterance. In order to facilitate the development of SLU models that leverage the success of pre-trained speech representations, we will release a new benchmark suite, including for each task (i) curated annotations for a relatively small fine-tuning set, (ii) reproducible pipeline (speech recognizer + text model) and end-to-end baseline models and evaluation metrics, (iii) baseline model performance in various types of systems for easy comparisons. We present the details of data collection and annotation and the performance of the baseline models. We also analyze the sensitivity of pipeline models’ performance to the speech recognition accuracy, using more than 20 publicly availablespeech recognition models."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2023.acl-long.496.pdf'
url_code: 'https://github.com/asappresearch/slue-toolkit'
url_dataset: 'https://huggingface.co/datasets/asapp/slue-phase-2'
#url_poster: ''
url_project: 'https://asappresearch.github.io/slue-toolkit/'
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

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
