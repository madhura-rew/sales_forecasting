# Insurance Fraud Detection

This project contains a Python notebook for analyzing an insurance claims dataset and building a fraud detection model.

## Overview

The notebook explores a dataset of insurance claim records and predicts whether a claim is genuine or fraudulent. It uses common machine learning techniques such as preprocessing, feature engineering, and classification models.

## Project Goal

Identify patterns in insurance claims that are associated with fraud, helping to flag suspicious claims before payment approval.

## Dataset

The project expects a CSV file named `fraud_oracle.csv`.

The dataset includes features such as:
- Claim month and week information
- Vehicle and policy details
- Driver and accident information
- Claim history information
- Policy type and coverage details
- Target label: `FraudFound_P`

## Notebook

The main analysis is in:
- `Untitled14.ipynb`

The notebook includes:
- Importing required Python libraries
- Uploading the dataset
- Loading and inspecting the data
- Checking missing values
- Visualizing fraud distribution
- Summarizing numerical statistics
- Preparing data for model training
- Training classification models
- Evaluating model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Dependencies

Install the required libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Open the notebook in Jupyter or Google Colab.
2. Upload the dataset file (`fraud_oracle.csv`) if it is not already present.
3. Run the cells in order.
4. Review the visualizations and model outputs.

## Example Workflow

```python
import pandas as pd

df = pd.read_csv("fraud_oracle.csv")
print(df.head())
```

## Model Evaluation

The notebook evaluates classification performance using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Notes

- This project appears to be a notebook-based exploratory data science workflow.
- It is designed to run in environments like Jupyter Notebook or Google Colab.
- The dataset is uploaded manually in the notebook, so you may need to place the CSV file in the working directory or upload it during execution.

## License

This repository does not currently include a license file. If you plan to share or publish this project publicly, consider adding an open-source license.

## Contact

If you want to extend or improve the project, feel free to contribute or modify the notebook and add additional model pipelines, feature engineering, or deployment scripts.
