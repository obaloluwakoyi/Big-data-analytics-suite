📊 Big Data Analytics & Business Intelligence Suite
📌 Executive Summary
This repository is a curated collection of end-to-end data pipelines. It demonstrates the ability to transform massive, raw datasets (up to 1M+ rows) into high-fidelity dashboards that drive executive decision-making.

🚀 Deep Dive: Featured Projects
⚡ 1. Quick Commerce KPI Dashboard (Q-Commerce.ipynb)
This project simulates a real-world "Quick Commerce" (10-30 minute delivery) environment.

Core Metrics Analyzed:
| Metric | Description | Business Value |
| :--- | :--- | :--- |
| Order Prep Time (OPT) | Time from order placement to dispatch. | Identifies warehouse bottlenecks. |
| Delivery Latency | Delta between estimated and actual arrival. | Directly correlates to customer churn. |
| Revenue per Slot | Sales volume categorized by time of day. | Optimizes driver shift scheduling. |

Advanced Logic: Implemented custom binning for delivery times to identify "Extreme Latency" outliers affecting the bottom 5% of customers.

Visual Strategy: Utilized a dual-axis approach to show the correlation between Average Rating and Delivery Speed.

💰 2. Tech Industry Salary Benchmarking (Salary_Data.ipynb)
An intensive Exploratory Data Analysis (EDA) of 22,000+ global salary records.

Key Insight: While experience (Years) is the primary driver of salary, location-based cost-of-living adjustments create "Golden Zones"—cities where the salary-to-rent ratio is most favorable for engineers.

Methodology:

Data Cleaning: Handled inconsistent company naming conventions using string fuzzy matching.

Statistical Profiling: Used interquartile range (IQR) filtering to remove executive-level outliers and focus on mid-to-senior engineering roles.

Visualization: Built a "Salary Heatmap" to visualize geographic pay disparities.

🛠️ Technical Workflow
Every project in this suite follows a rigorous Data Engineering Lifecycle:

Ingestion: Loading large-scale CSV/JSON logs into optimized Pandas DataFrames.

Transformation: Feature engineering (e.g., converting timestamps into "Peak Hour" categories).

Analysis: Hypothesis testing regarding delivery speeds and compensation variables.

Synthesis: Packaging findings into interactive Plotly dashboards and static Seaborn reports.

💻 How to Run Locally
Clone the repository:

Bash

git clone https://github.com/obaloluwakoyi/Big-data-analytics-suite.gir
Install dependencies:

Bash

pip install -r requirements.txt
Launch the environment:
Open any .ipynb file in Jupyter Lab or VS Code to view the interactive visualizations.



🏗️ Future Roadmap
[ ] Real-time Stream: Integrating a mock Kafka stream to simulate live order updates for the Q-Commerce dashboard.

[ ] Advanced NLP: Adding sentiment analysis to the "Customer Rating" logs to categorize feedback.
