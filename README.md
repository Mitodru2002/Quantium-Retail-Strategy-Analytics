# Quantium-Retail-Strategy-Analytics
Data analytics project focusing on customer segmentation, transaction behavior analysis, and uplift testing for a major retail category (Chips).

# Quantium Retail Strategy and Analytics - Web Internship

This project was completed as part of the Quantium Data Analytics Virtual Internship. It involves analyzing retail transaction data to provide strategic recommendations for the "Chips" category manager (Julia).

## 📋 Project Overview
The goal was to transform raw transaction and customer data into actionable insights to drive the supermarket's strategic plan for the next half year. The project is divided into three key tasks:

1. **Data Preparation and Customer Segmentation:** Cleaning data and identifying high-value customer segments.
2. **Experimentation and Uplift Testing:** Evaluating the impact of new store layouts using trial and control store comparisons.
3. **Strategic Reporting:** Presenting findings using the "Pyramid Principle."

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scipy (for T-Tests)
* **Environment:** Jupyter Notebook

## 🔍 Key Tasks & Findings

### Task 1: Data Cleaning & Segmentation
* **Cleaning:** Removed non-chip products (salsa/dips) and handled commercial outliers (e.g., Customer 226000).
* **Feature Engineering:** Extracted `Pack Size` and `Brand` from product descriptions.
* **Insights:** * **Mainstream Young Singles/Couples** and **Mainstream Retirees** are the largest customer segments.
    * **Mainstream Young Singles/Couples** are the most profitable, showing the highest average spend per unit.

### Task 2: Experimentation & Uplift Testing
* **Methodology:** Selected Control Stores for Trial Stores 77, 86, and 88 based on Pearson Correlation and Magnitude Distance.
* **Analysis:** Scaled control store sales to trial store levels for the pre-trial period (July 2018 - Jan 2019).
* **Results:** * Trial Stores 77 and 86 saw statistically significant sales increases during the trial period.
    * The growth was primarily driven by **increased customer footfall**, proving the success of the new layout.

### Task 3: Strategic Recommendation
* Recommended a full rollout of the new layout to urban stores with high concentrations of "Mainstream" segments.
* Suggested prioritizing premium brands (Kettle, Tyrrells) in 175g formats based on affinity analysis.

## 📁 Repository Structure
* `/data`: Contains links/placeholders for the raw datasets (`QVI_transaction_data` and `QVI_purchase_behaviour`).
* `/notebooks`: Jupyter Notebooks containing the Python analysis code.
* `/visualizations`: PNG exports of key charts (Sales by Segment, Trial Uplift).
* `Final_Report.pdf`: The strategic presentation submitted to the client.

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have the `cleaned_merged_data.csv` or raw CSVs in the root directory.
3. Run the Jupyter Notebooks in order: `Task_1_Analysis.ipynb` followed by `Task_2_Trial_Analysis.ipynb`.
