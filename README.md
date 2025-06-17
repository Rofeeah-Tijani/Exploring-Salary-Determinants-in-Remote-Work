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
-Key Insight
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
 #Descriptive Statistics Of The Numerical Variable
      Annual_Salary
count     500.000000
mean    91583.001369
std     66189.317251
min       401.275080
25%     41203.776000
50%     89840.809650
75%    138337.079850
max    253907.594800


#PCA

Number of components explaining 95% variance: 25
Explained Variance Ratio:
 [1.77097953e-01 6.42772640e-02 5.62838784e-02 5.00775181e-02
 4.74559612e-02 4.71351735e-02 4.53230055e-02 4.31414852e-02
 4.06062797e-02 3.61312032e-02 3.20635943e-02 3.07370146e-02
 2.96137355e-02 2.81669008e-02 2.76845223e-02 2.64991625e-02
 2.56294212e-02 2.47467311e-02 2.22786103e-02 1.86809703e-02
 1.76116215e-02 1.75160294e-02 1.69214832e-02 1.63325653e-02
 1.55199028e-02 1.52565652e-02 1.41252405e-02 1.30862078e-02
 2.18568058e-17 3.05350169e-18 2.75030512e-18 0.00000000e+00
 0.00000000e+00 0.00000000e+00]

 #Top and Below 10 features driving PC1 and PC2
 PC1	PC2
Annual_Salary	0.991378	0.014153
Employment_Type_Full-time	-0.046372	-0.069572
Experience_Level_Entry	0.046292	-0.084118
Remote_Flexibility_Onsite	0.039162	-0.268310
Job_Title_Data Scientist	0.038937	-0.062894
Employment_Type_Contract	0.031432	0.046995
Experience_Level_Mid	-0.031409	0.015918
Employment_Type_Part-time	0.030848	0.067539
Industry_Healthcare	-0.029926	0.013224
Company_Meta	-0.028311	0.018509

PC1	PC2
Company_Netflix	0.010328	-0.003896
Company_Adobe	0.009381	0.026805
Company_Amazon	-0.008303	-0.063136
Experience_Level_Senior	0.006005	-0.072624
Job_Title_Software Engineer	0.005598	0.049787
Industry_Tech	0.004264	0.027753
Company_IBM	0.002398	0.023129
Industry_Retail	0.001369	-0.118126
Job_Title_UX Designer	0.000609	-0.076792
Job_Title_Product Manager	-0.000387	0.09158

---

#💡 Key Insights

The first principal component (PC1) is highly influenced by Annual Salary, suggesting it captures overall pay level.

Experience Level, Job Title, and Remote Flexibility also contribute significantly.

PCA reduced the dataset to 25 components, explaining 95% of the total variance — allowing efficient visualization and clustering.



 





