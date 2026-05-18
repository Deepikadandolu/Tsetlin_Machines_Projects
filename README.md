# Diabetes Classification using Tsetlin Machines

## Project Overview

This project implements a multiclass diabetes classification system using a Tsetlin Machine.  
The model predicts whether a person is:

- Non-Diabetic
- Prediabetic
- Diabetic

using health-related indicators from the Diabetes Health Indicators Dataset.

The project demonstrates the use of logical machine learning with Tsetlin Machines for interpretable healthcare prediction.

---

## Dataset

Dataset Source:  
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data

Target Variable:
- `Diabetes_012`

Class Labels:
- `0` → Non-Diabetic
- `1` → Prediabetic
- `2` → Diabetic

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- pyTsetlinMachine

---

## Project Workflow

1. Load dataset
2. Perform data inspection
3. Clean dataset
4. Exploratory Data Analysis (EDA)
5. Split features and labels
6. Train-test split
7. Feature binarization using KBinsDiscretizer
8. Train Multiclass Tsetlin Machine
9. Evaluate model performance
10. Visualize results

---

## Model Used

Multiclass Tsetlin Machine

Parameters:
- Number of Clauses: 500
- T Value: 300
- s Value: 3.0
- Epochs: 10

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Results

The model is trained over multiple epochs and evaluated using classification metrics and accuracy plots.

---

## Advantages of Tsetlin Machines

- Explainable AI
- Rule-based learning
- Logical clause interpretation
- Lower memory requirements compared to large neural networks

---

## Future Improvements

- Hyperparameter tuning
- Feature engineering
- Class balancing
- Comparison with traditional ML models
- Clause interpretation and explainability analysis

---

## Author

Deepika Reddy
