# 🩺 ML Pipeline Notebook Pediatric Bone Marrow Transplant Survival Prediction

**📌 Project Description**

This notebook demonstrates the end-to-end construction of a Machine Learning pipeline using the Pediatric Bone Marrow Transplantation dataset from the UCI Machine Learning Repository. The dataset contains detailed medical information about pediatric patients who underwent bone marrow transplantation — including donor and recipient characteristics, risk groups, immunological markers, and clinical outcomes.

The primary goal of this project is to predict patient survival status after transplantation based on these clinical and demographic features. The task is framed as a binary classification problem:

- 0 → Patient survived
- 1 → Patient did not survive
- 
Beyond building a predictive model, the purpose of this project is to showcase the complete ML workflow.

**📊 Dataset Overview**

The dataset (bone-marrow.arff) contains 187 samples with 36 features, covering:

Recipient information: age, gender, blood type, body mass, relapse status, etc.
Donor information: age, blood group, cytomegalovirus (CMV) status, HLA match, etc.
Transplantation details: stem cell source, risk group, relapse indicators, GVHD (Graft versus Host Disease) indicators, etc.
Outcome variables: survival_time (continuous), survival_status (binary target).
Many features are categorical but encoded as numbers; some are medical risk indicators. The dataset includes missing values and requires careful preprocessing.

**🎯 Project Goals**

Reproduce a rigorous ML workflow on a biomedical dataset.
Clean, preprocess, and explore the data to understand patterns and relationships.
Engineer features (normalization, encoding, discretization, variance filtering).
Select and compare classification models (e.g., Logistic Regression, Random Forest).
Evaluate models using accuracy, precision, recall, F1-score, ROC-AUC.
Optimize hyperparameters via GridSearchCV.
Validate the final model on a hold-out test set.
Build and save a robust ML pipeline for deployment and reproducibility.

**⚙️ Usage**

Place the file bone-marrow.arff in the working directory (or update the path in the script).
Run the notebook cell-by-cell in Jupyter or execute as a Python script .
The final trained pipeline will be saved as final_ml_pipeline.joblib for later use.
