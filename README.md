
# 📊 Customer Churn Analysis Dashboard

This project presents an interactive dashboard built using **Tableau** to analyze and visualize **customer churn** patterns for a telecom company. The analysis leverages a cleaned dataset and highlights the factors influencing customer retention and attrition.

---

## 🔍 Project Objective

The goal of this project is to understand the underlying reasons for customer churn and identify high-risk customer segments using demographic, service, and financial features. Insights from this analysis can help businesses design more effective retention strategies.

---

## 🧰 Tools Used

- 🐍 **Python (Pandas)** – for data cleaning and preprocessing
- 📈 **Tableau Public** – for dashboard creation and visualization
- 📁 **CSV File** – input and output data format
- 💡 **Kaggle Dataset** – [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 📁 Folder Structure

```
Customer_Churn_Analysis/
├── Telco-Customer-Churn
├── Telco_Customer_Churn_Cleaned
├── clean_data.py
├── Customer Churn Dashboard.twb
├── README.md
```

---

## 🧹 Data Cleaning (Python)

Before building the dashboard, the raw data was cleaned using a Python script:

- Converted `TotalCharges` to numeric
- Handled missing values
- Mapped binary responses (Yes/No) to 1/0
- Standardized categorical fields for Tableau compatibility

```bash
# To run the cleaning script
python scripts/clean_data.py
```

Cleaned data is saved as:  
`data/Telco_Customer_Churn_Cleaned.csv`

---

## 📊 Tableau Dashboard Features

The dashboard contains multiple views:

### 1. **KPI Summary**
- Total Customers
- Churned Customers
- Churn Rate (%)

### 2. **Demographics Breakdown**
- Churn by Gender, Senior Citizenship, and Partner/Dependent Status

### 3. **Financial Analysis**
- Monthly Charges vs. Churn (Box plot)
- Tenure Distribution of Churned vs. Retained

### 4. **Service Usage Impact**
- Churn by Internet Service Type
- Streaming Services and Tech Support Impact

### 5. **Contract & Billing**
- Churn by Contract Length
- Impact of Electronic Payment Methods

📌 All views include interactive filters for Contract Type, Internet Service, and more.

---

## 🖼️ Dashboard Preview

*(Add screenshots here)*  
![Dashboard Preview](images/dashboard_overview.png)

---

## 🚀 How to Use

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/customer-churn-analysis.git
   ```

2. Run the cleaning script (optional):
   ```bash
   python scripts/clean_data.py
   ```

3. Open Tableau Public or Tableau Desktop

4. Load the cleaned CSV: `data/Telco_Customer_Churn_Cleaned.csv`

5. Explore or publish the dashboard

---

## 📈 Live Tableau Dashboard

🔗 **[View on Tableau Public](https://public.tableau.com/app/profile/rakhesh.varshan.dhamodaran/viz/CustomerChurnDashboard_17494973611620/Dashboard1)**  

---

## 💬 Key Insights

- **Month-to-month contracts** have significantly higher churn rates than longer-term contracts.
- Customers using **Electronic Check** as payment method are more likely to churn.
- **Short tenure** and **higher monthly charges** are strong churn indicators.
- Providing **tech support** and **online security services** helps reduce churn.

---

## 📌 Future Improvements

- Integrate predictive churn score based on weighted factors.
- Link Tableau dashboard to a live data source (e.g., Google Sheets or a database).
- Add story points for guided walkthrough of findings.

---

## 🙋‍♂️ Author

**Rakhesh Varshan Dhamodaran**  
📫 [LinkedIn](https://www.linkedin.com/in/rvd7203/)  
🌐 [Portfolio](https://rakhesh.notion.site/)
