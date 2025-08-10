# Comprehensive ML Pipeline on Heart Disease UCI Dataset

This project was built as part of the **Sprints x Microsoft Summer Camp**, focusing on real-world machine learning pipelines, model deployment, and interactive UI development using the Heart Disease UCI dataset.

---

## Project Overview

This repo implements a full machine learning workflow on the Heart Disease UCI dataset, including:

- Data preprocessing & cleaning (handling missing values, encoding, scaling)  
- Dimensionality reduction with PCA  
- Feature selection using statistical and ML-based methods  
- Supervised learning with Logistic Regression, Decision Trees, Random Forest, and SVM  
- Unsupervised learning via K-Means and Hierarchical Clustering  
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV  
- Model export and pipeline saving for reproducibility  
- **Bonus:** Streamlit UI for real-time predictions  
- **Bonus:** Deployment with Ngrok for public access  

---

## Folder Structure

- `data/` — cleaned datasets ready for modeling  
- `models/` — saved trained models (.pkl files)  
- `notebooks/` — step-by-step Jupyter notebooks for each phase:  
  - `01_data_preprocessing.ipynb`  
  - `02_pca_analysis.ipynb`  
  - `03_feature_selection.ipynb`  
  - `04_supervised_learning.ipynb`  
  - `05_unsupervised_learning.ipynb`  
  - `06_hyperparameter_tuning.ipynb`  
- `results/` — evaluation metrics and plots  

---


## Key Features

* **Robust data cleaning and EDA** to understand and prepare the dataset
* **Dimensionality reduction with PCA** to focus on most important features
* **Feature selection combining model-based and statistical methods** for better performance
* **Supervised classification models** with thorough evaluation metrics (accuracy, precision, recall, F1-score, ROC-AUC)
* **Unsupervised clustering** with K-Means and Hierarchical methods, including elbow method and dendrogram visualization
* **Hyperparameter tuning** with GridSearchCV and RandomizedSearchCV to squeeze out best model performance
* **Model export** with `.pkl` files including preprocessing pipelines for reproducibility
