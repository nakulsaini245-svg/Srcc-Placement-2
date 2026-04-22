🛒 E-Commerce Growth & Retention Analysis

Analyzed 1M+ retail transactions to uncover customer retention patterns, revenue trends, and growth opportunities using SQL and Python.


📌 Objective
To perform an end-to-end growth analysis on a real-world e-commerce dataset — identifying high-value customer segments, retention bottlenecks, and revenue drivers to support data-driven business decisions.

🛠️ Tools & Technologies
ToolUsageSQL (SQLite)Data querying, segmentation, funnel analysisPython (Pandas, Seaborn, Matplotlib)Cohort analysis, visualizationsDB Browser for SQLiteSQL execution and data explorationGoogle ColabPython environment

📊 Dataset

Source: Online Retail II - UCI via Kaggle
Size: 1,067,371 transactions
Period: December 2009 – December 2011
Region: UK-based online retail store


🔍 Key Business Insights
#Insight155.1% Repeat Customer Rate — majority of customers return, indicating strong product-market fit2Average Order Value: £465.99 — high AOV suggests bulk/wholesale buying behaviour3United Kingdom dominates with £16.38M revenue across 5,410 customers4Peak Revenue Month: March 2010 — potential seasonal demand spike5Top 20% customers drive 80% of revenue — classic Pareto distribution confirmed675.4% Retention Rate — only 1,461 out of 5,943 customers are one-time buyers

🗂️ SQL Analysis
1️⃣ Revenue by Country

UK leads with £16.38M, followed by EIRE (£615K) and Netherlands (£548K)
Top 3 countries account for ~90% of total revenue

2️⃣ Customer Segmentation (RFM-based)
SegmentCustomersAvg Revenue/CustomerChampion (10+ orders)1,243£12,011.53Loyal (5-9 orders)1,260£1,911.30Returning (2-4 orders)1,979£785.76One-Time1,461£269.44

Champions spend 44x more than one-time buyers — high retention ROI potential

3️⃣ Monthly Active Users & Revenue

Tracked MAU and revenue per user across 24 months
Identified growth trends and seasonal patterns

4️⃣ Top 10 Products by Revenue

REGENCY CAKESTAND 3 TIER — £327,813 (top revenue product)
WHITE HANGING HEART T-LIGHT HOLDER — 93,050 units sold (top volume)

5️⃣ One-Time vs Repeat Customers

1,461 one-time buyers vs 4,482 repeat customers
Retention Rate: 75.4%


📈 Python Analysis
Cohort Retention Heatmap

Built monthly cohort analysis to track how well each acquisition batch retains over time
Identified which cohorts had strongest long-term retention

Revenue Trend Analysis

Plotted monthly revenue curve across 2 years
Identified peak periods and growth inflection points


💡 Business Recommendations

Re-engage One-Time Buyers — 1,461 customers with avg £269 spend → targeted email/discount campaign could unlock significant revenue
Protect Champion Segment — 1,243 customers driving £12K avg revenue need VIP retention programs
Expand beyond UK — Netherlands and Germany show high revenue per customer despite low volume → growth opportunity
Leverage Peak Month Trends — March spike suggests pre-spring campaign opportunity


📁 Repository Structure
ecommerce-growth-analysis/
│
├── analysis_queries.sql       # All 5 SQL queries
├── notebook.ipynb             # Python analysis + visualizations
└── README.md                  # Project overview
