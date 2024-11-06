---
title: "Machine Learning for the Reconstruction and Analysis of Synchrotron-radiation Tomography Data"
collection: publications
permalink: /publication/2024-moosmann2024machine
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-10-23
venue: 'Optical Engineering + Applications, 2024, San Diego, California, United States'
authors: 'Julian Moosmann, Jennifer Ahrens, Sarah Irvine, <b>Tak Ming Wong</b>, Christian Lucas, Felix Beckmann, Jörg U. Hammel, D. C. Florian Wieland, Berit Zeller-Plumhoff, Philipp Heuser'
paperurl: 'https://doi.org/10.1117/12.3028018'
# citation: ''
teaser: publications/moosmann2024machine_teaser.png
# video: ''
# code: ''
# arxiv: ''
categories: [SRCT,DVC]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/publications/moosmann2024machine_teaser.png" alt="Teaser Image" />

## Abstract
> The Helmholtz-Zentrum Hereon is operating imaging beamlines for X-ray tomography (P05 IBL, P07 HEMS) for academic and industrial users at the synchrotron-radiation source PETRA III at DESY in Hamburg, Germany. The high flux density and coherence of synchrotron radiation enable high-resolution in situ/operando/in vivo tomography experiments and phase-contrast imaging techniques, respectively. Large amounts of 3D and 4D data are collected that are difficult to process and analyze. Recently, we have explored machine learning approaches for the reconstruction, processing and analysis of synchrotron-radiation tomography data. Here, we report on the application of supervised learning for multimodal data analysis to generate a virtual 3D histology, digital volume correlation of 4D in situ tomography data, and instance segmentation. Furthermore, we present findings related to unsupervised learning in the context of semantic segmentation.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @InProceedings{moosmann2024machine,
        title       = {Machine learning for the reconstruction and analysis of synchrotron-radiation tomography data},
        author      = {Moosmann, Julian P and Irvine, Sarah and Hailu, Dawit and Kazimi, Bashir and Wong, Tak and Yang, Xiaogang and Heuser, Philipp and Jentschke, Thomas and Kulvait, Vojtech and Zeller-Plumhoff, Berit and others},
        booktitle   = {Developments in X-Ray Tomography XV},
        volume      = {13152},
        pages       = {131520Z},
        year        = {2024},
        organization= {SPIE}
    }