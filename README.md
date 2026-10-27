# Credit Card Fraud Detection Using Machine Learning

## Overview
This project applies machine learning techniques to detect fraudulent credit card transactions. It explores transaction data, addresses class imbalance, and compares classification approaches to identify potentially fraudulent activities.

## Objectives
- Analyze transaction data using exploratory data analysis (EDA).
- Handle class imbalance through undersampling.
- Identify important features associated with fraudulent transactions.
- Train and optimize Random Forest and XGBoost classifiers.
- Evaluate model performance using classification metrics.

## Technologies Used
- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Machine Learning:** Scikit-learn, XGBoost
- **Model Optimization:** GridSearchCV and cross-validation

## Project Workflow
1. Load and explore the credit card transaction dataset.
2. Analyze the distribution of legitimate and fraudulent transactions.
3. Prepare the data and address class imbalance.
4. Train and evaluate machine learning models.
5. Analyze feature importance and experiment with feature selection.
6. Tune model hyperparameters and compare evaluation metrics.

## Evaluation Metrics
The models are evaluated using accuracy, precision, recall, F1-score, confusion matrices, cross-validation, and ROC-AUC.

## Dataset
The notebook expects a dataset file named `creditcard.csv` in the project root directory. Obtain the dataset from its original provider and follow its usage and licensing terms.

**Note:** The dataset is not included in this repository.

## Installation and Usage

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Place `creditcard.csv` in the project root directory.
4. Open `Fraud_detection.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the notebook cells in order.

## Learning Outcomes
This project demonstrates practical experience in data analysis, imbalanced classification, feature importance, hyperparameter tuning, and machine learning model evaluation.

## Disclaimer
This project is for educational purposes and is not intended for real-world financial fraud prevention without further testing and validation.
