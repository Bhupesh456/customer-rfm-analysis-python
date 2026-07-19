# 📊 Customer RFM Analysis using Python & Pandas

An end-to-end Customer Segmentation project that uses **RFM (Recency, Frequency, Monetary) Analysis** to identify valuable customer groups based on purchasing behavior.

This project demonstrates the complete data analytics workflow—from data cleaning and preprocessing to customer segmentation, visualization, and business insight generation.

---

# 🎯 Project Objective

The objective of this project is to analyze customer purchasing behavior and segment customers into meaningful business groups using the RFM model.

Businesses can use these insights to:

- Improve customer retention
- Identify high-value customers
- Reduce customer churn
- Personalize marketing campaigns
- Increase customer lifetime value

---

# 📂 Dataset

The analysis uses two datasets:

- Customer Master Data
- Customer Transaction Data

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Datetime
- Jupyter Notebook

---

# 📈 Project Workflow

## 1️⃣ Data Loading

Loaded customer master data and transaction history.

---

## 2️⃣ Data Cleaning

Performed several preprocessing steps including:

- Missing value detection
- Duplicate record removal
- Invalid customer validation
- Data type conversion
- Date formatting
- Transaction verification

This ensures that the data is reliable before analysis.

---

## 3️⃣ RFM Calculation

Calculated three important customer metrics:

### 📅 Recency
Days since the customer's last purchase.

### 🔁 Frequency
Total number of purchases made by the customer.

### 💰 Monetary
Total amount spent by the customer.

---

## 4️⃣ RFM Scoring

Each customer was assigned an RFM score using quantile-based scoring.

The scores were then combined to classify customers into business-friendly segments.

---

# 👥 Customer Segments

- 🏆 Champions
- ❤️ Loyal Customers
- 🌱 Potential Loyalists
- 💰 Big Spenders
- ⚠ At Risk
- ❌ Lost Customers
- 📦 Others

---

# 📊 Visualizations

Correlation Heatmap
![Correlation Heatmap](screenshots/correlation_heat_map.png)

Shows relationships between RFM metrics and their corresponding scores.

Customer Distribution by Segment
![Customer Distribution](screenshots/customer_distribution_rfm.png)

Displays how customers are distributed across RFM segments.

Customer Spending Distribution
![Customer Spending](screenshots/customer_spending_by_segment.png)

Compares customer spending patterns across segments using a box plot.

Frequency vs Monetary Analysis
![Frequency vs Monetary](screenshots/frequency_monetary_scatter.png)

Illustrates how purchase frequency relates to customer spending.

Recency vs Monetary Analysis
![Recency vs Monetary](screenshots/recency_monetary_scatter.png)

Highlights purchasing behavior based on spending and recent activity.

Revenue by Customer Segment
![Revenue by Segment](screenshots/revenue_by_customer_segment.png)

Shows which customer groups contribute the most revenue.

Revenue Contribution
![Revenue Contribution](screenshots/revenue_contribution_by_segments.png)

Visualizes each customer segment's percentage contribution to total revenue.
---

# 💡 Key Business Insights

- Champions generate significant business value and should be retained through loyalty programs.

- Loyal customers are stable buyers and can be targeted for premium offerings.

- Potential Loyalists can become long-term customers through personalized campaigns.

- At Risk customers require re-engagement before they churn.

- Lost customers may require win-back campaigns.

- Revenue analysis helps businesses focus marketing efforts on high-value customer groups.

---

# 📁 Project Structure

```
RFM-Analysis/
│
├── data/
│   ├── Customer_Master_Data.csv
│   ├── Customer_Transactions.csv
│
├── notebook/
│   └── rfm_analysis_with_pandas.ipynb
│
├── screenshots/
│   ├── customer_distribution_rfm.png
│   ├── revenue_contribution_by_segments.png
│   └── recency_monetary_scatter.png
│
├── output/
│   └── RFM_Analysis.xlsx
│
├── requirements.txt
│
└── README.md
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Customer Analytics
- RFM Analysis
- Customer Segmentation
- Pandas
- NumPy
- Data Visualization
- Business Intelligence
- Business Insight Generation

---

# 📌 Business Applications

This project can be applied in:

- Retail Analytics
- E-commerce
- Banking
- Financial Services
- Insurance
- Subscription Businesses
- Customer Relationship Management (CRM)

---

# 👨‍💻 Author

**Bhupesh Masram**

Aspiring Data Analyst | Financial Analytics | Python | SQL | Power BI

Always learning, building real-world analytics projects, and transforming data into meaningful business insights.
