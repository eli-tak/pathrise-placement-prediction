# pathrise-placement-prediction

A machine learning project that explores Pathrise fellow data and predicts whether a fellow gets placed in a job.

## Objective

Predict the `placed` outcome from fellow, cohort, and job-search information.

## Dataset

`Data_Pathrise.xlsx` contains fellow-level records with:

- Placement outcome (`placed`)
- Job-search activity (number of applications, interviews, length of job search, biggest challenge)
- Education and professional experience
- Program information (track, cohort, program duration, Pathrise status)
- Demographic attributes (gender, race, work authorization)

## Workflow

1. Environment setup and data loading
2. Exploratory data analysis and visualization
3. Outlier review and management
4. Feature engineering and transformation
5. Missing-value handling
6. Categorical encoding and data export
7. Classification modeling and hyperparameter search
8. Model evaluation and serialization
9. Supplementary regression analysis

## Models

Classification models compared:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Logistic Regression

Models are evaluated with ROC curves and AUC scores.

## Repository Contents

- `pathrise_analysis_fixed.ipynb`: main analysis notebook, with outputs included
- `Data_Pathrise.xlsx`: source dataset

## How to Run

1. Install the required packages:
```bash
   pip install pandas numpy seaborn matplotlib scikit-learn openpyxl jupyter
   


This project aims to explore factors associated with job placement for Pathrise fellows.

## Status

Project files have not been uploaded yet.
