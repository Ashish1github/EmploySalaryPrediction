# EmploySalaryPrediction
# Employee Salary Classification

This project predicts whether an employee earns more than $50K or not based on demographic and work-related features. It includes a web application built using Streamlit and a machine learning model trained on the UCI Adult Income dataset.

## Project Features

- Streamlit-based web interface
- Single prediction through form input
- Batch prediction via CSV upload
- Trained ML model using scikit-learn

## Dataset

The model is trained on the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult). The target variable is salary class: `<=50K` or `>50K`.

### Features Used:
- age
- workclass
- fnlwgt
- education-num
- marital-status
- occupation
- relationship
- race
- capital-gain
- capital-loss
- hours-per-week
- native-country
- gender
