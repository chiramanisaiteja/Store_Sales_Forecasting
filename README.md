# 🏪 Store Sales Forecasting using Machine Learning & Tableau

## 📌 Project Overview

This project analyzes historical retail sales data to identify sales trends, evaluate business performance, and forecast future sales using Machine Learning.

The project combines Python for data preprocessing and predictive modeling with Tableau for interactive business intelligence dashboards.

---

## 🎯 Business Problem

Retail businesses need accurate sales forecasts to optimize inventory, staffing, promotions, and operational planning.

The objective of this project is to:

- Analyze historical sales trends
- Identify high-performing stores and product families
- Measure the impact of promotions and holidays
- Forecast future sales using XGBoost
- Present insights through interactive Tableau dashboards

---

# 📂 Dataset

The project combines six datasets:

- Train Sales Data
- Test Sales Data
- Store Information
- Transactions
- Oil Prices
- Holidays & Events

After merging all datasets:

- **Rows:** 3,000,888
- **Columns:** 18

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Tableau Desktop
- Google Colab
- Git & GitHub

---

# 🔄 Project Workflow

```
Data Cleaning
        ↓
Data Merging
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Machine Learning (XGBoost)
        ↓
Model Evaluation
        ↓
Business Intelligence Dashboard (Tableau)
```

---

# 📊 Exploratory Data Analysis

Key findings include:

- Sales increased steadily over time.
- Grocery and Beverage categories generated the highest revenue.
- Stores 44, 45, and 47 achieved the highest sales.
- Promotions significantly increased average sales.
- Holiday/Event days showed higher average sales.
- Higher transaction volume was associated with higher sales.

---

# 🤖 Machine Learning Model

The final forecasting model was built using **XGBoost**.

Due to Google Colab memory limitations, the model was trained using:

- Training Rows: **150,000**
- Testing Rows: **50,000**

---

# 📈 Model Performance

| Metric | Score |
|---------|-------|
| MAE | **59.35** |
| RMSE | **217.75** |
| R² Score | **0.9732** |

The model explains approximately **97.3%** of the variance in sales, demonstrating excellent predictive performance.

---

# 📊 Tableau Dashboards

The project contains two interactive dashboards.

## Dashboard 1 – Executive Overview
<img width="1873" height="1004" alt="Dashboard_1 png" src="https://github.com/user-attachments/assets/72087f8a-53a3-406a-ab4f-5d8f49755aa9" />

Features:

- Total Sales KPI
- Total Transactions KPI
- Average Sales KPI
- Total Promotions KPI
- Daily Sales Trend
- Monthly Sales Trend
- Top 10 Stores
- Top Product Families

---

## Dashboard 2 – Business Insights
<img width="1902" height="1025" alt="Dashboard_2 png" src="https://github.com/user-attachments/assets/19676a1d-9652-4f33-9488-7fa14a76c82b" />

Features:

- Promotion Impact
- Holiday Impact
- Sales by State
- Sales by Store Type

---

# 📁 Project Structure

```
Store_Sales_Forecasting/

│
├── Data/
│   ├── Raw/
│   └── Processed/
│
├── Images/
│   ├── Dashboard_1.png
│   ├── Dashboard_2.png
│   ├── Model_Evaluation/
│   └── EDA/
│
├── Models/
│   └── xgboost_sales_forecasting_light.pkl
│
├── Notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_Data_Merging.ipynb
│   ├── 03_EDA.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Model_Training.ipynb
│   ├── 06_Model_Evaluation.ipynb
│   └── 07_Project_Summary.ipynb
│
├── Tableau/
│   └── Store_Sales_Forecasting.twbx
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Store_Sales_Forecasting.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebooks in numerical order.

4. Open the Tableau workbook to explore the dashboards.

---

# 🔮 Future Improvements

- Deploy the forecasting model as a web application.
- Add real-time forecasting.
- Integrate weather and economic indicators.
- Compare additional machine learning models.
- Add interactive dashboard filters and drill-down features.

---

# 👤 Author

**Chiramani Saiteja**

MSc Data Science & Business Analysis

EDC Paris Business School

GitHub: https://github.com/chiramanisaiteja

---

## ⭐ If you found this project useful, consider giving it a star!
