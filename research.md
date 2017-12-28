---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "Characterize transcription factor binding in a shared space"
      author:  "Yuan H, Kshirsgar M, Leslie CS"
      journal: "in preparation"
      year:    "2018"

    - title: "Topic model for infering transcription factor binding jointly from SELEX-seq and ATAC_seq"
      author:  "Kshirsgar M, Yuan H, Leslie CS"
      journal: "in preparation"
      year:    "2018"

    - title:   "characterization of global BRD binding pattern"
      author:  "Schaefer U, Yuan H, Leslie CS, Tarakhovsky A"
      journal: "in preparation"
      year:    "2018"

    - title:   "Stage-specific human induced pluripotent stem cells map the progression of meyloid transformation to transplantable leukemia"
      author:  "Kotini AG, Chang CJ, Chow A, Yuan H, et al."
      journal: "Cell Stem Cell"
      year:    "2017"
      url:     "http://www.cell.com/cell-stem-cell/abstract/S1934-5909(17)30031-0"

    - title:   "Multitask learning improves prediction of cancer drug sensitivity"
      author:  "Yuan H, Paskov I, Paskov H, Gonzalez AJ, Leslie CS"
      journal: "Scientific Reports"
      year:    "2016"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4994023/"

    - title:   "Investigation of maternal genotype effects in autism by genome-wide association"
      author:  "Yuan H, Dougherty JD"
      journal: "Autism Research"
      year:    "2014"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3989385/"

    - title:   "Translational profiling of hypocretin neurons identifies candidate molecules for sleep regulation"
      author:  "Dalal J, Roh JH, Shah S, Yuan H, et al."
      journal: "Gene & Development"
      year:    "2013"
      url:     "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3605469/"


---

My research interests include both developing machine learning methods to address biological relevant questions, and understanding complex biological systems and processes by next-generation sequence data analysis.

## Publications (peer reviewed)

{% assign thumbnail="left" %}

{% for pub in page.pubs %}
{% if pub.image %}
{% include image.html url=pub.image caption="" height="100px" align=thumbnail %}
{% endif %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}* {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

{% endfor %}
