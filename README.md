# Healthcare Dataset Analysis and Modeling

This project involves a comprehensive analysis of a healthcare dataset. Below is an overview of the steps undertaken, insights derived, and tools used.

## Table of Contents
1. [Dataset Loading and Preprocessing](#dataset-loading-and-preprocessing)
2. [Data Analysis](#data-analysis)
3. [Data Visualization](#data-visualization)
4. [Feature Engineering](#feature-engineering)
5. [Machine Learning Modeling](#machine-learning-modeling)
6. [Dashboard Creation](#dashboard-creation)
7. [Summary and Documentation](#summary-and-documentation)

---

## Dataset Loading and Preprocessing

1. **Loading Dataset**: Loaded the dataset into a Pandas DataFrame for analysis.
2. **Handling Missing Values**: Checked for missing values and handled them via imputation or removal.
3. **Standardizing Column Names**: Standardized column names by converting them to lowercase and removing spaces.
4. **Data Type Validation**: Validated data types and converted columns appropriately (e.g., dates to `datetime`, numerical values).

---

## Data Analysis

5. **Demographic Analysis**: Analyzed demographic distribution, including age and gender.
6. **Medical Conditions Distribution**: Examined the distribution of medical conditions.
7. **Blood Type Analysis**: Studied the distribution of blood types and their frequency.
8. **Hospital-wise Patient Distribution**: Visualized patient distribution across hospitals.
9. **Billing Analysis**: Analyzed billing amounts, including minimum, maximum, average, and outliers.
10. **Admission and Discharge Trends**: Studied trends in admissions and discharges by month or day.
11. **Admission Type Analysis**: Examined the relationship between admission type and medical conditions.

---

## Data Visualization

12. **Correlation Heatmaps**: Created heatmaps for numerical columns to identify relationships.
13. **Medication Trends**: Visualized trends in medications prescribed by doctors.
14. **Test Result Patterns**: Studied patterns in test results against medical conditions.
15. **Hospital Room Trends**: Analyzed room numbers for trends, such as occupancy patterns.
16. **Insurance Coverage Trends**: Examined trends in insurance providers and coverage amounts.

---

## Feature Engineering

17. **Length of Stay**: Created a new feature `Length of Stay` calculated as `discharge_date - admission_date`.
18. **Standardizing Data**: Standardized numerical columns for machine learning.
19. **Age Categories**: Grouped patients into age categories (e.g., children, adults, seniors).
20. **Encoding Categorical Variables**: Encoded variables like gender and blood type for modeling.
21. **Hospital Summary Statistics**: Aggregated data by hospital for summary statistics (e.g., average billing).

---

## Machine Learning Modeling

22. **Length of Stay Prediction**: Predicted `Length of Stay` based on patient attributes.
23. **Billing Amount Prediction**: Predicted billing amounts using features like age and medical condition.
24. **Readmission Prediction**: Used a binary classification model to predict readmission likelihood.
25. **Patient Clustering**: Performed clustering to segment patients using K-Means.
26. **Time-Series Analysis**: Conducted time-series analysis on admissions by date.
27. **Trend Forecasting**: Forecasted admission trends using ARIMA and Prophet.
28. **Outlier Detection**: Identified outliers in billing amounts using Isolation Forest.
29. **Anomaly Detection**: Detected anomalies in `Length of Stay` using Z-scores.

---

## Dashboard Creation

30. **Interactive Dashboards**: Created dashboards using Plotly and Tableau for visualizing key insights.

---

## Summary and Documentation

31. **Evaluation Metrics**: Evaluated models using metrics such as R², MAE, and accuracy.
32. **Cleaned Dataset**: Exported the final cleaned dataset for sharing or further use.
33. **Model Saving**: Saved trained models as `.pkl` files for reuse.
34. **Documentation**: Documented the entire process in this README file and added all resources to the GitHub repository.

---

### Repository Structure

- **data/**: Contains the raw and cleaned datasets.
- **notebooks/**: Jupyter notebooks for analysis and modeling.
- **models/**: Saved machine learning models in `.pkl` format.
- **visualizations/**: Generated plots and dashboards.
- **README.md**: Documentation of the project.

---

### Tools and Libraries Used

- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, TensorFlow, Plotly.
- **Dashboard Tools**: Tableau, Plotly Dash.
- **Machine Learning Models**: Linear Regression, Decision Trees, K-Means, ARIMA, Prophet.
- **Version Control**: GitHub for code and documentation management.

---

### Key Findings

- Identified trends in patient demographics, hospital admissions, and medical conditions.
- Developed predictive models with high accuracy for billing amounts and length of stay.
- Detected anomalies and outliers effectively using statistical methods and machine learning.

---

For further details, please refer to the respective notebooks and reports in the repository.

