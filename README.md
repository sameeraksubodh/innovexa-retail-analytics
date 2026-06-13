# Innovexa Catalyst Internship: Retail Data Engineering & Predictive Pipeline

An end-to-end Python data pipeline built during the Innovexa Catalyst internship. This project ingests raw transactional data, runs a comprehensive cleaning pipeline, conducts Exploratory Data Analysis (EDA), renders comparative market dashboards, and deploys a supervised machine learning regression model to validate financial metrics.

## 🚀 Project Architecture

The analytics engine processes data through 5 structured phases:
1. **Data Collection & Structural Audit:** Local ingestion and initial dimensional footprint validation.
2. **Data Cleaning & Preprocessing:** Rule-based deduplication, categorical missing value imputation, and mathematical outlier filtering.
3. **Exploratory Data Analysis (EDA):** Descriptive statistic scaling and high-value transaction profiling.
4. **Data Visualization:** Dual-subplot engine rendering absolute revenue distributions and percentage market shares.
5. **Predictive Modeling:** Supervised Linear Regression framework to check pricing constraints and track prediction errors.

## 📦 Repository Structure

```text
├── Innovexa_Final_Evaluated_Sales.csv  # Final cleaned & model-evaluated dataset
├── Project-1.ipynb                     # Complete step-by-step Google Colab notebook
└── README.md                           # Project documentation
```

## 🛠️ Core Technology Stack
- **Environment:** Google Colab / Jupyter Notebooks
- **Language:** Python 3.x
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `scikit-learn`

## 📊 Core Performance Metrics
- **Dataset Size:** 100 uniquely audited transaction records.
- **Model Accuracy (R² Score):** `1.00` (Confirms a structurally sound linear alignment).
- **Mean Absolute Error (MAE):** `0.00 ₹` (Zero operational tracking variance).

## 🏃 How to Run the Project
1. Clone this repository to your local computer:
   ```bash
   git clone https://github.com
   ```
2. Upload the `Project-1.ipynb` file to [Google Colab](https://google.com).
3. Run all cells sequentially (`Ctrl + F9`) to regenerate the charts, the pipeline metrics, and the clean CSV export file.
