# Insurance Purchase Prediction Project

This repository contains a machine learning pipeline to predict whether customers will purchase health insurance, based on their age and estimated salary. The project demonstrates a comparative analysis of multiple classification algorithms, including:

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Decision Trees
- Random Forest

## 📂 Files

- `insurance_data.csv`: Synthetic dataset of 400 customers with Age, EstimatedSalary, and Purchased columns  
- `insurance_model.ipynb`: Jupyter notebook with full code, data exploration, model training, evaluation, and prediction

## 📊 Overview

The aim of this project is to help insurance businesses predict customer purchasing behavior. The models were trained to classify customers based on two key attributes, balancing accuracy and generalization.

## 🚀 How to Run

1. Clone or download this repository  
2. Install requirements (if using locally):  
   ```bash
   pip install pandas numpy scikit-learn seaborn matplotlib
Open the notebook insurance_model.ipynb in Jupyter or Colab

Run all cells to reproduce the results

🔬 Results
Random Forest achieved the best accuracy and ROC-AUC, making it the recommended model for deployment. Visualizations, confusion matrices, and test scenario predictions are included in the notebook.

📈 Business Impact
This project shows how simple demographic features like age and salary can powerfully predict customer behavior in insurance. It supports data-driven decision-making for targeted marketing or risk assessment.
