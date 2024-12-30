# Credit-Card-Fraud-Detection

## Overview

This project involves detecting fraudulent transactions in credit card data using machine learning techniques. The dataset used includes anonymized features and a binary target variable indicating whether a transaction is fraudulent.
## Dataset https://drive.google.com/file/d/1FpYk7FeSb2-bo_ZLAJ3Yrq7PV5nOHS-X/view?usp=sharing
## Key Choices

1. **Dataset:** The dataset consists of anonymized credit card transaction data with a binary target variable (`0` for legitimate transactions and `1` for fraudulent transactions).
2. **Preprocessing:** Steps include scaling features using StandardScaler and handling imbalanced data through techniques such as SMOTE (Synthetic Minority Oversampling Technique).
3. **Modeling:** Various machine learning models were evaluated, including logistic regression, decision trees, and ensemble methods.
4. **Evaluation Metrics:** Due to the class imbalance, metrics such as precision, recall, F1-score, and the ROC-AUC score were prioritized over accuracy.

## Setup Instructions

### Requirements

- Python 3.8+
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

### Installation

1. Clone the repository or download the notebook file.
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   If a `requirements.txt` file is not provided, install the libraries manually:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

### Running the Notebook

1. Open the notebook in Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook Credit\ Card\ Fraud\ Detection.ipynb
   ```
2. Execute the cells in sequential order to reproduce the results.

### Results

- Models were evaluated using a combination of precision, recall, F1-score, and ROC-AUC.
- The best-performing model achieved an ROC-AUC score of **[insert score here]**, balancing high recall for fraudulent transactions with minimal false positives.

## Reproducing the Results

1. Ensure the dataset is available in the correct format.
2. Follow the preprocessing steps outlined in the notebook.
3. Train and evaluate the models using the provided code.
4. Compare the results to the metrics mentioned above.

For additional details, refer to the comments and markdown cells in the notebook.

