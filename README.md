#  Iris Flower Classification

This project applies machine learning techniques to classify iris flowers into one of three species: **Setosa**, **Versicolor**, or **Virginica** based on their petal and sepal dimensions.

## 📊 Dataset Overview

- The dataset contains **150 samples** with:
- 4 features: `sepal length`, `sepal width`, `petal length`, `petal width`
- 3 classes: `Iris-setosa`, `Iris-versicolor`, `Iris-virginica`
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

##  Exploratory Data Analysis

- Visualized feature distributions using histograms and box plots
- Analyzed pairwise relationships with seaborn's `pairplot`
- Plotted class distribution with a custom flower-themed count plot 🌸

## 🤖 Models Used

Multiple classifiers were trained and evaluated:

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | ✅ ~93%  |
| K-Nearest Neighbors    | ✅ ~97%   |
| Decision Tree          | ✅ ~91%   |
| Random Forest          | ✅ ~91%   |
| Support Vector Machine | ✅ ~95%   |

> Note: Accuracy may vary slightly depending on random state or split.

## 📈 Evaluation

- Models were evaluated using:
  - Accuracy
  - Classification Report (Precision, Recall, F1-score)
  - Confusion Matrix
- Visual decision boundaries were plotted for Logistic Regression

## 🧠 Key Insights

- **Petal length and width** are the most discriminative features
- K-Nearest Neighbors and SVM performed exceptionally well
- The dataset is clean and perfectly balanced

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/jmokhtarx/iris-flower-classification.git
