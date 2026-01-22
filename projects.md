---
layout: page
title: Research
permalink: /projects/
---

<div class="research-section" markdown="1">

## ML-Based Therapeutic Target Discovery

An important focus of my research is building frameworks for therapeutic target discovery that bridge human genetics, regulatory genomics, and machine learning.

My work transfers sequence-to-function models into disease-relevant cellular contexts to infer gene regulatory networks, identify disrupted pathways and regulatory mechanisms, and mechanistically interpret disease-associated variants. By integrating statistical genetics (fine-mapping, QTL colocalization) with sequence-based deep learning, this approach enables the prioritization of therapeutic targets with interpretable regulatory mechanisms.

We applied this framework across multiple disease areas to uncover regulatory genes and pathways with strong translational potential.

<div class="related-work" markdown="1">
**Related work:** [Borzoi-PEFT](https://www.biorxiv.org/content/10.1101/2025.05.26.656171v2) (*Genome Biology*, 2026)
</div>

</div>

<div class="research-section" markdown="1">

## Efficiency and Interpretability of Long-Context Models

As DNA sequence models increasingly adopt long-context architectures, computational demands have grown dramatically—training time has expanded from hours to days or months, while inference and interpretation (e.g., *in silico* saturation mutagenesis) have become equally expensive.

I am developing more efficient approaches across the entire modeling pipeline, including architectural innovations, parameter-efficient training and transfer strategies, and scalable model interpretation methods. These advances make it feasible to apply foundational models to new biological contexts and enable mechanistic interpretation at scale.

<div class="related-work" markdown="1">
**Related work:** [Borzoi-PEFT](https://www.biorxiv.org/content/10.1101/2025.05.26.656171v2) (*Genome Biology*, 2026), [Borzoi](https://www.nature.com/articles/s41588-024-02053-6) (*Nature Genetics*, 2025), [Borzoi-PRIME](https://www.biorxiv.org/content/10.1101/2025.06.10.658961v1) (*bioRxiv*, 2025)
</div>

</div>

<div class="research-section" markdown="1">

## Sequence-Based Models of Chromatin Accessibility

Chromatin accessibility is particularly well-suited for short-context DNA sequence models. Unlike gene expression which benefits from long-range interactions, accessibility signals can be accurately predicted from local sequence features, making them tractable for single-cell resolution modeling.

My work focuses on developing models that carefully account for assay biases and technical artifacts, capture true regulatory signals in chromatin accessibility data, and link these signals to gene expression. This enables effective gene regulatory network inference and interpretation of regulatory variants at single-cell resolution.

<div class="related-work" markdown="1">
**Related work:** [scBasset](https://www.nature.com/articles/s41592-022-01562-8) (*Nature Methods*, 2022), [BindVAE](https://link.springer.com/article/10.1186/s13059-022-02723-w) (*Genome Biology*, 2022), [BindSpace](https://www.nature.com/articles/s41592-019-0511-y) (*Nature Methods*, 2019)
</div>

</div>

