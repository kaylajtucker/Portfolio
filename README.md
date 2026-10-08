# Portfolio





### Superstore Profitability & Regional Performance Dashboard

**Dashboard:** [`Superstore Profitability Dashboard`](https://public.tableau.com/views/SuperstoreProfitabilityRegionalPerformanceDashboard/ProfitabilityStoryCategoryRegionDrivers?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**File:** [`Superstore Profitability Dashboard.twbx`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Superstore%20Profitability%20Dashboard.twbx)

**Written Analysis:** [`Superstore Analysis`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Superstore%20Profitability%20Analysis.pdf)

**Goal:** To analyze sales and profitability across product categories, subcategories, and regions in order to identify areas driving strong performance and areas contributing to losses.

**Description:** The project analyzes the Superstore dataset to evaluate profitability across product categories, subcategories, states, and regions. The analysis includes KPI tracking, product performance, regional profitability, profit-versus-sales analysis, Pareto analysis, outlier analysis, and interactive filtering. The dashboard was designed to identify high-performing products and regions while highlighting areas where pricing, inventory, or operational changes may improve profitability.

**Skills:** data analysis, dashboard design, KPI analysis, calculated fields, parameters, LOD expressions, Pareto analysis, geographic analysis, data visualization, business recommendations.

**Technology:** Tableau.

**Results:** The analysis showed that Technology was the strongest-performing category, with Phones, Copiers, and Accessories contributing strong profits. Furniture was the weakest category, with Chairs and Tables contributing to losses in several areas. The West and East regions performed more strongly overall, while the Central region showed weaker profitability, with Texas standing out for repeated losses across multiple Furniture subcategories. The findings supported recommendations related to inventory reduction, pricing adjustments, regional strategy, and increased support for high-performing Technology products.


### Water Quality Monitoring Database & SQL Analysis

**Code:** [`Water Quality Monitoring Database.sql`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Water%20Quality%20Monitoring%20Database.sql)

**Written Project:** [`Water Quality Database Project.pdf`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Water%20Quality%20Database%20Project.pdf)

**Goal:** To implement a normalized MySQL database for environmental water quality data and use SQL to analyze chlorophyll-a concentrations, sampling patterns, and station-level measurements.

**Description:** The project used Chesapeake Bay water quality monitoring data provided as a flat CSV file. Using a supplied relational schema, I created and populated related tables for stations, events, samples, parameters, methods, labs, and measurements in MySQL. I also created an ERD and wrote SQL queries to analyze chlorophyll-a concentrations and sampling activity.

**Skills:** relational database implementation, SQL joins, subqueries, aggregate functions, GROUP BY, HAVING, UNION, date functions, primary keys, foreign keys, ERD interpretation.

**Technology:** MySQL, MySQL Workbench, SQL.

**Results:** The analysis compared monthly chlorophyll-a averages with the overall average, identified minimum and maximum CHLA measurements at each station with their collection dates and times, summarized sample replicate types, and identified station-month combinations where CHLA measurements remained at or below the specified 18.0 µg/L threshold.



### Connecticut Housing Affordability Analysis & Forecasting

**Notebook:** [`Connecticut Housing Affordability Analysis & Forecasting`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Connecticut_Housing_Affordability_Analysis_%26_Forecasting.ipynb)

**Goal:** To analyze how housing prices and occupational income in Connecticut changed from 2006–2023 and evaluate whether housing affordability has worsened over time.

**Description:** This project combines Connecticut housing, occupational income, and inflation data to examine long-term affordability trends. The analysis includes data cleaning, merging multiple datasets, inflation-adjusted comparisons, affordability metrics, visualizations, feature engineering, and predictive modeling. An XGBoost regression model was developed and tuned using RandomizedSearchCV and GridSearchCV, then used to generate affordability projections through 2040. 

**Skills:** data cleaning, data integration, exploratory data analysis, feature engineering, inflation adjustment, regression modeling, hyperparameter tuning, forecasting, data visualization.

**Technology:** Python, Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost.

**Results:** Historical analysis showed that Connecticut housing prices have generally grown faster than occupational income, with the affordability gap becoming more pronounced in recent years. The XGBoost projections estimated a median affordability gap of approximately $225,096 in 2024 and about $228,780 by 2040, indicating persistent affordability pressure under the projected trends. 



### Student Placement Prediction

**Notebook:** [`Student Placement Prediction.ipynb`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Student_Placement_Prediction.ipynb)

**Presentation:** [`Student Placement Prediction.pptx`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/Student_Placement_Prediction.pptx)

**Goal:** To build a supervised machine learning classification pipeline to predict whether a student would receive job placement based on academic performance, internship experience, communication skills, and other student factors.

**Description:** The project used a dataset of 10,000 student records and included data exploration, categorical encoding, feature scaling, stratified train-test splitting, model comparison, cross-validation, and hyperparameter tuning. Multiple classification models were evaluated, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors. 

**Skills:** data preprocessing, exploratory data analysis, feature encoding, feature scaling, classification modeling, train-test splitting, cross-validation, hyperparameter tuning, model evaluation, confusion matrices.

**Technology:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn.

**Results:** Random Forest produced the strongest performance, achieving approximately 99.9% accuracy, while the tuned SVM achieved 97.4% accuracy. The analysis identified CGPA, previous semester results, and communication skills as important predictors of placement, while also noting class imbalance as a limitation. 


### University Parental Leave Visualization

**Project Report:** [`University Parental Leave Visualization`](https://github.com/kaylajtucker/PortfolioProjects/blob/main/parental-leave-project-report.md)

**Interactive Visualization:** [`Observable Chart`](https://observablehq.com/d/669fe1ffb022b1a6)

**Goal:** To compare paid parental leave policies at public and private universities and examine differences in leave provided to women and men.

**Description:** This project analyzed parental leave policies from U.S. and Canadian universities using data from the 2018 parental leave repository. After cleaning missing and invalid values, I explored the data in Python and developed an interactive grouped bar chart in Observable to compare average paid leave by university type and gender. :chatgpt-content-reference{index="0"}

**Skills:** data cleaning, exploratory data analysis, data visualization, interactive visualization, annotation design, hover interactions, tooltip design, comparative analysis.

**Technology:** Python, Pandas, Matplotlib, Seaborn, JavaScript, D3, Observable.

**Results:** The analysis found that private universities generally offered more paid parental leave overall, while public universities showed a larger gap between leave provided to women and men. The final visualization used annotations, hover highlighting, and tooltips to make these differences easier to interpret. :chatgpt-content-reference{index="1"} :chatgpt-content-reference{index="2"}
