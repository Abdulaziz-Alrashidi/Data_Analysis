# DataAnalysis Projects Repository

This repository showcases a diverse collection of data analysis and data science projects, demonstrating skills in SQL, Python, Power BI, machine learning, and advanced analytics. Each project highlights end-to-end workflows, from data acquisition and integration to cleaning, transformation, exploration, visualization, and analysis. The projects are self-contained, reproducible, and emphasize actionable insights, reflecting real-world analytical problem-solving.

## Projects

*Project 1: SpaceX Analysis (Completed)*
---

Goal: Determine the likelihood of successful first-stage landings to estimate launch costs.

The Problem: Commercial space flight cost is heavily dependent on rocket reusability.

The Solution: Built a classification pipeline using Python to predict landing outcomes.

Tech Stack: Python, SQL, Scikit-Learn, Folium

Key Highlights: 

Consolidation of datasets from multiple sources (APIs, web scraping, CSVs, SQL, and local files) into structured and validated format

Performed Exploratory Data Analysis (EDA) using SQL queries.

Developed an interactive dashboard for real-time launch site visualization.

Trained and compared SVM, Decision Tree, and KNN models for optimal accuracy.


*Project 2: High-cardinality Analysis (Completed)*
---

Goal: Explore and analyze the Adult Income Census dataset to uncover patterns in demographics and employment, with a focus on high-cardinality categorical features.

The Problem: Large categorical datasets can be complex, imbalanced, and high-dimensional, making it challenging to extract meaningful insights while maintaining interpretability.

The Solution: Performed end-to-end data analysis and feature engineering to clean, consolidate, and simplify categories, revealing actionable patterns and ensuring reproducibility.

Tech Stack: Python, Pandas, NumPy, Scikit-Learn

Key Highlights:

Conducted detailed data profiling and handling of missing or inconsistent values.

Systematically reduced cardinality in high-cardinality features by merging semantically similar categories while preserving meaningful signals.

Performed exploratory data analysis (EDA) to identify trends, distributions, correlations, and class imbalances.

Created derived features to enhance interpretability and analytical insights.

Compared multiple approaches (feature-engineered, fully encoded, raw) to understand trade-offs between complexity, interpretability, and predictive power.


*Project 3: Sales Performance & Customer Segmentation Analysis (Completed)*
---

Goal:
Analyze sales performance and customer behavior to uncover operational inefficiencies, profitability drivers, and strategic customer segments.

The Problem:
Transactional sales data often contains inconsistent data types, missing values, and noisy records. Without proper auditing and validation, downstream analysis and dashboards can be misleading.

The Solution:
Implemented a structured data auditing, cleaning, and transformation pipeline before engineering KPIs and customer-level insights, ensuring analytical accuracy and reliability.

Tech Stack:
Python, Pandas, Power BI

Key Highlights:

Performed systematic data auditing to validate schema, data types, null values, and logical consistency across all fields.

Standardized and corrected numerical, categorical, and datetime columns to ensure analytical readiness and Power BI compatibility.

Conducted data quality checks to confirm completeness, valid ranges, and realistic distributions before analysis.

Engineered operational KPIs such as shipping lag and profit margin to assess efficiency and profitability.

Applied the RFM (Recency, Frequency, Monetary) framework to segment customers based on behavioral patterns.

Aggregated transactional data at the customer level to distinguish high-value, loyal, and at-risk segments.

Built an interactive Power BI dashboard with KPI cards and customer segmentation visuals for executive-level insights.
