

# 📊 Credit Risk Modeling with Logistic Regression

## 📌 Overview

This project focuses on building a **credit risk prediction model** to identify the likelihood of loan default using historical borrower data. The goal is to support better lending decisions by highlighting key risk drivers and predicting default probabilities.

Credit risk modeling is a critical function in banking and financial institutions, helping to minimize losses and improve portfolio quality.

---

## 📂 Project Structure

```
credit-risk-model/
│
├── data/
│   └── credit_risk_dataset.csv
│
├── notebooks/
│   └── credit_risk_model_analysis.ipynb
│
├── images/
│   └── (visualizations)
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 📊 Dataset Description

The dataset contains borrower-level information used to assess creditworthiness.

### Key Features:

* **Income** – Borrower’s income level
* **Loan Amount** – Amount requested or issued
* **Credit History** – Past repayment behavior
* **Employment Status** – Job stability indicator
* **Default (Target Variable)** – Whether the borrower defaulted (1) or not (0)

---

## ⚙️ Methodology

### 1. Data Cleaning

* Handled missing values
* Removed duplicates
* Standardized data formats

### 2. Exploratory Data Analysis (EDA)

* Distribution of key variables
* Relationship between features and default
* Identification of risk patterns

### 3. Feature Engineering

* Created meaningful variables (e.g., loan-to-income ratio)
* Encoded categorical variables

### 4. Model Building

* Used **Logistic Regression** for binary classification
* Split data into training and testing sets

### 5. Model Evaluation

* Accuracy
* Precision & Recall
* Confusion Matrix

---

## 📈 Results & Insights

Key findings from the model:

* Borrowers with **higher loan-to-income ratios** show increased default risk
* **Higher income levels** generally reduce default probability
* Credit history is a strong predictor of repayment behavior

The model provides a simple but effective baseline for credit risk assessment.

---

## 📊 Visualizations

The project includes visual insights such as:

* Default rate by income
* Loan amount vs default
* Correlation heatmap

(See `/images` folder)

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/ElkanemiProf/credit-risk-model.git
```

2. Navigate into the project:

```bash
cd credit-risk-model
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open:

```
notebooks/credit_risk_model_analysis.ipynb
```

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🎯 Business Impact

This model can help financial institutions:

* Improve **loan approval decisions**
* Reduce **default rates**
* Identify **high-risk customers early**
* Support **data-driven lending strategies**

---

## 📌 Future Improvements

* Implement advanced models (Random Forest, XGBoost)
* Add ROC-AUC evaluation
* Deploy as an API or web app
* Integrate real-time scoring

---

## 👤 Author

**Kenneth Okoye**
Fraud Analyst | Aspiring Credit Risk Analyst | Data Enthusiast


