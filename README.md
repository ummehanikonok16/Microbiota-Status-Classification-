# Microbiota-Status-Classification-
This project involves an end-to-end data science workflow focused on healthcare data, using exploratory data analysis, feature engineering, and baseline machine learning models Baseline Models: Logistic Regression, Random Forest, XGBoost, Advanced Models: ANN, LightGBM, ransformer-Based Model: TabNet.

## 📊 Project Overview

The notebook performs a comprehensive analysis of healthcare-related data with the goal of building predictive models. Key stages in the pipeline include:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Handling Class Imbalance using SMOTE
- Baseline Modeling using machine learning classifiers
- Model Evaluation with ROC-AUC and confusion matrix
- Model Interpretability with SHAP

## 🗂️ Dataset Description

The dataset used in this notebook is:

**Filename:** `health_data_10000_chunk.csv`  
**Location:** Mounted from Google Drive (`/content/drive/MyDrive/SM technology/`)
This data has 1 target colum named "Current status of microbiota" and 55 feature column among them top 20 imporatnt features are given below:
Comparison with optimal values

BMI

Height (cm)

Weight (kg)

Average sleep hours (hours)

Daily water intake (liters)

Frequency of bowel movements

Weekly consumption of whole grains (portions)

Weekly consumption of plant proteins (portions)

Weekly consumption of animal proteins (portions)

Weekly consumption of fruits (portions)

Weekly consumption of vegetables (portions)

Weekly consumption of fermented foods (portions)

Weekly consumption of dairy products (portions)

Stress level (1-10 scale)

Weekly frequency of physical activity (per week)

Stool consistency (Bristol scale)

Meal times

Difficult digestion

Vitamins

## ⚙️ Setup Instructions

To run this notebook:

1. Clone the repository or download the `.ipynb` file.
2. Open in [Google Colab](https://colab.research.google.com/) for easiest compatibility (especially for mounting Google Drive).
3. Install dependencies (within Colab or locally):

```bash
pip install shap optuna imbalanced-learn scikit-learn pandas matplotlib seaborn
```

4. Mount Google Drive (in Colab):

```python
from google.colab import drive
drive.mount('/content/drive')
```

5. Load the dataset and execute each cell step-by-step.

## ✅ Key Results

Preprocessing:

Handled missing values

Encoded categorical variables

Scaled numerical features

SMOTE: Used to handle class imbalance

Models: Baseline ML models such as logistic regression and random forest

Metrics:

roc_auc_score for classification performance

confusion_matrix to inspect prediction correctness

classification_report showing precision, recall, and F1-score

Interpretability:

SHAP values computed for model transparency and feature importance analysis

## 📌 Notes

- Make sure the dataset path is correctly set after mounting your Google Drive.
- Visualizations and outputs are embedded in the notebook for intuitive analysis.

## 📄 License

This project is open for academic or personal use under the MIT License.

## ✍️ Author

**Konok**
