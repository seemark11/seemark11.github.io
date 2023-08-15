---
title: Subgroup Identification in Pancancer
summary: Identification of subgroups in pan-cancer samples using machine learning (ML) techniques applied on multi-omics data.
tags:
  - Machine Learning
  - Multi-omics Data Integration
  - Pancancer
date: '2022-09-27'

# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: Outline of pipeline
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Github
    url: https://github.com/seemark11/Pancancer-subgroup-identification
# url_code: ''
url_pdf: 'https://www.biorxiv.org/content/10.1101/2022.09.15.507989v2.abstract'
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Cancer is a heterogeneous disease and patients with tumors from different organs can share similar epigenetic and genetic alterations. Therefore, it is crucial to identify the novel subgroup of patients with similar molecular characteristics. It is possible to propose a better treatment strategy when the heterogeneity of the patient is accounted for during subgroup identification irrespective of the tissue of origin. In this work, mRNA, miRNA, DNA methylation, and protein expression features from pan-cancer samples were concatenated and non-linearly projected to lower dimension using machine learning (ML) algorithm. This data was then clustered to identify multi-omics based novel subgroups. The clinical characterization of these ML subgroups indicated significant differences in overall survival (OS) and disease free survival (DFS) (p-value < 0.0001). The subgroups formed by the patients from different tumors shared similar molecular alterations in terms of immune microenvironment, mutation profile, and enriched pathways. Further, decision-level and feature-level fused classification models were built to identify the novel subgroups for unseen samples. Additionally, the classification models were used to obtain the class labels for the validation samples and the molecular characteristics were verified. To summarize, this work identified novel ML subgroups using multi-omics data and showed that patients with different tumor types can be similar molecularly. We also proposed and validated the classification models for subgroup identification. The proposed classification models can be used to identify the novel multi-omics subgroups and the molecular characteristics of each subgroup can be used to design appropriate treatment regimen.

