# UAE Banking Customer Satisfaction Analysis

Overview:

Goal:
Identify the primary drivers of customer satisfaction in the UAE banking sector and uncover meaningful trends across customer segments.

The Problem:
Large-scale survey data (222 questions) contained high dimensionality and strong multicollinearity, making simple correlation ranking and linear modeling unreliable for identifying true satisfaction drivers.

The Solution:
Built a structured analytical pipeline including systematic data cleaning, conceptual feature grouping, robust machine learning modeling, and interpretability techniques to extract reliable drivers and segment-level insights.

Tech Stack:
Python, Pandas, NumPy, Scikit-Learn, SHAP

Key Highlights:

Performed comprehensive data auditing and cleaning (redundancy removal, missingness handling, variance filtering).

Grouped CSAT variables into five conceptual domains to improve interpretability.

Replaced unstable OLS regression (VIF 100–300) with Histogram Gradient Boosting for robustness.

Applied permutation importance and SHAP to identify true satisfaction drivers.

Identified Physical Reach (branches, ATMs, waiting time, comfort) as the master driver (~3x impact vs Service Support).

Conducted segmentation analysis across age, account tenure, bank, and service channel.

Discovered lower satisfaction among first-year and senior (50+) customers.

Identified key analytical limitations, including lack of survey metadata and potential self-reporting bias, ensuring transparent interpretation of results and responsible business recommendations.

Produced actionable strategic recommendations aligned with operational decision-making.
