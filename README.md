# Exploring-Salary-Determinants-in-Remote-Work
Uncovering the Drivers of High-Paying Remote Jobs: A Principal Component Analysis Approach
# TABLE OF CONTENT
-Overview
-Description
-Project Objective
-Key Areas Analyzed
-Data Source
-Data Description
-Tools and Method Used
-
---

#🎛Overview

This project analyzes the factors contributing to the high remote salary job
---
#💎Description
This project uses Principal Component Analysis (PCA) to explore the key factors that contribute to high-paying remote jobs. By analyzing a dataset of salaries, job roles, company affiliations, industries, and job types, the project aims to reduce dimensionality and uncover hidden patterns driving compensation in remote positions.

Through PCA, I identify which variables contribute the most to salary variation, helping us answer:

What job titles and experience levels are commonly associated with high pay?

How do company and industry types influence compensation?

What insights can be drawn from the structure of the data?

---
#🎯 Project Objective
The objective of this project is to identify the key factors that define high-paying remote jobs by applying Principal Component Analysis (PCA) to a dataset containing salary, company, industry, job title, employment type, and other related features.

---

#📊 Key Areas Analyzed
This project focused on the following core areas using PCA:

Annual Salary Patterns: Explored how salary levels vary across job roles, companies, and employment types.

Job Titles: Assessed the influence of specific roles (e.g., Data Scientist, Software Engineer) on salary distribution.

Company Influence: Compared salary trends across major tech companies (e.g., Google, Meta, Amazon).

Employment Type: Analyzed the impact of full-time, part-time, and contract roles on compensation.

Experience Level: Examined how entry-level, mid-level, and senior-level roles contribute to salary variation.

Remote Flexibility: Investigated the role of work setting (onsite vs. remote) in salary outcomes.

Industry Sectors: Compared salary differences across industries like Tech, Healthcare, and Retail.

---

#🎹Data Source
🗂️ Data Source
The dataset used for this analysis was downloaded from Kaggle. It contains detailed information on tech salaries, including job titles, companies, experience levels, employment types, industries, and remote work flexibility.

---

#📊 Data Description
The dataset contains the following variables:

Company: The organization where the employee works (e.g., Google, Meta, Amazon).

Job_Title: The professional title of the individual (e.g., Data Scientist, Software Engineer, Product Manager).

Industry: The sector or domain in which the company operates (e.g., Tech, Healthcare, Retail).

Employment_Type: The nature of the employment contract (e.g., Full-time, Part-time, Contract).

Experience_Level: The level of professional experience (e.g., Entry, Mid, Senior).

Remote_Flexibility: The flexibility of the work arrangement (e.g., Remote, Hybrid, Onsite).

Annual_Salary: The annual compensation received by the employee in U.S. Dollars (USD).

---

#Tool Used:
Language: Python
Libraries: (Pandas, Numpy, sklearn, matplotlib, Seaborn)
Jupyter Notebook

---


#📊 Methods Used:
Data Cleaning and Preprocessing

One-Hot Encoding of Categorical Variables

Standardization

Principal Component Analysis (PCA)

Scree Plot and Explained Variance

Loadings Interpretation

---

#💡 Key Insights
The first principal component (PC1) is highly influenced by Annual Salary, suggesting it captures overall pay level.

Experience Level, Job Title, and Remote Flexibility also contribute significantly.

PCA reduced the dataset to 25 components, explaining 95% of the total variance — allowing efficient visualization and clustering.







