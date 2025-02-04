---
title: "A Framework for the AI-based visualization and analysis of massive amounts of 4D tomography data for end users of beamlines"
collection: publications
permalink: /publication/2025-02-01-steffen2025framework
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-02-01
venue: '14th Conference on Industrial Computed Tomography (iCT) 2025'
authors: 'teffen Kieß, Thomas Lang, Tomas Sauer, A. Michael Stock, Andrei Chernov, Yipeng Sun, Andreas Maier, Tomáš Faragó, Alexey Ershov, Gabriel Lefloch, Guilherme Silva, Tilo Baumbach, Simon Zabler, Astrid Hölzing, Kilian Dremel, Ali Riza Durmaz, Akhil Thomas, Ingo Manke, Nikolay Kardjilov, Tobias Arlt, <b>Tak Ming Wong</b>, Regine Willumeit-Römer, Julian Moosmann, Berit Zeller-Plumhoff, Dieter Froning, Sven Simon'
paperurl: 'https://doi.org/10.58286/30717'
# citation: ''
teaser: publications/steffan2025framework_teaser.png
# video: ''
# code: ''
# arxiv: ''
categories: [CT,synchrotron imaging,neutron imaging]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/publications/steffan2025framework_teaser.png" alt="Teaser Image" />

## Abstract
> The size of 4D tomography datasets acquired at synchrotron or neutron imaging facilities can reach several terabytes, which presents a significant challenge for their evaluation. This paper presents a framework that allows a compressed dataset to be kept in memory and makes it possible to evaluate and manipulate the dataset without requiring enough memory to decompress the entire dataset. The framework enables the compensation of imaging artifacts, including the compression artifacts of the 4D dataset, through the integration of neural networks. The reduction of imaging artifacts can be performed at the imaging facility or at the user's home institution. This framework reduces the computational burden on the computing infrastructure of large synchrotron and neutron facilities by allowing end users to process datasets on their institution's computers. This is made possible by compressing TBs of data to less than 128 GB, allowing powerful PCs to process TBs of 4D tomography data. 

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


<!-- ## Bibtex

    @InProceedings{moosmann2024machine,
        title       = {Machine learning for the reconstruction and analysis of synchrotron-radiation tomography data},
        author      = {Moosmann, Julian P and Irvine, Sarah and Hailu, Dawit and Kazimi, Bashir and Wong, Tak and Yang, Xiaogang and Heuser, Philipp and Jentschke, Thomas and Kulvait, Vojtech and Zeller-Plumhoff, Berit and others},
        booktitle   = {Developments in X-Ray Tomography XV},
        volume      = {13152},
        pages       = {131520Z},
        year        = {2024},
        organization= {SPIE}
    } -->