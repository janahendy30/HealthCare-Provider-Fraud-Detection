# HealthCare-Provider-Fraud-Detection
## Project Overview
The HealthCare Provider Fraud Detection project aims to build a machine learning model to detect fraudulent healthcare providers using various features from healthcare claims data. By identifying fraudulent providers, the project can help reduce financial losses and improve the quality of healthcare services.

This repository contains the full project workflow, including data exploration, feature engineering, modeling, evaluation, and deployment. It demonstrates the process of detecting fraud in healthcare claims data using a combination of data preprocessing, machine learning models, and performance evaluation.

## Table of Contents
- [Project Overview](#project-overview)
- [Team Members](#team-members)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
## Team Members
- Nour Mohamed:Data Exploration & Feature Engineering
- Jana Hendy: Model Building 
- Zeina Beshbeshy:Evaluation
- Hams Dewedar: Reporting and Documentation

## Repository Structure
The project repository is structured as follows:
fraud_detection_project/
│
├── data/ # Dataset storage (with download instructions if needed)
│
├── notebooks/ # Jupyter notebooks for each phase
│ ├── 01_data_exploration_and_feature_engineering.ipynb
│ ├── 02_modeling.ipynb
│ └── 03_evaluation.ipynb
│
├── reports/ # Final reports and presentation files
│ ├── technical_report.pdf # Detailed project report
│ └── presentation.pptx # PowerPoint presentation for the project
│
└── README.md # Project overview and instructions
## Installation
To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/janahendy30/HealthCare-Provider-Fraud-Detection.git
   cd HealthCare-Provider-Fraud-Detection
Install the required dependencies:

pip install -r requirements.txt
## Usage
Data Exploration and Feature Engineering:

The first notebook (01_data_exploration_and_feature_engineering.ipynb) explores the dataset and performs necessary feature engineering steps to prepare the data for modeling.

Modeling:

The second notebook (modeling.ipynb) includes the process of training machine learning models, evaluating different algorithms, and tuning hyperparameters for fraud detection.

Evaluation:

The third notebook (Evaluation.ipynb) evaluates the models, comparing metrics like precision, recall, F1 score, and AUC to assess their performance.

Report and Presentation:

The final report (Technical Report.pdf) summarizes the project, methodology, results, and conclusions.

The PowerPoint presentation (presentation.pptx) provides a brief overview of the project for presentation.

## Data
The dataset used in this project consists of healthcare provider claims data, including information about claim amounts, the number of procedures, and whether the provider is fraudulent.

[Download dataset] - (Provide instructions or link to where the dataset can be accessed, if applicable)

Results

The models were evaluated based on various metrics, including:

Precision: Measures the accuracy of fraud predictions.

Recall: Measures the ability to detect fraud.

F1 Score: Balances precision and recall.

AUC (Area Under Curve): Measures the model’s ability to distinguish between fraud and non-fraud cases.

Key results:

Best Model: Random Forest Classifier

Best Precision: 0.54

Best Recall: 0.64

Best F1 Score: 0.59

Best ROC AUC: 0.92

For more detailed results, refer to the notebooks and the technical report.
