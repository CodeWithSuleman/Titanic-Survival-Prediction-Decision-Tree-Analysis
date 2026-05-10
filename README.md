# Titanic Survival Prediction: Decision Tree Analysis

This repository contains a comprehensive Machine Learning project focused on predicting passenger survival on the Titanic using a **Decision Tree Classifier**. The project covers the entire pipeline from data preprocessing to model optimization and real-time prediction.

## 🚀 Project Overview
The objective is to analyze the Titanic dataset and build a model that predicts whether a passenger survived based on features like Age, Sex, Class, and Fare. This project was developed as part of the **Advance Statistics Lab** at SMIU.

## 📊 Key Features
- **Data Preprocessing:** Handled missing values (Median Imputation) and encoded categorical variables.
- **Hyperparameter Tuning:** Optimized the Decision Tree using `max_depth` and `min_samples_split` to prevent overfitting.
- **Visual Interpretation:** Includes a graphical representation of the decision paths.
- **Predictive System:** A functional Python script to simulate survival for custom passenger data.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** - `Pandas` (Data manipulation)
  - `NumPy` (Numerical computing)
  - `Scikit-learn` (Machine Learning)
  - `Matplotlib` & `Seaborn` (Visualization)

## 📁 Dataset
The project uses the `Titanic-Dataset.csv`, which includes:
- **Survived:** 0 = No, 1 = Yes (Target)
- **Pclass:** Ticket class (1, 2, 3)
- **Sex:** Gender
- **Age:** Age in years
- **SibSp / Parch:** Family relations
- **Fare:** Passenger fare
- **Embarked:** Port of embarkation

## 📈 Model Performance
- **Accuracy:** ~79.89% (Base Model) -> Enhanced with Tuning.
- **Criterion:** Entropy (Information Gain).
- **Strategy:** 80% Training, 20% Testing.

## 💻 How to Use
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/titanic-decision-tree.git](https://github.com/your-username/titanic-decision-tree.git)
