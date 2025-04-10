# 📊 Telco Customer Churn Analysis

This project is a detailed exploratory data analysis (EDA) of a telecom customer dataset to understand why customers are leaving (churning). The goal is to identify key patterns and features associated with customer churn and provide business insights to improve customer retention.

---

## 🔍 Project Overview

Customer churn is a major problem in the telecom industry, and reducing churn is crucial for maintaining profitability. This project dives into the Telco dataset, performs cleaning, analysis, and visualization to understand:
- What percentage of customers are churning?
- Which factors influence churn the most?
- How can the company take data-driven actions?

---

## 🛠️ Tech Stack

| Purpose               | Tools & Libraries                            |
|-----------------------|----------------------------------------------|
| Programming Language  | Python                                       |
| Data Manipulation     | Pandas, NumPy                                |
| Data Visualization    | Matplotlib, Seaborn                          |
| Notebook Environment  | Jupyter Notebook                             |

---

## 📈 EDA Highlights

- Cleaned the dataset (handled missing values in `TotalCharges` and `tenure`).
- Converted numerical flags (e.g., `SeniorCitizen`) to categorical for better readability.
- Found that **26.54%** of customers have churned.
- Identified that **senior citizens** and certain contract types are more prone to churn.
- Visualized trends with bar plots, pie charts, and correlation heatmaps.

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
git clone https://github.com/your-username/telco-customer-churn-analysis.git
cd telco-customer-churn-analysis
Install dependencies
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn jupyter
Launch the notebook

bash
Copy
Edit
jupyter notebook
Then open Telco Customer Churn Analysis.ipynb.
