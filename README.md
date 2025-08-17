# Online Retail RFM Analysis

This project performs **RFM (Recency, Frequency, Monetary) analysis** on the Online Retail dataset to segment customers and generate actionable insights.  
The analysis includes **data cleaning, feature engineering, RFM scoring, and visualization**.

---

## 📊 Steps in the Analysis
1. **Data Cleaning**
   - Remove null values
   - Convert `InvoiceDate` to datetime
   - Remove cancelled transactions
   - Create `Revenue` column  

2. **Reference Date**
   - Define snapshot date (last date + 1 day)

3. **RFM Metrics**
   - Recency = Days since last purchase
   - Frequency = Number of invoices
   - Monetary = Total spend

4. **RFM Scoring**
   - Quartile-based scoring (1–4)
   - Combine into `RFM_Segment` and `RFM_Score`

5. **Visualization**
   - Bar Chart of RFM segments
   - Distribution plots of Recency, Frequency, and Monetary


---

## 📥 Dataset
Due to size, the dataset is not included in this repository.  
You can download it from:  
👉 [Online Retail Dataset (UCI Repository)](https://archive.ics.uci.edu/ml/datasets/online+retail)


---

## 📌 Insights
- Customers with **low Recency & high Frequency/Monetary** are the most valuable (loyal).
- Customers with **high Recency & low Frequency/Monetary** are at risk of churn.
- Segmentation helps in targeted marketing campaigns.

---

v
