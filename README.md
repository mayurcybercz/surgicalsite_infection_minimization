# surgicalsite_infection_minimization
Minimizing Deep Incisional and Organ/Space Surgical site infections (SSIs) in California acute care hospitals using Predictive risk analysis


## Requirements

Python 3 and Anaconda and Jupyter notebook

conda install missingno imblearn

(Most of the libraries should already be present in anaconda distribution)

### Dataset
uploaded on google drive (access from link below)

https://drive.google.com/drive/folders/1f9fEMnXEKTqefRss5xLkt_oEIF1GbZUm?usp=sharing

### Notebooks
There are a total of 4 Jupyter Notebooks.
sepsis_data_handling is data cleaning notebook.
sepsis_rf_sample is the random forest model on sample data.
sepsis_rf is the random forest model with half of dataset size.
sepsis_smote_fs is random forest model with smote class balancing and feature selection.

data_baseline.pickle contains the clean train,val,test data

## Publication link
https://scholarworks.csun.edu/handle/10211.3/224642
