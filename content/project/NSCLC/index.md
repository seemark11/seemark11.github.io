---
title: Subgroup Identification in Non-small Cell Lung Cancer (NSCLC)
summary: Identify subgroups in non-small cell lung cancer (NSCLC) using machine learning (ML) techniques applied on multi-omics data.
tags:
  - Machine Learning
  - Multi-omics Data Integration
  - NSCLC
date: '2017-11-17'

# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: Outline of pipeline
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Github
    url: https://github.com/seemark11/NSCLC-subgroup-identification
# url_code: ''
url_pdf: 'https://www.nature.com/articles/s41598-023-31426-w'
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In this study, an autoencoder based approach is followed to non-linearly project high-dimensional multi-omics (mRNA, miRNA, methylation, and protein expression) non-small cell lung cancer (NSCLC) data to a lower dimensional space. The compressed data is then subjected to consensus k-means clustering to identify the clusters. Survival analysis of the resulting clusters revealed a significant difference in overall survival (p: 0.019, p: 0.169 for PCA based approach). Furthermore, molecular characterization of these subgroups using ANOVA, Tukey’s post-hoc test, and limma applied to each omic level, revealed that the group with the longest survival time had fewer genomic changes. To predict the subgroup of unseen patients, classification models (base classifiers) and their ensemble (linear and non-linearly combined base classifiers) with input features selected based on ANOVA, Tukey’s post-hoc test, limma, and fold-change (FC) from each omic level are built. Furthermore, the base classifiers along with the ensemble models are also built for various combinations of single-omic data. It is observed that multi-omics outperforms single-omic analysis, and the combination of classifiers proves to be a more accurate prediction model than the individual classifiers.

