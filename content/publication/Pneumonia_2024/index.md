---
abstract: <b>Background</b> Pneumonia is the leading cause of preventable mortality in children under the age of five. While accurate diagnosis is crucial, effective case management plays a pivotal role in reducing mortality, especially in primary care settings. Despite the accurate and widespread use of computer science in diagnosing pneumonia, prognosis studies remain comparatively scarce. In this context, we have developed a machine learning-based clinical decision support system for childhood pneumonia to enhance prognostic support in case management.<b>Methods</b> This study involved the analysis of data from 437 children diagnosed with pneumonia and admitted to our clinic between 2014 and 2020. Pediatricians classified the raw data set based on candidate features. Prior to the machine learning algorithms' experimental study using Pycaret, the SMOTE-Tomek method was applied to address the challenge of imbalanced datasets. Feature selection was conducted by assessing the SHAP values of the highest-performing algorithm, followed by re-modeling with the most critical clinical features. Hyperparameters were optimized, and ensemble methods were utilized to develop a robust predictive model.<b>Results</b> The optimized models demonstrated a prediction accuracy of 77-88% for pneumonia prognosis. It was observed that over 84% of severity determinations could be accurately made using five clinical features; hypoxia, respiratory distress, age, the Z score of weight for age, and previous antibiotic use before admission.<b>Conclusions</b> The experimental study highlights the potential of contemporary data science techniques, including oversampling, feature selection, and machine learning tools, in predicting the need for critical care in patients. Even with relatively small sample sizes, as in our study, machine learning methods can align with current medical understanding and offer significant insights.<b>Highlights</b>- Pneumonia is responsible for 14% of all deaths in children under five, totaling over 740,000 fatalities in 2019 alone.- Initiatives like WHO and UNICEF’s GAPPD aim to reduce mortality rates by focusing on vaccinations, sanitation, breastfeeding, and tackling pediatric HIV.- Accurate pneumonia diagnosis and timely treatment can lower mortality rates by up to 28%, although diagnosis poses challenges.- The scarcity of essential diagnostic equipment and trained personnel in underdeveloped regions increases mortality rates.- Data science and machine learning present promising avenues for managing pneumonia, especially in LMICs, with an emphasis on prognostic support.

author_notes:
-
authors:
- Serin 0
- Akbasli IT
- Bocutcu Cetin S
- Koseoglu B
- Deveci AF
- Ugur MZ
- Ozsurekci Y
date: "2024-02-23T00:00:00Z"
doi: "10.1101/2024.02.22.24303209"
featured: true
image: 
  caption: 'Graphical abstract'
  focal_point: ""
  preview_only: false
projects: []
publication: 'medRxiv'
publication_short: "*medRxiv*"
publication_types:
- "manuscript" #https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publishDate: "2024-02-23T00:00:00Z"

summary: "This study developed a machine learning-based tool for childhood pneumonia prognosis, analyzing data from 437 cases between 2014 and 2020. Using SMOTE-Tomek for dataset balancing and SHAP values for feature selection, the model achieved 77-88% accuracy in predicting pneumonia outcomes, with critical severity indicators identified. The research underscores the potential of data science and machine learning in enhancing pneumonia case management and prognosis, even with limited sample sizes."
tags: 
- Machine Learning
- Critical Care
title: 'Advancing primary care for childhood pneumonia: a machine learning-based approach to prognosis and case management'
# varsa alttakileri doldurabilirsin
url_code: ""
url_dataset: ""
url_pdf: "https://www.medrxiv.org/content/10.1101/2024.02.22.24303209v1.full.pdf+html"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---



