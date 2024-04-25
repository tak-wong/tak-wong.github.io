---
title: "Optimization-based Enhancement of THz Data and Image"
collection: publications
permalink: /publication/2023-wong2023optimization
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-11-25
venue: 'PhD Dissertation, University of Siegen'
authors: '<b>Tak Ming Wong</b>'
paperurl: 'http://dx.doi.org/10.25819/ubsi/10350'
citation: 'Wong, Tak Ming. "Optimization-based enhancement of THz data and image." (2023).'
teaser: /publications/wong2023optimization_teaser.png
# video: ''
# code: ''
# arxiv: ''
categories: [THz,Optimization,Image-Enhancement]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/publications/wong2023optimization_teaser.png" alt="Teaser Image" title="teaser" />

## Abstract
> THz imaging is significantly limited in its spatial resolution due to the substantially longer wavelength of the associated frequencies, which has made the problem of imaging beyond diffraction limit to be an emerging challenge in the THz research community. In this dissertation, an optimization-based THz data and imaging enhancement concept is introduced. In this context, inverse problems in THz data and image enhancement, such as parameter estimation, image reconstruction, denoising and deblurring, are expressed as mathematical optimization problems, in which the core components are a physical model and an optimizer. Instead of solely maximizing the subjective improvement in terms of the visual perception, the optimizer minimizes an objective measure between the THz physical model and the measured THz data. This concept enables various kinds of computational optimization methods, for example, classical gradient descent based optimizers and modern neural network based optimizers, to solve the non-convex optimization problems and to estimate the material-related THz parameters from the measured THz data. Experiments show that this concept is beneficial for resolution enhancement, the ability to find energy minima, the requirements of measured data size, the robustness of parameter estimation, and computational resources. This study demonstrates the advantages brought by the cross-disciplinary collaboration between the fields of THz imaging and visual computing.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @article{wong2023optimization,
        title={Optimization-based enhancement of THz data and image},
        author={Wong, Tak Ming},
        year={2023}
    }