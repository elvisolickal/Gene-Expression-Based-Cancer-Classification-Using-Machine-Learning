# Machine Learning for Cancer Classification Using Gene Expression Data


## Overview

This project develops a machine learning pipeline to classify five cancer types using high-dimensional gene expression (RNA-Seq) data from **801 patient samples**. Since each sample contains **20,531 gene expression features**, feature selection techniques are used to reduce dimensionality and retain the most informative genes.

Multiple supervised machine learning algorithms are trained and compared to identify the best-performing model. The project also analyzes feature importance to improve model interpretability by identifying the genes that contribute most to the predictions.

---

## Objectives

- Explore and preprocess gene expression data.
- Perform feature selection to reduce dimensionality.
- Train multiple machine learning classification models.
- Compare model performance using standard evaluation metrics.
- Identify the best-performing classifier.
- Interpret predictions using feature importance analysis.

---

## Dataset

**Dataset:** TCGA Pan-Cancer HiSeq Gene Expression Dataset

- **Samples:** 801
- **Features:** 20,531 genes
- **Cancer Types:** 5

### Cancer Classes

- BRCA – Breast Invasive Carcinoma
- COAD – Colon Adenocarcinoma
- KIRC – Kidney Renal Clear Cell Carcinoma
- LUAD – Lung Adenocarcinoma
- PRAD – Prostate Adenocarcinoma

Dataset files:

```
data.csv
labels.csv
```

---

## Project Workflow

```
Dataset Extraction
        │
        ▼
Data Exploration
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Selection
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
        │
        ▼
Feature Importance Analysis
```

---

## Machine Learning Models

The following algorithms are implemented and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naïve Bayes
- XGBoost *(optional)*

---

## Evaluation Metrics

Models are compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost *(optional)*

---

## Project Structure

```
Machine-Learning-Cancer-Classification/
│
├── data/
│   ├── data.csv
│   └── labels.csv
│
├── notebooks/
│   └── Cancer_Classification.ipynb
│
├── results/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Machine-Learning-Cancer-Classification.git
cd Machine-Learning-Cancer-Classification
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Download the TCGA Pan-Cancer HiSeq dataset.
2. Place the dataset in the `data/` directory.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run the notebook sequentially to:
   - Load and explore the dataset
   - Preprocess the data
   - Perform feature selection
   - Train and evaluate models
   - Compare results
   - Analyze feature importance

---

## Expected Results

- Accurate classification of five cancer types.
- Reduced feature space through feature selection.
- Comparative analysis of multiple machine learning models.
- Identification of the best-performing classifier.
- Improved interpretability through feature importance analysis.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deep learning approaches
- SHAP/LIME explainability
- Web application deployment
- Support for additional cancer types

---

## License

This project is licensed under the MIT License.
