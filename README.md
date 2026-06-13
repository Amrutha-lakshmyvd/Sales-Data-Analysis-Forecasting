# 🛒 Sales Data Analysis and Forecasting

> **Techie Interns Data Science Internship — Task 1**

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow?style=flat-square&logo=jupyter)

---

## 📌 Project Overview

End-to-end sales data analysis using a Superstore-style dataset — from data cleaning to machine learning forecasting — delivering actionable business insights across regions, categories, and time periods.

---

## 🗂️ Repository Structure

```
Sales-Data-Analysis-Forecasting/
│
├── Sales_Data_Analysis_Forecasting.ipynb   # Main Jupyter Notebook (fully executed)
├── cleaned_sales_data.csv                  # Cleaned dataset (1,000 rows, 18 columns)
├── Sales_Analysis_Report.pdf               # Exported PDF report
└── README.md                               # This file
```

---

## 🔧 Tech Stack

| Library | Purpose |
|---------|---------|
| Python 3.10 | Core language |
| Pandas | Data manipulation & cleaning |
| NumPy | Numerical operations & feature engineering |
| Matplotlib | Custom dark-themed visualizations |
| Seaborn | Statistical heatmaps |
| Scikit-learn | Linear Regression + cross-validation |
| Jupyter Notebook | Interactive development environment |
| Git | Version control |

---

## 📋 Dataset

- **Source:** Superstore Sales Dataset (Kaggle-schema compatible)
- **Records:** 1,000 sales orders
- **Timeframe:** January 2021 – December 2023
- **Columns:** 18 (after feature engineering)
- **Missing values after cleaning:** 0

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/Amrutha-lakshmyvd/Sales-Data-Analysis-Forecasting.git
cd Sales-Data-Analysis-Forecasting

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Launch notebook
jupyter notebook Sales_Data_Analysis_Forecasting.ipynb
```

---

## 📊 Key Results (Actual Outputs)

| Metric | Value |
|--------|-------|
| Total Sales | ₹1,49,282.05 |
| Total Profit | ₹19,656.00 |
| Total Orders | 1,000 |
| Avg Order Value | ₹153.90 |
| Top Region | West (₹40,343.98) |
| Top Category | Technology (₹79,969.00) |

### Model Performance

| Metric | Value |
|--------|-------|
| R² (Full Data) | 0.5101 |
| CV R² Mean (5-Fold) | 0.2745 ± 0.2492 |
| RMSE (Full Data) | ₹677.32 |
| CV RMSE (Mean) | ₹759.37 |

> Note: Moderate R² is expected given the high natural variability in monthly sales. The model captures trend and seasonality reliably for forecasting purposes.

### 6-Month Forecast (Jan–Jun 2024)

| Month | Forecasted Sales |
|-------|-----------------|
| Jan 2024 | ₹4,381.79 |
| Feb 2024 | ₹4,308.63 |
| Mar 2024 | ₹4,192.72 |
| Apr 2024 | ₹4,065.15 |
| May 2024 | ₹3,960.13 |
| Jun 2024 | ₹3,905.83 |

---

## 💡 Key Business Insights

1. **Technology leads** — ₹79,969 in sales (53.5% of total revenue)
2. **West region dominates** — ₹40,343.98, highest of all 4 regions
3. **Discount danger** — Discounts >30% consistently produce negative profit
4. **Q4 seasonality** — Year-end months show the highest quarterly sales
5. **Growth regions** — South (₹34,917) and Central (₹37,986) are underperforming; targeted campaigns recommended

---

## 📦 Deliverables

- [x] Jupyter Notebook with code + markdown explanations
- [x] Cleaned dataset (`cleaned_sales_data.csv`)
- [x] 6 visualizations (dark-themed, saved as PNG in notebook)
- [x] Linear Regression forecasting model with cross-validation
- [x] Business insights summary
- [x] PDF report (`Sales_Analysis_Report.pdf`)
- [x] README with actual results (not estimates)

---



## Demo Video

https://drive.google.com/file/d/1YEX8pQEBiXpRkF68mdWLEQdoGVsni5y_/view?usp=sharing


---

## 👩‍💻 Author

**Amrutha**    
Techie Interns — Data Science Internship

