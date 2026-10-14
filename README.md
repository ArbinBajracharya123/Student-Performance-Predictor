# Student-Performance-Predictor

## Overview

This project uses Machine Learning to predict a student's overall academic performance.

Students are classified into three performance categories:

- Low
- Medium
- High

The project explores how different student-related factors can be used to predict academic performance.

## What This Project Uses

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP
- Jupyter Notebook

## Machine Learning Approach

The project follows these main steps:

1. Load and explore the student dataset.
2. Preprocess the data and encode categorical features.
3. Create performance categories based on the final grade (G3).
4. Split the data into training and testing sets.
5. Train a **Random Forest Classifier**.
6. Use **GridSearchCV** to find better model parameters.
7. Evaluate the model using:
   - Accuracy
   - Classification Report
   - Confusion Matrix
   - 5-Fold Cross-Validation
8. Analyze feature importance and use **SHAP** to understand the model's predictions.

## Dataset

The dataset contains information about **649 students** and includes **33 original attributes** related to academic, personal, social, and demographic factors.

The final grade (**G3**) is used to determine the student's overall performance category.

## Project Workflow

```text
Student Dataset
      ↓
Data Preprocessing
      ↓
Feature Encoding
      ↓
Performance Classification
      ↓
Train/Test Split
      ↓
Random Forest Classifier
      ↓
Hyperparameter Tuning
      ↓
Model Evaluation
      ↓
Feature Importance & SHAP Analysis
```

## Project Structure

```text
Student-Performance-Predictor/
│
├── Student Performance Predictor.ipynb
├── StudentData.csv
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open `Student Performance Predictor.ipynb` in Jupyter Notebook or VS Code.
3. Install the required Python libraries if they are not already installed.
4. Run the notebook cells in order.

## Conclusion

This project demonstrates how Machine Learning can be applied to student data to predict academic performance. It also uses feature importance and SHAP analysis to provide better understanding of which factors influence the model's predictions.
