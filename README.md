# CEO Compensation & Company Performance Analysis

## 📌 Overview
This project analyzes CEO compensation in relation to various company performance metrics. Using a dataset of **367 companies**, we investigate:
- **What financial and market factors influence CEO pay?**
- **Can we predict CEO total compensation using financial indicators?**
- **How does debt structure relate to executive compensation?**

This project was developed for **B DATA 200** by **Anushna Gunda, Inaya Rizvi, Harsh Malik, and Sai Bathina**.

---

## 📊 Dataset
The dataset (`ceo_comp_data.csv`) was sourced from **Pitchbook** and includes:
- **Dependent Variable:** `CEO Total Compensation` (in millions)
- **Independent Variables:**
  - **Financial Metrics:** `Total Revenue`, `EBITDA Margin`, `ROIC`
  - **Market Performance:** `Stock Price`, `Price % Change YTD`
  - **Debt & Leverage:** `Net Debt`, `Debt to Capital`
  - **Company Information:** `Industry Group`, `HQ State/Province`

---

## ⚙️ Methodology
### **1️⃣ Data Preprocessing**
- **Handled missing values** (median imputation for numeric variables, mode for categorical).
- **Converted negative values formatted as `(x.xx)` to `-x.xx`**.
- **Renamed columns** for consistency (`_` instead of spaces).

### **2️⃣ Exploratory Data Analysis (EDA)**
- **Summary statistics** for CEO pay and financial variables.
- **Visualizations** (correlation heatmaps, scatter plots, box plots by industry).

### **3️⃣ Regression Analysis**
- **Multiple Linear Regression** to assess which variables significantly predict CEO compensation.
- **Stepwise Regression** to refine the model and remove weak predictors.

### **4️⃣ Clustering (Optional)**
- **K-Means Clustering** to group companies based on debt, profitability, and compensation patterns.

---

## 🚀 How to Run the Analysis
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/YOUR-USERNAME/ceo-compensation-analysis.git
cd ceo-compensation-analysis
