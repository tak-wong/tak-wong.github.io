---
title: Training Auto-Encoder-Based Optimizers for Terahertz Image Reconstruction

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Matthias Kahl
  - Peter Haring-Bolívar
  - Andreas Kolb
  - Michael Möller

# Author notes (optional)
author_notes:
  - ""

date: 2019-10-25T00:00:00.000Z

# Schedule page publish date (NOT publication date).
publishDate: 2019-10-25T00:00:00.000Z

# Publication type from the CSL standard.
# Accepts a single type but formatted as a YAML list (Hugo requirement).
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*German Conference on Pattern Recognition*"
publication_short: "*GCPR*"

abstract: |
  Terahertz (THz) sensing is a promising imaging technology for a wide variety of different applications. Extracting the interpretable and physically meaningful parameters for such applications, however, requires solving an inverse problem in which a model function determined by these parameters needs to be fitted to the measured data. Since the underlying optimization problem is nonconvex and very costly to solve, we propose learning the prediction of suitable parameters from the measured data directly. More precisely, we develop a model-based autoencoder in which the encoder network predicts suitable parameters and the decoder is fixed to a physically meaningful model function, such that we can train the encoding network in an unsupervised way. We illustrate numerically that the resulting network is more than 140 times faster than classical optimization techniques while making predictions with only slightly higher objective values. Using such predictions as starting points of local optimization techniques allows us to converge to better local minima about twice as fast as optimizing without the network-based initialization.

# Summary. An optional shortened abstract.
summary: "An unsupservised model-based autoencoder in which the encoder network predicts suitable parameters and the decoder is fixed to a physical model."

tags:
  - THz
  - Model-based Autoencoder
  - Computational Imaging
  - Image Reconstruction

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: "10.1007/978-3-030-33676-9_7"
    arxiv: "1907.01377"

# Custom links
links:
#   - type: pdf
#     url: ""
  - type: code
    url: "https://github.com/tak-wong/THz-AutoEncoder"
  - type: dataset
    url: "https://www.cg.informatik.uni-siegen.de/data/THz-AutoEncoder/thz-dataset.zip"
#   - type: poster
#     url: ""
#   - type: project
#     url: ""
#   - type: slides
#     url: ""
#   - type: source
#     url: ""
#   - type: video
#     url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project folder name without extension.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck folder name without extension.
slides: ""

# draft: true
status: published
---

<!-- Add the paper text or supplementary notes. Markdown, math, and code are supported. -->

## How to cite

Wong, Tak Ming, Matthias Kahl, Peter Haring-Bolívar, Andreas Kolb, and Michael Möller. "Training auto-encoder-based optimizers for terahertz image reconstruction." In German Conference on Pattern Recognition, pp. 93-106. Cham: Springer International Publishing, 2019.

## Bibtex

    @inproceedings{wong2019training,
        title={Training auto-encoder-based optimizers for terahertz image reconstruction},
        author={Wong, Tak Ming and Kahl, Matthias and Haring-Bol{\'\i}var, Peter and Kolb, Andreas and M{\"o}ller, Michael},
        booktitle={German Conference on Pattern Recognition},
        pages={93--106},
        year={2019},
        organization={Springer}
    }