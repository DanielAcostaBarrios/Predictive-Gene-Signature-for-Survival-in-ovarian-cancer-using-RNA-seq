# Predictive-Gene-Signature-for-Survival-in-Ovarian-Cancer
## Development and validation of a predictive gene signature for survival in ovarian cancer using RNA-seq data

Ovarian cancer is the most lethal gynecological neoplasm worldwide, mainly due to its late diagnosis in advanced stages and the absence of effective early detection methods. This project aims to develop a gene signature predictive of survival in ovarian cancer, using RNA-seq transcriptomic and clinical data available from public databases such as The Cancer Genome Atlas (TCGA). The analysis has been conducted using the R programming language.

The methodology included data collection and preprocessing to ensure quality, differential expression analysis that identified 54 genes significantly associated with survival, and the development of a predictive model based on Cox regression and machine learning algorithms. The model, built with 161 principal components, achieved a concordance index (C-index) of 0.7799, indicating robust accuracy after being evaluated through cross-validation. Functional analysis identified 34 enriched terms related to key processes in tumour progression. Additionally, a group of patients with unique clinical characteristics, classified as outliers, was identified, showing older age, increased mortality and a possible tendency toward advanced tumour stages. 

This model highlights the potential of transcriptomic data for developing predictive tools in oncology and opens new lines of research, such as validation in external cohorts and functional analysis of outliers.
