---
title: 'DeepMPS: Development and validation of a deep learning model for whole slide image base prognostic prediction of low grade Lung adenocarcinoma patients'
    
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Akshay Jagjampi 
- admin
- Prabhat S Malik 
- Deepali Jain 
- Naveen M B 
- Sudhanshu Shukla 

author_notes:
- "Equal contribution"
- "Equal contribution"
-
-
- "Equal contribution"
- "Equal contribution"

date: "2022-12-30"
doi: "10.1101/2022.12.27.522072"
    
# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"
    
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]
    
# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: "bioRxiv"
    
abstract: "Lung adenocarcinoma (LUAD) is one of the most common cancers, and patients’ prognostication is crucial for treatment decisions. Histopathological images are the most generally accessible clinical information, however they have not been employed in clinical settings for prognosis. In this study, we used WSIs and clinical data from TCGA (training and testing) and East Asian Cohort (EAS, Validation) to develop and validate DL-based prognosticator. To circumvent the need for manual ROI generation, WSIs from these patients were divided into smaller patches and scored. DeepMPS prediction model was built using the top scoring 226,383 patches. The DeepMPS model showed a C-index of 0.638 in the TCGA training cohort. The univariate and multivariate cox regression analysis identified DeepMPS as an independent predictor of survival (HR: 9.48, p-value: $<$ 0.0001) in the training cohort. The training cohort of patients was separated into low and high-risk groups at various points. Kaplan-Meier analysis showed the highest difference in survival of low and high-risk patients at the 75th percentile (HR: 3.58, 95% CI: 2.57-5.00, p-value: $<$ 0.0001). At the same cut-off as the training samples, TCGA testing cohort patients demonstrated a significant difference in survival when split into low and high-risk patients (HR: 2.30, 95% CI: 1.11-4.82, p-value: 0.044). The DeepMPS model was validated in the EAS cohort patients. DeepMPS risk score significantly segregated EAS patients into low and high-risk groups at the same cut-off point as the training cohort (HR: 2.09, 95% CI: 1.11-3.97, p-value: 0.008). In multivariate Cox regression analysis, the DeepMPS score outperformed the stage in survival prediction. We also compared the DeepMPS model with the previously developed DL-based model to show that it was the best predictor of survival with the highest C-index. In conclusion, we developed a robust DL-based prognostic model which can predict the LUAD outcome without manual intervention using histopathological images."
    
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
    
tags: [Lung cancer, H $\&$ E, WSI, Prognostic model, CNN]
    
# Display this page in the Featured widget?
featured: true
    
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
    
url_pdf: 'https://www.biorxiv.org/content/10.1101/2022.12.27.522072v1.abstract'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
