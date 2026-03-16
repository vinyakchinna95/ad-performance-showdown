# Ad-Performance-Showdown: Facebook vs. Google Ads Analysis

## 📌 Project Overview
This project focuses on a comparative **A/B Testing Analysis** between two major digital advertising platforms: **Facebook Ads** and **Google Ads (AdWords)**. The goal is to determine which platform provides better cost-efficiency and a higher Return on Investment (ROI) for a marketing agency managing multiple client campaigns.

## 🏢 Business Problem
A marketing agency recently launched simultaneous campaigns on both Facebook and Google. While both platforms generate impressions and clicks, the agency faces a "President's Problem": **Where should the limited budget be allocated for maximum impact?**

It is currently unclear which platform delivers better performance in terms of conversion outcomes versus the cost incurred. This analysis provides a data-driven answer to optimize budget allocation.

## 📊 Dataset Description
The analysis is performed on a structured dataset containing **1,000 observations** spanning from **2021 to 2024**.

### Key Raw Metrics:
* **Views:** Total impressions received.
* **Clicks:** Total number of users who clicked the ad.
* **Conversions:** Number of users who completed a desired action.
* **Total Ad Cost:** Amount spent on the campaign.

### Engineered Features:
* **Click-Through Rate (CTR):** `(Clicks / Views) * 100`
* **Conversion Rate:** `(Conversions / Clicks) * 100`
* **Cost Per Click (CPC):** `(Total Cost / Clicks)`

## 🛠️ Analysis Workflow
The project follows a rigorous data science pipeline to ensure statistical validity:

1.  **Exploratory Data Analysis (EDA):** Identifying underlying patterns, outliers, and distribution of engagement across platforms.
2.  **Feature Engineering:** Normalizing raw data into performance ratios (CTR, CPC, Conversion Rate) for a fair "apples-to-apples" comparison.
3.  **Statistical Comparison (A/B Testing):** Using descriptive and inferential statistics to compare the mean performance of the two groups.
4.  **Time Series Analysis:** Utilizing seasonal decomposition to understand performance trends and seasonality from 2021–2024.
5.  **Predictive Modeling:** Implementing **Linear Regression** to quantify the relationship between ad spend and conversion growth.

## 🚀 Key Technologies
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Statistical/ML Modeling:** `scikit-learn` (Linear Regression), `statsmodels` (Seasonal Decomposition)

## 💡 Conclusion & Insights
By analyzing the metrics, this project identifies:
* Which platform yields a lower **Cost Per Conversion**.
* The correlation between ad spend and actual revenue-generating actions.
* Actionable recommendations for the agency to shift budgets toward the higher-performing platform.

---

## 📂 Repository Structure
```bash
├── A_OR_B testing analysis/                  
├── Ad Performance Analysis.ipynb     # Main Jupyter Notebook with analysis
├── README.md               # Project documentation
├── A_B_testing_dataset        # Dataset file
