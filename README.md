# 🏥 U.S. Chronic Disease Indicators Analysis using Python

## 📖 Project Overview

The **U.S. Chronic Disease Indicators (CDI)** dataset, published by the **Centers for Disease Control and Prevention (CDC)**, provides comprehensive information on chronic disease prevalence, mortality, health status, risk factors, and preventive healthcare indicators across the United States.

This project applies **Python-based data analytics techniques** to transform raw public health data into meaningful insights. The analysis includes **data preprocessing, feature engineering, exploratory data analysis (EDA), statistical analysis, and visualization** to identify disease patterns, demographic variations, and year-wise trends that support evidence-based public health decision-making.

---

# 🎯 Problem Statement

Chronic diseases remain one of the leading causes of illness and mortality in the United States. The CDI dataset contains a large volume of healthcare records collected across multiple states, demographic groups, and reporting years. Due to the complexity and scale of the dataset, extracting meaningful insights through manual analysis is challenging.

This project leverages Python to clean, transform, analyze, and visualize the dataset in order to discover trends, evaluate disease indicators, and support data-driven healthcare planning.

---

# 🎯 Project Objectives

- Analyze chronic disease indicators across the United States using public health surveillance data.
- Compare disease indicator values across states, years, and demographic groups.
- Evaluate trends in chronic disease prevalence and mortality.
- Assess the distribution and variability of disease indicators using statistical analysis.
- Identify relationships among healthcare indicators through exploratory data analysis and visualization.
- Generate data-driven insights to support evidence-based public health decision-making.

---

# 📂 Dataset Overview

| Attribute | Details |
|-----------|---------|
| Dataset Name | U.S. Chronic Disease Indicators (CDI) |
| Data Source | Centers for Disease Control and Prevention (CDC) |
| Total Records | 283,950 |
| Total Columns | 24 |
| Time Period | 2020 – 2023 |
| Data Type | Numerical & Categorical |

### Key Dataset Attributes

- YearStart & YearEnd
- State / Location
- Disease Topic
- Health Indicator
- Disease Value
- Data Source
- Confidence Limits
- Demographic Stratification

---

# ⚙️ Project Methodology

```
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Data Transformation
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Statistical Analysis
        │
        ▼
Data Visualization
        │
        ▼
Key Insights
        │
        ▼
Business Recommendations
        │
        ▼
Conclusion

# 🧹 Data Preprocessing

### Data Cleaning

- Removed duplicate records.
- Handled missing values.
- Converted appropriate data types.
- Renamed columns for improved readability.

### Data Transformation

- Standardized categorical variables.
- Extracted Latitude and Longitude from Geolocation.
- Optimized data types for memory efficiency.
- Improved data consistency for reliable analysis.

---

# 🔧 Feature Engineering

- Created **RegionType** for geographical classification.
- Developed **SurveyType** based on healthcare data sources.
- Calculated **ConfidenceWidth** using confidence interval values.
- Created **DemographicGroup** for simplified demographic analysis.

---

# 📊 Exploratory Data Analysis

- Dataset Structure Analysis
- Missing Value and Duplicate Analysis
- Descriptive Statistical Analysis
- Disease, State, and Data Source Analysis
- Year-wise and Disease-wise Trend Analysis
- Grouped Analysis for Pattern Identification

---

# 📈 Statistical Analysis

### Measures of Dispersion

- Mean
- Variance
- Standard Deviation
- Coefficient of Variation

### Distribution Analysis

- Skewness
- Kurtosis

### Correlation Analysis

- Correlation Matrix
- Correlation Heatmap

---

# 💡 Key Insights

- Chronic disease indicators exhibit variations across U.S. states and territories.
- Disease patterns differ across demographic groups and health topics.
- Year-wise analysis reveals changes in disease indicator values over time.
- Statistical analysis indicates variability in disease measurements.
- Correlation analysis demonstrates strong relationships between disease values and confidence interval measures.

---

# 📌 Business Recommendations

- Prioritize healthcare resources for regions with higher disease burden.
- Strengthen preventive healthcare and public awareness initiatives.
- Develop targeted interventions for vulnerable demographic groups.
- Improve healthcare data quality and reporting consistency.
- Support evidence-based public health planning through continuous data monitoring.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

# ✅ Conclusion

This project successfully demonstrates the application of Python-based data analytics techniques to analyze the U.S. Chronic Disease Indicators dataset. Through systematic preprocessing, feature engineering, exploratory data analysis, statistical evaluation, and visualization, the project identifies meaningful healthcare trends and demographic variations. The insights generated can assist public health organizations in evidence-based planning, resource allocation, and policy development.



**Python Data Analytics Project**
