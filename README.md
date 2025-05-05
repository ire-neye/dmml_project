# 📁 H9DMML Portfolio – x24139645

## 📌 Project Title

**Ensemble Learning for Predicting Hospital Readmission Using Electronic Health Records**

---

## 👩‍💻 Author

**Name:** Irene
**Student ID:** x24139645
**Course:** MSc Data Analytics
**Module:** Data Mining and Machine Learning (H9DMML)
**Institution:** National College of Ireland

---

## 📂 Project Structure

```
x24139645_H9DMML_Portfolio/
├── diabetes_project.ipynb       # UCI Diabetes Readmission Notebook
├── chunking_csv.ipynb           # Chunking CSV Notebook
├── mimic_iv.ipynb               # MIMIC-IV Readmission Notebook
├── README.md                    # This file
└── requirements.txt             # List of required packages
```

---

## 📝 Notebooks Overview

### 1. **diabetes\_project.ipynb**

* Dataset: UCI 130-US Hospitals Readmission Dataset
* Key Tasks:

  * Data cleaning & EDA
  * Feature selection (RFE, SelectKBest)
  * Model training: Random Forest, XGBoost, Logistic Regression, LightGBM
  * Hyperparameter tuning with `RandomizedSearchCV`
  * Evaluation metrics: Accuracy, F1, Precision, Recall, ROC-AUC

### 2. **mimic\_iv.ipynb**

* Dataset: MIMIC-IV v3.1 (de-identified ICU EHR data)
* Key Tasks:

  * Data merging & filtering
  * Balancing with undersampling
  * Model training & hyperparameter tuning
  * Evaluation metrics
  * Final ensemble model

---

## ⚙️ Requirements

Run this project in an environment with Python 3.7+ and the following packages:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
lightgbm
imblearn
```

You can install them using:

```bash
pip install -r requirements.txt
```

---

## 🧪 Running the Notebooks

1. Open each notebook in Jupyter or Google Colab.
2. Run cells sequentially from top to bottom.
3. Ensure the datasets are preloaded or paths are adjusted if needed (for private use only).

---

## 📜 Notes

* The models are trained on pre-processed datasets and may require substantial memory for MIMIC-IV due to size.
* All evaluation metrics and results discussed in the report are reproducible from these notebooks.
* SHAP is not used in this version but planned for future iterations.

---

Let me know if you’d like a version of this as a downloadable `.txt` or `.md` file!
