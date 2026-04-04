---
title: "Self-supervised physics-informed generative networks for phase retrieval from a single X-ray hologram"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaogang Yang
  - Dawit Hailu
  - Vojtěch Kulvait
  - Thomas Jentschke
  - Silja Flenner
  - Imke Greving
  - Stuart I. Campbell
  - Johannes Hagemann
  - Christian G. Schroer
  - me
  - Julian Moosmann

# Author notes (optional)
author_notes:
  - ""

date: 2025-08-13T00:00:00.000Z

# Schedule page publish date (NOT publication date).
publishDate: 2025-08-13T00:00:00.000Z

# Publication type from the CSL standard.
# Accepts a single type but formatted as a YAML list (Hugo requirement).
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Optics Express*"
publication_short: ""

abstract: |
  X-ray phase contrast imaging significantly improves the visualization of structures with weak or uniform absorption, broadening its applications across a wide range of scientific disciplines. Propagation-based phase contrast is particularly suitable for time- or dose-critical in vivo/in situ/operando (tomography) experiments because it requires only a single intensity measurement. However, the phase information of the wave field is lost during the measurement and must be recovered. Conventional algebraic and iterative methods often rely on specific approximations or boundary conditions that may not be met by many samples or experimental setups. In addition, they require manual tuning of reconstruction parameters by experts, making them less adaptable for complex or variable conditions. Here we present a self-learning approach for solving the inverse problem of phase retrieval in the near-field regime of Fresnel theory using a single intensity measurement (hologram). A physics-informed generative adversarial network is employed to reconstruct both the phase and absorbance of the unpropagated wave field in the sample plane from a single hologram. Unlike most state-of-the-art deep learning approaches for phase retrieval, our approach does not require paired, unpaired, or simulated training data. This significantly broadens the applicability of our approach, as acquiring or generating suitable training data remains a major challenge due to the wide variability in sample types and experimental configurations. The algorithm demonstrates robust and consistent performance across diverse imaging conditions and sample types, delivering quantitative, high-quality reconstructions for both simulated data and experimental datasets acquired at beamline P05 at PETRA III (DESY, Hamburg), operated by Helmholtz-Zentrum Hereon. Furthermore, it enables the simultaneous retrieval of both phase and absorption information.

# Summary. An optional shortened abstract.
summary: "SelfPhish: self-supservised and physics-informed GANs for phase retrieval."

tags:
  - CT
  - Phase Retrieval
  - Synchrotron Radiation CT (SRCT)
  - GANs
  - nanoCT

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: "2508.15530"
    doi: "10.1364/OE.569216"

# Custom links
links:
#   - type: pdf
#     url: ""
#   - type: code
#     url: ""
#   - type: dataset
#     url: ""
#   - type: poster
#     url: ""
#   - type: project
#     url: ""
#   - type: slides
#     url: ""
#   - type: source
#     url: ""
  # - type: video
  #   url: ""
  - name: "Supplementary"
    url: "https://doi.org/10.6084/m9.figshare.29803343"

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

> [!NOTE]
> :trophy: This paper is highlighted as an Editors\' Pick.

## How to cite

Yang, Xiaogang, Dawit Hailu, Vojtěch Kulvait, Thomas Jentschke, Silja Flenner, Imke Greving, Stuart I. Campbell, Johannes Hagemann, Christian G. Schroer, Tak Ming Wong, and Julian Moosmann. "Self-supervised physics-informed generative networks for phase retrieval from a single X-ray hologram." Optics Express 33, no. 17 (2025): 35832-35851.

## Bibtex

    @article{yang2025self,
        title={Self-supervised physics-informed generative networks for phase retrieval from a single X-ray hologram},
        author={Yang, Xiaogang and Hailu, Dawit and Kulvait, Vojt{\v{e}}ch and Jentschke, Thomas and Flenner, Silja and Greving, Imke and Campbell, Stuart I and Hagemann, Johannes and Schroer, Christian G and Wong, Tak Ming and Moosmann, Julian},
        journal={Optics Express},
        volume={33},
        number={17},
        pages={35832--35851},
        year={2025},
        publisher={Optica Publishing Group}
    }



