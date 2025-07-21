# Fraud Transaction Analysis (Power BI)

This project provides a complete fraud detection analysis using Power BI, focused on identifying and visualizing suspicious credit card transactions. It combines machine learning insights with clear, interactive visuals for business understanding.

---

## Project Overview

The goal of this project is to analyze a dataset of financial transactions and identify fraudulent behavior using classification models. The results are presented in an interactive Power BI dashboard that allows users to explore trends, metrics, and anomalies.

### Features
- Data preprocessing and SMOTE balancing
- Model evaluation using Logistic Regression and Random Forest
- Dynamic visualizations of transaction patterns
- Filters for fraud class, transaction hour, and amount range

---

## Files Included

| File                          | Description                                 |
|------------------------------|---------------------------------------------|
| `Fraud_Analysis.pbix`        | Power BI dashboard file (available as `.zip`) |
| `fraud_dataset.csv`          | Cleaned dataset used in the dashboard       |
| `model_evaluation_summary.csv` | Model evaluation metrics (Precision, Recall, F1-Score) |
| `README.md`                  | Project documentation                       |

---

## Dashboard Download

Download the full Power BI dashboard from the link below:

**Releases Page**:  
[https://github.com/Darkrai-99/Fraud-Transaction-Analysis/releases](https://github.com/Darkrai-99/Fraud-Transaction-Analysis/releases)

Once downloaded, extract the `.zip` and open the `.pbix` file using Power BI Desktop.

---

## Dashboard Highlights

- **Key Metrics (KPI Cards)**: Total transactions, fraud count, fraud percentage
- **Trend by Hour**: Line chart showing transaction volume by hour and class
- **Amount Analysis**: Clustered column chart with average and median transaction amounts
- **Model Evaluation Table**: Precision, Recall, and F1-Score for each ML model
- **Filters**: Class (fraud vs. non-fraud), transaction hour, and amount range

---

## Technologies Used

- Power BI Desktop
- Python (for model building and preprocessing)
- Scikit-learn, Pandas, imbalanced-learn

---

## How to Use

1. Download the dashboard `.zip` file from the [Releases](https://github.com/Darkrai-99/Fraud-Transaction-Analysis/releases).
2. Extract the `.pbix` file.
3. Open in Power BI Desktop.
4. Explore visuals and interact with filters to analyze results.

---

## Author

Created by [Darkrai-99](https://github.com/Darkrai-99).  
For feedback or contributions, feel free to open an issue or pull request.

