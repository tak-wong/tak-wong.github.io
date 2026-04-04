---
title: Deep Neural Network as an Optimizer for FMCW THz Image Deblurring

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Hartmut Bauermeister
  - Matthias Kahl
  - Peter Haring Bolívar
  - Michael Möller
  - Andreas Kolb

# Author notes (optional)
author_notes:
  - ""

date: 2022-11-25T00:00:00.000Z

# Schedule page publish date (NOT publication date).
publishDate: 2022-11-25T00:00:00.000Z

# Publication type from the CSL standard.
# Accepts a single type but formatted as a YAML list (Hugo requirement).
publication_types: ["chapter"]

# Publication name and optional abbreviated publication name.
publication: "*ATHENA Research Book*"
publication_short: ""

abstract: |
  A stable estimation of the THz model parameters for low SNR configurations is essential to achieve acquisition times required for applications in, e.g., quality control. The deep optimization prior approach was introduced with application to the estimation of material-related model parameters from THz data, which is acquired by a FMCW THz scanning system. Conceptually, this approach estimates the desired THz model parameters by optimizing for the weights of a 3D spatially coupled deep neural network. This approach was verified numerically on various THz parameter estimation problems for synthetic and real data. In this paper, we propose to combine the deep optimization prior approach to the modern 2D blind deblurring method for the FMCW THz image resolution enhancement. The experimental results show that this approach improves the lateral resolution enhancement robustly under low SNR noise condition in comparison to the per-pixel curve fitting method.

# Summary. An optional shortened abstract.
summary: "Combine the deep optimization prior approach to the modern 2D blind deblurring method FMCW THz."

tags:
  - THz
  - Deconvolution
  - Computational Imaging
  - Parameter Estimation

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # arxiv: ""
    doi: "10.18690/um.3.2022.2"

# Custom links
links:
  - type: pdf
    url: "https://press.um.si/index.php/ump/catalog/view/735/1018/2679"
  # - type: code
  #   url: ""
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: ""
  # - type: source
  #   url: ""
  # - type: video
  #   url: ""

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

Wong, Tak Ming, Hartmut Bauermeister, Matthias Kahl, Peter Haring Bolıvar, Michael Möller, and Andreas Kolb. "Deep Neural Network as an Optimizer for FMCW THz Image Deblurring." ATHENA Research Book, Volume (2022): 13.

## Bibtex

    @article{wong2022deep,
        title={Deep Neural Network as an Optimizer for FMCW THz Image Deblurring},
        author={Wong, Tak Ming and Bauermeister, Hartmut and Kahl, Matthias and Bol{\i}var, Peter Haring and M{\"o}ller, Michael and Kolb, Andreas},
        journal={ATHENA Research Book, Volume},
        pages={13},
        year={2022}
    }
