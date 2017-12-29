---
layout: page
title: Research
permalink: /research/
---
### Research interests
**Computational Biology**: transcription factor binding site prediction, drug sensitivity prediction, next-generation sequencing analysis. <br />
**Machine Learning**: generalized linear models, multitask learning, word embedding, probablistic models.

### Characterize transcription factor binding patterns
Using *in vitro* binding profiles of transcription factors, we implemented popular methods in natural language processing such as word embedding and topic models and try to characterize the binding pattern of different transcription factors as probablity distribution over short sequences (kmers). Based on the models we learned and genome-wide accessibility landscape, we try to decode transcription factor binding network in various cell types. 

### Predict cancer drug response using multitask learning
Using publicly available drug response and molecular characterization data sets of cancer cell lines, we developed a novel multi-task learning approach to predict drug sensitivity. While traditional approaches train a model for each drug independently, our model train one model for all drugs at once. Our model exploits the relationship between drugs to improve prediction performance. We implemented a trace norm regularized regression model that outperformed elastic net single-task learning model on all data sets.

### Collaboration projects
I engage in a number of collaborative projects to study cancer biology and immunology from a data-driven prospective. Meanwhile, together with my colleagues, we established a pipeline to process next-genereation sequencing data (RNA-seq, ChIP-seq, ATAC-seq) in an efficient and reproducible manner. These projects include: 
* identify target genomic regions for safe and efficient CRISPR editing in CAR-T cells, collaboration with [Michel Sadelain] lab;
* study the roles of BET proteins in response to viral infection, collaboration with [Alexander Tarakhovsky] lab;
* study characteristics of leukemia induced pluripotent stem cells, collaboration with [Michael Kharas] and [Eirini Papapetrou] lab;
* study expression changes in mouse regulatory T cells with gastrointestinal stromal tumors, collaboration with [Ronald DeMatteo] lab.

[Michel Sadelain]:https://www.mskcc.org/research-areas/labs/michel-sadelain
[Alexander Tarakhovsky]:https://www.rockefeller.edu/our-scientists/heads-of-laboratories/979-alexander-tarakhovsky/
[Michael Kharas]:https://www.mskcc.org/research-areas/labs/michael-kharas
[Eirini Papapetrou]:http://icahn.mssm.edu/profiles/eirini-papapetrou
[Ronald DeMatteo]:https://www.mskcc.org/experience/physicians-at-work/ronald-dematteo-work


