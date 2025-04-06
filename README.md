# Fraud Detection with Machine Learning 🕵️‍♂️💳

This project aims to build a machine learning pipeline to detect fraudulent transactions using structured customer and store-level data.

## 📊 Project Overview

Fraudulent activities can lead to significant financial loss. Using classification models, this project predicts whether a transaction is fraudulent based on key features such as:

- Transaction amount
- Customer age
- Store location
- Country

## 🧰 Tools & Technologies

- Python  
- Pandas & NumPy  
- Scikit-learn  
- OneHotEncoder  
- StandardScaler  
- Train/Test Split  
- Matplotlib & Seaborn (for EDA)

## 📌 Workflow

1. **Data Cleaning & Preprocessing**
   - Removed missing values
   - Excluded entries with 'Unknown' country
   - Applied One-Hot Encoding to categorical features
   - Scaled numerical features

2. **Feature Engineering**
   - Selected relevant features: `amount`, `age`, `store`, `country`
   - Target variable: `fraud`

3. **Modeling**
   - Applied classification algorithms such as Logistic Regression and Random Forest
   - Evaluated using accuracy and ROC-AUC

## 📈 Results

- Explored the distribution of fraudulent vs. non-fraudulent cases
- Identified data imbalance
- Achieved good performance with ensemble methods

## 📁 Files

- `FP_Project.ipynb`: Complete Jupyter Notebook with preprocessing, modeling, and evaluation

---

## 🚀 Future Improvements

- Implement SMOTE or other resampling methods to better handle class imbalance
- Deploy the model with a real-time inference API (e.g., using Flask)
- Add SHAP or LIME for model interpretability

## 📬 Contact

For questions or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/auhood-aljailani/)
