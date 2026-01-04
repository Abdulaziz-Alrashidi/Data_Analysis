High–cardinlity: End-to-End Data Exploration & Feature Engineering

Goal: Analyze and understand the Adult Income Census dataset to extract actionable insights from high-cardinality categorical features, uncover demographic and employment patterns, and prepare the data for downstream modeling.

The Problem: The dataset contains numerous categorical features with many unique values (high cardinality) and imbalanced classes, making it challenging to interpret trends and derive insights directly. Simplifying the data without losing important signals was crucial for meaningful analysis and potential predictive modeling.

The Solution: Performed a comprehensive, step-by-step data analysis workflow, focusing on cleaning, profiling, consolidating categories, and systematically examining the relationships across the different features. The approach prioritized interpretability, reproducibility, and maintaining meaningful signals in the data.

Tech Stack: Python, Pandas, NumPy, Scikit-Learn, Jupyter Notebook

Key Highlights:

Data Overview and Preparation:

Examined dataset structure, distributions, and missing or inconsistent values.

Handled high-cardinality categorical features by merging semantically similar categories while preserving key demographic signals.

Reduced dimensionality in categorical variables to simplify analysis and ensure interpretability.

Exploratory Data Analysis (EDA):

Investigated distributions, correlations, and relationships between demographic and employment features.

Explored income distributions across work classes, education levels, and other demographic groups.

Identified patterns by using cross-tabulation

Feature Engineering for Analysis:

Consolidated work classes into Private, Public, and Self-employed to reduce imbalance and simplify interpretation.

Combined education categories into logical groups (e.g., HS-grad, Undergrad/Associate, Bachelors/Masters, Prof-school/Doctorate) to capture meaningful trends in income.

Derived additional features to highlight demographic and income-related patterns.

Comparative Approach for Downstream Modeling:

Prepared three dataset versions:

Feature-engineered: reduced cardinality, simplified categories, 30 features.

Fully encoded: one-hot encoding of all categorical variables, 103 features.

Raw dataset: unprocessed, for CatBoost models supporting categorical features natively.

This comparison highlighted trade-offs between interpretability, dimensionality, and computational efficiency.

Insights:

Feature engineering retained meaningful predictive information while improving dataset compactness and interpretability.

Fully one-hot encoded data slightly increased predictive performance but at the cost of higher dimensionality and complexity.

Raw data provided maximal predictive potential but required substantially more computational resources and posed technical complexity.

Outcome: The project demonstrates a careful, data-driven approach to handling high-cardinality and imbalanced categorical datasets, balancing insight discovery with practical considerations for analysis and future modeling. It emphasizes interpretability, reproducibility, and thoughtful feature engineering over purely predictive performance.
