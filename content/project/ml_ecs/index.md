---
title: Machine Learning for Protein Dynamics Prediction
summary: We developed a machine learning based method (FingerprintContacts) for predicting alternative protein conformations through combination of agglomerative clustering and bioinformatics.
tags:
- Machine Learning
- Bioinformatics
date: "2019-12-21T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/feng_jf8
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Proteins are dynamic molecules which perform diverse molecular functions by adopting different three-dimensional structures. Recent progress in coevolution contacts prediction opens up new avenues for the de novo protein structure prediction from sequence information. However, it is still difficult to predict more than one conformation from coevolution contacts alone. This is due to the inability to deconvolute the complex signals of coevolution contacts, i.e. spatial contacts relevant for protein folding, conformational diversity, and ligand binding. 

Here, we introduce a machine learning based method, called FingerprintContacts, for extending the capabilities of coevolution contacts. We demonstrate the capabilities of FingerprintContacts on four ligand binding proteins with varying conformational motions. Furthermore, FingerprintContacts identifies small clusters of coevolution contacts which are preferentially located in the dynamically fluctuating regions. With the rapid growth in protein sequence information, we expect FingerprintContacts to be a powerful first step in structural understanding of protein functional mechanisms.
