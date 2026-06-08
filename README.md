# WillyKAYONDO Machine Learning Individual Project

## Project: Predicting Bacterial Vaginosis from Vaginal Microbiome Data

**Author:** Willy Kayondo  
**Date:** June 2026  
**Program:** MSc Bioinformatics

---

## Background
Bacterial Vaginosis (BV) is a common vaginal condition in African women. 
This project applies machine learning to predict BV status from vaginal 
microbiome (OTU) and metabolomics data from Rwandan women.

## Data Source
Rwanda vaginal microbiome dataset (srep14174)  
Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4585667/

## Files
- `WillyKAYONDO.ipynb` - Main analysis notebook
- `srep14174-s1.xls` - Patient metadata
- `srep14174-s2.xls` - GC-MS metabolomics data
- `srep14174-s4.xls` - OTU microbiome data

## Models Used
- SVM, Random Forest, XGBoost, Logistic Regression, KNN, Decision Tree

## Requirements
```
pip install pandas numpy scikit-learn xgboost matplotlib seaborn xlrd
```
