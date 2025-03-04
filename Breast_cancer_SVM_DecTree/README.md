# Breast Cancer Classification

This project was developed for the professional practice of Data Science at the Instituto Superior Politecnico de Cordoba, in 2022.

## Objective
The goal is to develop a classification model to predict breast cancer diagnoses based on clinical data.

Two machine learning models are implemented and compared:
- **SVM with radial kernel** (SVM Radial).
- **Decision Tree**.

Results show that the SVM model with a radial kernel performs better.

All project annotations are in Spanish.

## About the Dataset
The dataset used is the **Breast Cancer Wisconsin Diagnostic Dataset**, provided by `sklearn.datasets`. It contains information on 569 breast tumors, each characterized by 30 attributes derived from biopsy images.

The target labels (`target`) indicate whether the tumor is **malignant (1)** or **benign (0)**.

## Requirements and Execution
To run the project, the following Python libraries need to be installed:
```bash
pip install numpy pandas scikit-learn matplotlib
```
The code is available in a **Jupyter notebook**, where the data is explored and models are trained.

