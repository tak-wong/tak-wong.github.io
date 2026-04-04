---
title: "Deep Optimization Prior for THz Model Parameter Estimation"

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

date: 2022-01-07T00:00:00.000Z

# Schedule page publish date (NOT publication date).
publishDate: 2022-01-07T00:00:00.000Z

# Publication type from the CSL standard.
# Accepts a single type but formatted as a YAML list (Hugo requirement).
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE/CVF Winter Conference on Applications of Computer Vision*"
publication_short: "*WACV*"

abstract: |
  In this paper, we propose a deep optimization prior approach with application to the estimation of material-related model parameters from terahertz (THz) data that is acquired using a Frequency Modulated Continuous Wave (FMCW) THz scanning system. A stable estimation of the THz model parameters for low SNR and shot noise configurations is essential to achieve acquisition times required for applications in, e.g., quality control. Conceptually, our deep optimization prior approach estimates the desired THz model parameters by optimizing for the weights of a neural network. While such a technique was shown to improve the reconstruction quality for convex objectives in the seminal work of Ulyanov et. al., our paper demonstrates that deep priors also allow to find better local optima in the non-convex energy landscape of the nonlinear inverse problem arising from THz imaging. We verify this claim numerically on various THz parameter estimation problems for synthetic and real data under low SNR and shot noise conditions. While the low SNR scenario not even requires regularization, the impact of shot noise is significantly reduced by total variation (TV) regularization. We compare our approach with existing optimization techniques that require sophisticated physically motivated initialization, and with a 1D single-pixel reparametrization method.

# Summary. An optional shortened abstract.
summary: "Deep Optimization Prior approach allows to find better local optima in the non-convex energy landscape."

tags:
  - THz
  - Parameter Estimation
  - Computational Imaging
  - Deep Image Priors
  - Model-based Autoencoder

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # arxiv: ""
    doi: "10.1109/WACV51458.2022.00410"

# Custom links
links:
  - type: pdf
    url: "https://openaccess.thecvf.com/content/WACV2022/html/Wong_Deep_Optimization_Prior_for_THz_Model_Parameter_Estimation_WACV_2022_paper.html"
  - type: code
    url: "https://github.com/tak-wong/Deep-Optimization-Prior"
  - type: dataset
    url: "https://www.cg.informatik.uni-siegen.de/data/Deep-Optimization-Prior/thz-dataset-modelparam.zip"
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: ""
  # - type: source
  #   url: ""
  - type: video
    url: "https://www.youtube.com/watch?v=6JP-q5C9E_4"
  - name: "Supplementary"
    url: "https://openaccess.thecvf.com/content/WACV2022/supplemental/Wong_Deep_Optimization_Prior_WACV_2022_supplemental.pdf"

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

Wong, Tak Ming, Hartmut Bauermeister, Matthias Kahl, Peter Haring Bolívar, Michael Möller, and Andreas Kolb. "Deep optimization prior for thz model parameter estimation." In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision, pp. 3811-3820. 2022.

## Bibtex

    @inproceedings{wong2022deep,
        title={Deep optimization prior for thz model parameter estimation},
        author={Wong, Tak Ming and Bauermeister, Hartmut and Kahl, Matthias and Bol{\'\i}var, Peter Haring and M{\"o}ller, Michael and Kolb, Andreas},
        booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
        pages={3811--3820},
        year={2022}
    }