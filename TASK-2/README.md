# Customer Churn Prediction

## Problem Statement

Customer churn is a major challenge for telecom companies as customer attrition directly affects revenue and growth. The objective of this project is to develop a machine learning solution capable of predicting customer churn and identifying the factors influencing customer retention.

## Dataset

* Dataset: Telco Customer Churn Dataset
* Records after preprocessing: 7010
* Features: 30
* Target Variable: `Churn_Yes`

## Project Structure

```text
TASK-2/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
├── Customer_Churn_Prediction_Report.pdf
│
├── data/
│   ├── Telco-Customer-Churn.csv
│   └── Telco-Customer-Churn-Cleaned.csv
│
└── images/
    ├── churn_distribution.png
    ├── contract_churn.png
    ├── monthly_charge_vs_churn.png
    ├── correlation_heatmap.png
    └── confusion_matrix.png
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

The developed models were evaluated to predict customer churn and identify important factors influencing customer attrition. Key insights and detailed analysis are provided in `Customer_Churn_Prediction_Report.pdf`.

## Repository Contents

* `Customer_Churn_Prediction.ipynb` : Complete implementation.
* `data/` : Raw and cleaned datasets.
* `images/` : Visualizations and confusion matrix.
* `requirements.txt` : Project dependencies.
* `Customer_Churn_Prediction_Report.pdf` : Detailed report and findings.

