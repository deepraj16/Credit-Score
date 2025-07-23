#  German Credit Risk Classification

This project uses the **German Credit dataset** to build a machine learning model that classifies individuals as **good** or **bad** credit risks based on personal and financial attributes. The aim is to assist financial institutions in making informed decisions.

##  Dataset Description

- Source: UCI Machine Learning Repository
- Rows: 1000 samples
- Features: 20 (categorical + numerical)
- Target: `Credit Risk`

## 🛠 Tech Stack

- Language: Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, XGBoost (optional)
- ML Models: Logistic Regression, Decision Tree, Random Forest, XGBoost, etc.

---


---

## Steps Covered

1. **Exploratory Data Analysis (EDA)**
   - Missing values, class distribution, feature correlation
2. **Data Preprocessing**
   - Label encoding, one-hot encoding
   - Scaling (StandardScaler or MinMaxScaler)
3. **Model Training**
   - Logistic Regression, Decision Tree, Random Forest, XGBoost
   - Cross-validation and hyperparameter tuning (GridSearchCV)
4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix and ROC curve
5. **Model Comparison & Selection**
6. **Feature Importance Visualization**

---

## Example Results

- **Best Model:** Random Forest and XGBoost
- **Accuracy:** ~90%
- **F1-Score:** 0.85 (varies)

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/german-credit-risk.git
cd german-credit-risk
pip install -r requirements.txt

