# Parkinson Detection

This repository contains a machine learning project aimed at detecting Parkinson's Disease using classification models. The project uses a dataset from [Kaggle]

## Introduction
Parkinson's Disease is a neurological disorder that impacts movement. Early detection is key to managing symptoms. This project leverages biomedical voice measurements to predict whether a patient has Parkinson's Disease.

## Dataset
The dataset consists of 22 biomedical voice measurements including:
- **MDVP: Fo(Hz)** – Average vocal fundamental frequency
- **MDVP: Jitter(%)** – Variation in frequency
- **MDVP: Shimmer** – Variation in amplitude
- **NHR** and **HNR** – Noise-to-harmonics ratio and harmonics-to-noise ratio
- **Status** – 0 indicates a healthy person, 1 indicates a Parkinson's patient

The dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/parkinsons).

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Models
Several machine learning algorithms were used:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
