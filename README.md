Ecommerce Analytics & ML Intelligence

![Python](https://img.shields.io/badge/Python-Analytics-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-purple)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-orange)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-ML-green)
![Prophet](https://img.shields.io/badge/Prophet-Time%20Series-black)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboards-yellow)
![Shopify](https://img.shields.io/badge/Shopify-Ecommerce-success)

Hanna’s Herbal Care Store (Shopify)
📌 Business Context
Hanna’s Herbal Care Store is a direct-to-consumer ecommerce brand operating on Shopify.
The business sought to move beyond basic reporting and gain actionable insights across revenue quality, product profitability, customer behavior, churn risk, and demand planning.
The goal of this project was to build a decision-ready analytics framework that connects data → insight → business action.
________________________________________
🎯 Objectives
1.	Evaluate revenue quality and identify controllable leakage
2.	Understand product-level profitability and concentration risk
3.	Segment customers using RFM and quantify revenue contribution
4.	Predict customer churn risk using machine learning
5.	Forecast SKU-level demand to support inventory planning
________________________________________
🗂️ Data Overview
•	Source: Shopify transactional data
•	Time Period: Nov 1, 2025 – Dec 31, 2025
•	Data Grain: Orders, customers, SKUs (line-item level)
________________________________________
🧪 Data Quality Assessment
Before analysis, data quality was audited to ensure reliability.
Dimension	Grade	Key Findings
Completeness	A	All SKUs and transactions present
Consistency	B	Minor duplicate order-lines handled during aggregation
Accuracy	A	No negative prices or invalid values
Timeliness	A	Data current through Dec 31, 2025
Conclusion: Data quality was sufficient for advanced analytics and ML modeling.
________________________________________
📈 Analysis 1: Revenue Quality & Leakage
Key Questions
•	Is revenue being fully realized?
•	Where is value leaking?
•	How concentrated is revenue?
Findings
•	Gross Revenue: ₹412,813
•	Net Revenue: ₹399,363
•	MoM Growth: +2.7%
•	Revenue Leakage: ~3.3%, driven primarily by discounts
•	Pending Revenue: ~9% (cash-flow exposure)
Insight
Revenue performance is stable, but discounting is the dominant controllable lever impacting net revenue and margins.
________________________________________
📦 Analysis 2: Product Profitability
Key Questions
•	Which products drive profit?
•	Are any SKUs loss-making?
•	Is there concentration risk?
Findings
•	No loss-making SKUs identified
•	Strong positive relationship between revenue and gross profit
•	A small number of SKUs drive a disproportionate share of profit
Hero SKUs:
•	Tulsi Shampoo
•	Aloe Vera Gel
•	Amla Hair Oil
Insight
The business benefits from strong unit economics but faces profit concentration risk if hero SKUs underperform.
________________________________________
👥 Analysis 3: Customer Segmentation (RFM)
Methodology
Customers were segmented using:
•	Recency
•	Frequency
•	Monetary Value
Findings
•	~68% of revenue comes from Potential Loyalists and Loyal Customers
•	Frequency is the strongest driver of customer value
•	At-Risk customers contribute little revenue but signal churn risk
Insight
Retention and frequency growth strategies deliver the highest ROI.
________________________________________
🤖 Analysis 4: Churn Prediction (Machine Learning)
Model
•	Algorithm: Logistic Regression (Scikit-learn)
•	Features: RFM metrics
•	Objective: Predict customer churn probability
Key Results
•	Declining purchase frequency sharply increases churn risk
•	Monetary value alone does not prevent churn
•	Customers disengage behaviorally before revenue declines
Business Impact
•	Early churn detection
•	Targeted win-back and retention campaigns
•	Improved Customer Lifetime Value (CLV)
________________________________________
🔮 Analysis 5: Demand Forecasting (Time-Series ML)
Model
•	Algorithm: META Prophet
•	Granularity: Daily, SKU-level
Findings
•	Clear weekly seasonality across SKUs
•	No strong long-term demand trend (mature products)
•	Forecast uncertainty increases with horizon (expected behavior)
Insight
Forecasts are reliable for short- to mid-term inventory planning, with safety stock guided by confidence intervals.
________________________________________
💡 Business Recommendations
Revenue Optimization
•	Cap and segment discount strategies
•	Reduce reliance on blanket promotions
Customer Growth
•	Convert Potential Loyalists into Loyal Customers
•	Monitor frequency drops as early churn signals
Product Strategy
•	Protect hero SKUs with inventory and pricing stability
•	Bundle mid-tier SKUs to lift AOV
Inventory Planning
•	Use forecast mean for planning
•	Use upper confidence bound for safety stock
________________________________________
🛠️ Tools & Technologies
•	Python (Pandas, NumPy)
•	Scikit-learn
•	Prophet
•	Power BI / Data Visualization
•	Jupyter Notebooks
________________________________________
📌 Outcome & Value
This case study demonstrates how analytics and ML can:
•	Improve revenue quality
•	Reduce churn risk
•	Optimize inventory decisions
•	Enable data-driven growth strategies
The framework is scalable, interpretable, and business-ready.
________________________________________
🚀 Future Enhancements
•	Add SHAP for churn explainability
•	Integrate marketing and promotion data
•	Automate reporting pipelines
•	Deploy churn scoring as a production service
________________________________________
👤 Author
Nithiskumar K


