# Supervised Learning Assignment – Titanic

This repository contains my project for the Supervised Learning assignment.

## 📌 Project Details
- **Dataset:** Titanic (Kaggle)  
- **Task:** Binary classification – predict survival (0 = did not survive, 1 = survived).  
- **Metric:** F1-Score on the positive class (survived).  

## 📊 Workflow
1. **Introduction**
   - Problem definition, dataset, quality metric.
2. **EDA (Exploratory Data Analysis)**
   - Data exploration and visualization (correlation heatmap, survival by sex, age distribution).
3. **Feature Engineering**
   - Processed Cabin, Age, created Family feature, applied One-Hot Encoding, scaling.
4. **Model Training**
   - Compared KNN, Decision Tree, Gradient Boosting.
   - Used Grid Search with 5-Fold Cross Validation.
5. **Results**
   - Best model: Gradient Boosting (with tuned hyperparameters).
   - Evaluated on test set (F1, Confusion Matrix, ROC curve).
6. **Insights**
   - Sex, Pclass, and Age were the most important features affecting survival.

## 🛠 Tools
- Python 3  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<username>/supervised-learning-assignment.git
   cd supervised-learning-assignment
