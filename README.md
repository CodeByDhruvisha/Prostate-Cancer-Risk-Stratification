# Prostate Cancer Risk Stratification using Gene Expression Data

## 📌 Overview
This project focuses on **prostate cancer risk stratification** using gene expression data and machine learning techniques.  
The goal is to identify molecular patterns that distinguish tumor and normal samples at both **gene-level** and **pathway-level**.

Dataset source: **GEO (GSE6919)**
---

## 🧬 Project Pipeline

### 1️⃣ Data Preprocessing
- Raw GEO expression matrix processing
- Probe-to-gene mapping
- Gene-level aggregation
- Sample label alignment (Tumor vs Normal)

Notebook: `01_Data_Preprocessing.ipynb`

---

### 2️⃣ Gene-Level Machine Learning
- Differential Expression Analysis (DEGs)
- Feature selection using statistically significant genes
- Machine learning models:
  - Logistic Regression
  - Random Forest
- Performance evaluation (Accuracy, ROC-AUC)

Notebook: `02_Gene_Level_ML.ipynb`

---

### 3️⃣ Pathway-Level Machine Learning
- Pathway scoring using biologically relevant gene sets
- Aggregation of gene expression into pathway scores
- ML modeling on pathway features
- Model interpretation via feature importance

Notebook: `03_Pathway_Level_ML.ipynb`

---

## 📁 Repository Structure
Prostate-Cancer-Risk-Stratification/ 
│── 01_Data_Preprocessing.ipynb
│── 02_Gene_Level_ML.ipynb
│── 03_Pathway_Level_ML.ipynb
│── gene_expression_matrix.csv 
│── labels_final.csv
│── DEGS.csv
│── README.md

---
## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Bioinformatics data analysis

---

## 🎯 Key Outcomes
- Identified significant DEGs associated with prostate cancer
- Demonstrated pathway-level modeling for biological interpretability
- Achieved meaningful classification performance using ML models

---
## 📊 Results Summary

- Gene-level models achieved strong classification performance (ROC-AUC evaluated)
- Pathway-level modeling improved biological interpretability
- Key cancer-associated pathways showed high feature importance
  
## 📌 Author
**Dhruvisha Vaghela**  
Bioinformatics | Machine Learning | Cancer Genomics
