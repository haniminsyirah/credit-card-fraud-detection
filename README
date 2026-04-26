
# Credit Card Fraud Detection: Predictive Modeling

## 📌 Project Overview
This project focuses on identifying fraudulent credit card transactions using a dataset of European cardholders. The primary challenge was the extreme class imbalance, where frauds accounted for only **0.172%** of the total 284,807 transactions.

## 🚀 Key Objectives
* **Handle Imbalanced Data:** Managed highly skewed classes (492 frauds vs. 284,315 legitimate).
* **Feature Engineering:** Utilized PCA-transformed features (V1-V28) and scaled transaction time and amount.
* **Advanced Modeling:** Implemented **LightGBM**, **CatBoost**, and **Random Forest** algorithms.
* **Precision-Recall Optimization:** Focused on maximizing AUC and Recall to catch fraud while minimizing false positives.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** LightGBM, CatBoost, Scikit-learn, Pandas, Matplotlib, Seaborn
- **Environment:** Google Colab

## 📊 Quantitative Results
* **Top Model:** LightGBM reached peak performance at **Round 85**.
* **AUC Score:** Achieved an **AUC of ~0.974**, showing excellent model separation.
* **Key Drivers:** Feature importance analysis identified **V17, V14, and V12** as the most significant predictors of fraudulent activity.

## 💡 Business Insights
- **Fraud Patterns:** Fraudulent transactions often occur in specific "time clusters" and involve distinct patterns in the PCA-transformed variables.
- **Model Stability:** By using early stopping and class weights, the model successfully avoids overfitting to the majority class (legitimate transactions).

## 📂 Repository Structure
- `notebooks/`: Contains the Google Colab `.ipynb` file.
- `images/`: Visualizations including Confusion Matrix and Feature Importance plots.
