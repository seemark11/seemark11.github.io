---
title: 'A feasible QRS detection algorithm for arrhythmia diagnosis'
    
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Aparna P

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# -

date: "2017-03-30"
doi: "10.1109/ICAEES.2016.7888004"
    
# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"
    
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]
    
# Publication name and optional abbreviated publication name.
publication: "IEEE"
publication_short: "IEEE"
    
abstract: "This paper presents a reliable QRS detection algorithm to detect and classify Electrocardiogram (ECG) waveform abnormalities by extracting features such as heart rate and duration of QRS complex. As R peak detection is the pivotal step in automatic electrocardiogram analysis, various mathematical operations like clipping, differentiation and squaring are carried out in the preprocessing stage to enhance the section containing the QRS complex. Thresholding is performed to detect the R peaks. In order to improve the accuracy of the algorithm search back technique is implemented to determine the missing R peaks and heart beat. Once the position of R peak is detected, positions of Q and S are determined using two different search intervals to take into account the anomalous conditions as well. The heart rate and QRS width are then computed and compared with the normal values to determine the degree and type of abnormality. MIT-BIH database is used to evaluate this algorithm. The algorithm gives sensitivity of 99.34% and positive predictivity of 96.79%. In the proposed algorithm complicated mathematical operations like Fourier Transform, Hilbert Transform or crosscorrelation are not computed, hence is convenient to realize."
#     
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
    
tags: [ECG, QRS, heart rate, MIT-BIH]
    
# Display this page in the Featured widget?
featured: false
    
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
    
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S2210670717314002'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
