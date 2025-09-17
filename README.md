# Telco Customer Churn – Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset.  
The goal is to understand how different customer attributes relate to churn behavior.

---

## 📂 Dataset
The dataset used is **Telco-Customer-Churn.csv**, which contains information about customer demographics, services subscribed, billing, and churn status.

- **Target Variable**: `Churn` (Yes / No)  
- **Categorical Features**: Gender, Partner, Dependents, InternetService, Contract, PaymentMethod, etc.  
- **Numerical Features**: Tenure, MonthlyCharges, TotalCharges, SeniorCitizen.  

---

## ⚙️ Requirements
Install dependencies before running the scripts:

```bash
pip install pandas numpy matplotlib seaborn

# Exploratory Data Analysis (EDA) – Telco Customer Churn

---

## 📊 EDA Steps

### 1. Calculate Means/Percentages (No Plots)

**Script**: `eda_calculations.py`

- Calculates **percentage churn** across categorical features.  
- Calculates **mean values** of numerical features grouped by churn.  
# Exploratory Data Analysis (EDA) – Telco Customer Churn

---

## 📊 EDA Steps

### 1. Calculate Means/Percentages (No Plots)

**Script**: `eda_calculations.py`

- Calculates **percentage churn** across categorical features.  
- Calculates **mean values** of numerical features grouped by churn.  

#### Example Output
=== Numerical Feature Means by Churn ===
Churn SeniorCitizen tenure MonthlyCharges TotalCharges
No 0.16 37.6 61.3 2555.3
Yes 0.28 17.9 74.4 1531.8



---

### 2. Statistical Graphics (Optional)

**Script**: `eda_visuals.py`  
Creates the following plots:

- 📊 Bar plots for categorical features vs churn  
- 📦 Boxplots & 📈 Histograms for numerical features  
- 🔥 Correlation Heatmap for numerical features  

---

## 🚀 How to Run

1. Open in **Google Colab** or run locally.  
2. Place **Telco-Customer-Churn.csv** in the same directory as the scripts.  
3. Run the Python files:

```bash
python eda_calculations.py   # For summary tables
python eda_visuals.py        # For plots