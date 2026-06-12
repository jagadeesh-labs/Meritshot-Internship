# Customer Churn Prediction

## Problem Statement

Customer churn is a major challenge for telecom companies as customer attrition directly affects revenue and growth. The objective of this project is to develop a machine learning solution capable of predicting customer churn and identifying the factors influencing customer retention.

## Dataset

* Dataset: Telco Customer Churn Dataset
* Records after preprocessing: 7010
* Features: 30
* Target Variable: `Churn_Yes`

## Project Structure

## Project Structure

```text
TASK-2/
│
├── Customer_Churn_Prediction.ipynb
├── Customer_Churn_Prediction_Report.pdf
├── README.md
├── requirements.txt
│
├── data/
│   ├── Telco-Customer-Churn.csv
│   └── Telco-Customer-Churn-Cleaned.csv
│
└── images/
    ├── churn_distribution.png
    ├── churn_rate_by_contract.png
    ├── monthly_charges_vs_churn.png
    ├── feature_correlation.png
    ├── model_metrics_comparison.png
    ├── model_f1_comparison.png
    ├── confusion_matrix.png
    ├── cleaned_dataset_shape.jpg
    └── model_results.jpg
```


## Installation

Clone the repository:

```bash
git clone https://github.com/jagadeesh-labs/Meritshot-Internship.git
```

Navigate to the Task-2 directory:

```bash
cd Meritshot-Internship/TASK-2
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```


## Running the Project

Open the Jupyter notebook:

```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```

Execute the notebook cells sequentially to reproduce the analysis and model evaluation.

## Machine Learning Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

## Evaluation Metrics

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

## Results

The developed machine learning models were evaluated to predict customer churn and identify factors influencing customer retention. Exploratory data analysis and model evaluation revealed that contract type and monthly charges significantly affect customer churn. Logistic Regression achieved the highest F1 Score and was selected as the final model. Detailed methodology, visualizations, and findings are presented in `Customer_Churn_Prediction_Report.pdf`.

## Repository Contents

* `Customer_Churn_Prediction.ipynb` : Complete implementation of data preprocessing, exploratory data analysis, model training, and evaluation.
* `data/` : Raw and cleaned Telco Customer Churn datasets.
* `images/` : Visualizations generated during exploratory analysis and model evaluation.
* `requirements.txt` : Required Python dependencies.
* `Customer_Churn_Prediction_Report.pdf` : Comprehensive report containing methodology, results, key findings, and conclusions.


