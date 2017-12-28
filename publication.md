---
layout: page
permalink: /publication/
title: Publication
pubs:

    - title:   "Characterize transcription factor binding in a shared space."
      author:  "Yuan H, Kshirsgar M, Leslie CS."
      journal: "in preparation"
      year:    "2018"

    - title: "Topic model for infering transcription factor binding jointly from SELEX-seq and ATAC-seq."
      author:  "Kshirsgar M, Yuan H, Leslie CS."
      journal: "in preparation"
      year:    "2018"

    - title:   "Characterization of global BRD binding pattern."
      author:  "Schaefer U, Yuan H, Leslie CS, Tarakhovsky A."
      journal: "in preparation"
      year:    "2018"

    - title:   "Stage-specific human induced pluripotent stem cells map the progression of meyloid transformation to transplantable leukemia."
      author:  "Kotini AG, Chang CJ, Chow A, Yuan H, et al."
      journal: "Cell Stem Cell"
      year:    "2017"
      url:     "http://www.cell.com/cell-stem-cell/abstract/S1934-5909(17)30031-0"

    - title:   "Multitask learning improves prediction of cancer drug sensitivity."
      author:  "Yuan H, Paskov I, Paskov H, Gonzalez AJ, Leslie CS."
      journal: "Scientific Reports"
      year:    "2016"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4994023/"

    - title:   "Investigation of maternal genotype effects in autism by genome-wide association."
      author:  "Yuan H, Dougherty JD."
      journal: "Autism Research"
      year:    "2014"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3989385/"

    - title:   "Translational profiling of hypocretin neurons identifies candidate molecules for sleep regulation."
      author:  "Dalal J, Roh JH, Shah S, Yuan H, et al."
      journal: "Gene & Development"
      year:    "2013"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3605469/"


---

## Publications

{% assign thumbnail="left" %}

{% for pub in page.pubs %}
[{{pub.title}}]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})
{{pub.author}}
*{{pub.journal}}*
*{{pub.year}}*

{% endfor %}

## Conferences
Kshirsagar M, Yuan H\*, Leslie CS. Topic model for inferring transcription factor binding profiles jointly from SELEX-seq and ATAC-seq. CSHL New York Quantitative Biology Meeting, August 2017. (*Oral presenter).

Yuan H\*, Paskov I, Paskov H, González AJ, Leslie CS. Multitask learning improves prediction of cancer drug sensitivity, NYAS Machine Learning Symposium, March 2016 (*Oral presenter)

Paskov I, Yuan H\*, Paskov H, González AJ, Leslie CS. Joint learning over drugs improves prediction of cancer drug response, RECOMB/ISCB Conference on Regulatory and Systems Genomics, Abstract and Oral Presentation, 2014. (*Oral presenter)

Dougherty JD, Yuan H, Constantino JN. Testing the Molecular Genetic Basis of Transmission of Autism Risk by Healthy Mothers, the International Meeting for Autism Research, Donostia, Spain, 2013.

