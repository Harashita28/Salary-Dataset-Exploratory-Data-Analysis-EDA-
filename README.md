# Salary Dataset Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a salary dataset containing information about job roles, company ratings, salaries, locations, and employment status.

The objective of this analysis is to understand salary patterns, identify factors that may influence compensation, and investigate potential data quality issues within the dataset.

---

## Dataset Features

* Rating
* Company Name
* Job Title
* Salary
* Salaries Reported
* Location
* Employment Status
* Job Roles

---

## Business Questions

The analysis was conducted to answer the following questions:

1. Does company rating affect salary?
2. Does location affect salary?
3. Which job roles have the highest salaries?
4. Which job roles appear most frequently?
5. Are there any unusual salary values or outliers?
6. What insights can be derived from salary distribution?

---

## Analysis Performed

### Data Understanding

* Examined dataset structure and data types.
* Checked dataset dimensions and feature information.

### Data Cleaning

* Identified missing values.
* Checked duplicate records.
* Investigated inconsistencies in job titles.

### Univariate Analysis

* Salary distribution analysis.
* Rating distribution analysis.
* Frequency analysis of job titles and locations.

### Bivariate Analysis

* Salary vs Rating.
* Salary vs Job Role.
* Salary vs Location.
* Salary vs Employment Status.

### Correlation Analysis

* Correlation matrix for numerical features.
* Investigation of relationships between salary, rating, and salaries reported.

### Outlier Detection

* Identified extreme salary values.
* Investigated unusually high and low salary records.

---

## Key Findings

* 75% of salary records are below ₹9 LPA.
* The salary distribution is positively skewed.
* Company rating has very little correlation with salary.
* Bangalore contains the highest number of records in the dataset.
* Developer-related roles appear frequently, indicating strong demand.
* Significant variation exists across job titles and employment categories.

---

## Data Quality Issues Identified

During the analysis, several potential data quality concerns were discovered:

* Extremely high salary values that may represent reporting errors.
* Extremely low salary values that require validation.
* Inconsistent job title naming conventions.
* Repeated salary patterns across certain job categories.
* Possible aggregation issues within salary records.

These findings suggest that additional data cleaning would be required before using the dataset for advanced modeling or business decision-making.

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Conclusion

This project provided hands-on experience in exploratory data analysis, data validation, and business-oriented investigation of salary data. In addition to uncovering salary trends, the analysis highlighted the importance of identifying data quality issues before drawing conclusions from a dataset.
