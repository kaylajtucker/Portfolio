# Kayla Tucker Portfolio





## Table of Contents

- [Portfolio Projects](#portfolio-projects)
  - Python
    - [Connecticut Housing Affordability Analysis & Forecasting](#connecticut-housing-affordability-analysis--forecasting)
    - [Student Placement Prediction](#student-placement-prediction)
  - SQL
    - [Water Quality Monitoring Database & SQL Analysis](#water-quality-monitoring-database--sql-analysis)
  - Tableau
    - [Superstore Profitability & Regional Performance Dashboard](#superstore-profitability--regional-performance-dashboard)
  - JavaScript / D3
    - [University Parental Leave Visualization](#university-parental-leave-visualization)
- [Education](#education)



## Portfolio Projects

In this section, I will list data analytics and data science projects, briefly describing the technology stack and skills used to complete each project.


### Connecticut Housing Affordability Analysis & Forecasting

**Code:** [`Connecticut Housing Affordability Analysis & Forecasting.ipynb`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Connecticut_Housing_Affordability_Analysis_%26_Forecasting.ipynb)

**Goal:** To analyze how housing prices and occupational income in Connecticut changed from 2006–2023 and evaluate long-term housing affordability trends.

**Description:** This project combines Connecticut housing, occupational income, and inflation data. The analysis includes data cleaning, merging multiple datasets, inflation-adjusted comparisons, exploratory data analysis, feature engineering, predictive modeling, and affordability forecasting through 2040.

**Skills:** data cleaning, data integration, exploratory data analysis, feature engineering, inflation adjustment, regression modeling, hyperparameter tuning, forecasting, data visualization.

**Technology:** Python, Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost.

**Results:** Historical analysis showed that housing prices generally grew faster than occupational income. The XGBoost projections estimated a median affordability gap of approximately $225,096 in 2024 and about $228,780 by 2040, suggesting continued affordability pressure under the projected trends.


### Student Placement Prediction

**Code:** [`Student Placement Prediction.ipynb`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Student_Placement_Prediction.ipynb)

**Presentation:** [`Student Placement Prediction.pptx`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Student_Placement_Prediction.pptx)

**Goal:** To build a supervised machine learning classification pipeline to predict student job placement.

**Description:** The project used a dataset of 10,000 student records and included data exploration, categorical encoding, feature scaling, stratified train-test splitting, model comparison, cross-validation, and hyperparameter tuning.

**Skills:** data preprocessing, exploratory data analysis, feature encoding, feature scaling, classification modeling, cross-validation, hyperparameter tuning, model evaluation, confusion matrices.

**Technology:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn.

**Results:** Random Forest produced the strongest performance at approximately 99.9% accuracy, while the tuned SVM achieved 97.4% accuracy. Important predictors included CGPA, previous semester results, and communication skills.


### Water Quality Monitoring Database & SQL Analysis

**Code:** [`Water Quality Monitoring Database.sql`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Water%20Quality%20Monitoring%20Database.sql)

**Written Project:** [`Water Quality Database Project.pdf`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Water%20Quality%20Database%20Project.pdf)

**Goal:** To implement a normalized MySQL database for environmental water quality data and use SQL to analyze chlorophyll-a concentrations and sampling activity.

**Description:** The project used Chesapeake Bay water quality data provided as a flat CSV file. Using a supplied relational schema, I created and populated related tables for stations, events, samples, parameters, methods, labs, and measurements. I also created an ERD and developed SQL queries to analyze the data.

**Skills:** relational database implementation, joins, subqueries, aggregate functions, GROUP BY, HAVING, UNION, date functions, primary keys, foreign keys, ERD interpretation.

**Technology:** MySQL, MySQL Workbench, SQL.

**Results:** The analysis compared monthly and overall chlorophyll-a averages, identified station-level minimum and maximum measurements, summarized sample replicate types, and evaluated chlorophyll-a thresholds by station and month.


### Superstore Profitability & Regional Performance Dashboard

**Dashboard:** [`Superstore Profitability Dashboard`](https://public.tableau.com/views/SuperstoreProfitabilityRegionalPerformanceDashboard/ProfitabilityStoryCategoryRegionDrivers?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**File:** [`Superstore Profitability Dashboard.twbx`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Superstore%20Profitability%20Dashboard.twbx)

**Written Analysis:** [`Superstore Analysis`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Superstore%20Profitability%20Analysis.pdf)

**Goal:** To analyze sales and profitability across product categories, subcategories, and regions to identify areas driving strong performance and areas contributing to losses.

**Description:** The project evaluates Superstore profitability using KPIs, product and regional analysis, profit-versus-sales comparisons, Pareto analysis, outlier analysis, geographic analysis, and interactive filtering.

**Skills:** dashboard design, KPI analysis, calculated fields, parameters, LOD expressions, Pareto analysis, geographic analysis, data visualization, business recommendations.

**Technology:** Tableau.

**Results:** Technology was the strongest-performing category, while Furniture showed weaker profitability. The West and East regions performed more strongly overall, while the Central region, particularly Texas, showed repeated losses across several Furniture subcategories.


### University Parental Leave Visualization

**Project Report:** [`University Parental Leave Visualization`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/parental-leave-project-report.md)

**Interactive Visualization:** [`Observable Chart`](https://observablehq.com/d/669fe1ffb022b1a6)

**Goal:** To compare paid parental leave policies at public and private universities and examine differences in leave provided to women and men.

**Description:** This project analyzed parental leave policies from U.S. and Canadian universities. After cleaning the data and exploring it in Python, I created an interactive grouped bar chart in Observable to compare average paid leave by university type and gender.

**Skills:** data cleaning, exploratory data analysis, interactive visualization, annotation design, hover interactions, tooltip design, comparative analysis.

**Technology:** Python, Pandas, Matplotlib, Seaborn, JavaScript, D3, Observable.

**Results:** Private universities generally offered more paid parental leave overall, while public universities showed a larger difference between leave provided to women and men.


## Education

Old Dominion University: Master of Science - MS, Data Science & Analytics with a Concentration in Business Intelligence, August 2025 - December 2026

Old Dominion University: Bachelor of Science - BS, Computer Science, August 2021 - May 2025

