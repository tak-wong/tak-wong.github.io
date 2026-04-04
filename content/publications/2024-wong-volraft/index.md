---
title: "VolRAFT: Volumetric Optical Flow Network for Digital Volume Correlation of Synchrotron Radiation-based Micro-CT Images of Bone-Implant Interfaces"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Julian Moosmann
  - Berit Zeller-Plumhoff

# Author notes (optional)
author_notes:
  - ""

date: 2024-06-18T00:00:00.000Z

# Schedule page publish date (NOT publication date).
publishDate: 2024-06-18T00:00:00.000Z

# Publication type from the CSL standard.
# Accepts a single type but formatted as a YAML list (Hugo requirement).
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE / CVF Computer Vision and Pattern Recognition Conference Workshops*"
publication_short: "CVPRW"

abstract: |
  In materials science research, digital volume correlation (DVC) analysis is commonly used to track deformations and strains to elucidate morphology-function relationships. Optical flow-based DVC is particularly popular because of its robustness to estimate the correlation as a dense deformation vector. Recently, computer vision researchers showed that network-based optical flow approaches can outperform classical iterative optical flow approaches. In this paper, we propose a supervised machine learning approach for digital volume correlation, VolRAFT, that estimates the 3D displacement vector between the reference volume and the deformed volume. The proposed approach extends the state-of-the-art network-based optical flow method, RAFT, from 2D images to 3D volumes such that it predicts the volumetric displacement vector from the input volume pairs. Experiments show that the proposed network performs well in estimating different displacement fields when compared to cutting-edge iterative DVC methods for bone-implant materials based on high resolution synchrotron-radiation micro-computed tomography imaging data.

# Summary. An optional shortened abstract.
summary: "VolRAFT: extend optical flow network RAFT to volumetric data for digital volume correlation (DVC)."

tags:
  - CT
  - Digital Volume Correlation (DVC)
  - Synchrotron Radiation CT (SRCT)
  - Optical Flow
  - Bone Implant

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # arxiv: ""
    doi: "10.1109/CVPRW63382.2024.00010"

# Custom links
links:
  - type: pdf
    url: "https://openaccess.thecvf.com/content/CVPR2024W/CV4MS/html/Wong_VolRAFT_Volumetric_Optical_Flow_Network_for_Digital_Volume_Correlation_of_CVPRW_2024_paper.html"
  - type: code
    url: "https://github.com/hereon-mbs/VolRAFT"
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
  - type: video
    url: "https://youtu.be/T9H2UkTeOxE?si=Rs6ppbgEsJSgjcHv&t=4860"

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

Wong, Tak Ming, Julian Moosmann, and Berit Zeller-Plumhoff. "VolRAFT: Volumetric Optical Flow Network for Digital Volume Correlation of Synchrotron Radiation-based Micro-CT Images of Bone-Implant Interfaces." In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 53-62. 2024.

## Bibtex

    @InProceedings{wong2024volraft,
        author    = {Wong, Tak Ming and Moosmann, Julian and Zeller-Plumhoff, Berit},
        title     = {VolRAFT: Volumetric Optical Flow Network for Digital Volume Correlation of Synchrotron Radiation-based Micro-CT Images of Bone-Implant Interfaces},
        booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
        month     = {June},
        year      = {2024},
        pages     = {53-62}
    }

