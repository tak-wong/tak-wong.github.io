---
title: "Project Granted: LIVR"
summary: "We are developing INR and Transformer-based frameworks to scale volumetric neural networks for massive synchrotron and biomedical CT datasets."
date: 2026-07-01
draft: false

# Featured image for cards/social
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  # caption: 'Credit or context (Markdown supported)'

cover:
  image: "featured.jpg"
  position:
    x: 0
    y: 0
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "✨"

# Authors are matched to profiles in content/authors/
authors:
  - me

tags:
  - Research Grant

content_meta:
  trending: true

status: published
---

<!-- Tip: open with the why, then show results, code, and next steps. -->

## Big News: Project LIVR is Granted! 🎉

I am thrilled to share that our latest research project, **LIVR** (**L**earnable **I**mplicit **V**olumetric **R**epresentations for High-resolution 3D Images), has been officially selected and funded under the Helmholtz AI project call 2025! 

Modern 3D imaging in materials science and biomedicine produces breathtaking volumetric data at micrometer and even nanometer scales. However, a single sample can easily reach **billions of voxels**. This massive scale creates a massive bottleneck: it completely overwhelms standard deep learning pipelines. 

To analyze these files today, researchers typically resort to patching, slicing, or aggressive downsampling. But these workarounds come at a steep cost—they break spatial continuity, destroy global context, and blur the subtle geometric cues (like micro-cracks or tiny blood vessels) that define the scientific value of the data. 

Our project aims to fix this. We are designing a pipeline that eliminates these destructive compromises entirely.

---

## Technical Pillars

Instead of processing rigid, heavy 3D voxel grids, our methodology bridges two cutting-edge paradigms to achieve scalable, high-fidelity analysis:

* **Implicit Neural Representations (INRs):** Encoding entire volumes as continuous mathematical functions to compactly capture full structural complexity without losing spatial continuity.
* **Dynamic Token Transformers:** Learning to intelligently focus limited memory and processing power exactly where the structural details matter most.
* **Conditioned Integration:** Unifying both strands into an agile framework where continuous weight spaces map seamlessly to task-ready tokens.

---

### 📋 Project Blueprint
* **Principal Investigators:** Prof. Dr. Klaus H. Maier-Hein (DKFZ), Dr. Julian Moosmann (Hereon), Dr. Tak Ming Wong (Hereon)
* **Collaborating Centres:** [German Cancer Research Center (DKFZ)](https://www.dkfz.de/en/medical-image-computing) & [Helmholtz-Zentrum Hereon](https://www.hereon.de/institutes/materials_physics/index.php.en)
* **Cross-Disciplinary Fields:** Information • Health • Matter
* **Validation:** Benchmark across a diverse mix of clinical radiological scans and high-resolution synchrotron CT datasets.

---

## What This Enables

By moving away from discrete, downsampled grids to continuous, attention-driven representations, this project aims to deliver:
* **Zero-loss fidelity:** Preserving the tiny, critical structural details that downsampling erases.
* **True scalability:** Enabling deep learning models to seamlessly ingest massive, gigavoxel-scale 3D volumes.
* **Modular tools:** Deploying robust, standalone open-source components for both the INR and Transformer communities.

Stay tuned for updates, code repositories, and preprints as the project kicks into high gear!

---

## Official Announcements & Coverage

* 🔗 [Helmholtz AI Project Call Awardees Announced at HAICON26](https://www.helmholtz.ai/detail/helmholtz-ai-project-call-2025-awardees-announced-at-haicon26/)
* 🔗 [Official Press Release at Helmholtz-Zentrum Hereon](https://www.hereon.de/institutes/metallic_biomaterials/news/120476/index.php.en)
