#  Employee Attrition Analysis & Prediction
**HR Analytics | IBM HR Dataset**

## Project Overview

Employee attrition is a critical challenge for organizations as it directly impacts productivity, cost, and workforce stability.  
This project analyzes employee attrition patterns and identifies key factors influencing employees leaving the organization using **Python (EDA & Machine Learning)** and an **interactive Power BI dashboard**.

The objective is to deliver **data-driven insights** that help HR teams understand attrition drivers and support informed workforce decisions.


## Tools & Technologies

- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

- **Jupyter Notebook:** Data analysis & modeling

- **Power BI:** Interactive dashboards & KPIs

- **GitHub:** Version control & project sharing

## Dataset

- **Source:** IBM HR Analytics Employee Attrition Dataset (Kaggle)

- **Records:** 1,470 employees

- **Target Variable:** Attrition (Yes / No)

## Analysis Workflow

**1. Data Cleaning & Preprocessing**

- Removed irrelevant columns
     
- Created attrition flag and meaningful buckets (age, salary, experience, tenure)

**2.Exploratory Data Analysis (EDA)**

- Demographic analysis (Age, Gender, Marital Status, Education)

- Compensation analysis (Monthly Income, Salary Buckets)

- Job & role analysis (Department, Job Role, Job Level)

- Experience & engagement analysis (Experience, Years at Company, Satisfaction, Work-Life Balance)

- Work conditions (Overtime, Business Travel, Distance from Home)
    
**3.Feature Engineering**

   - Bucket creation for continuous variables

   - Encoding categorical variables
  
**4.Predictive Modeling**

  - Logistic Regression

  - Random Forest Classifier

  - Model evaluation using Accuracy, ROC-AUC, Precision & Recall

**5.Visualization**

  - 3-page Power BI dashboard with slicers and KPIs

## Key Insights

  - Attrition is **highest among younger employees and freshers**

  - **Very low salary ranges** show significantly higher attrition

  - Employees working **overtime** have much higher attrition risk

  - **Entry-level job roles and lower job levels** experience more attrition

  - Higher **job involvement, satisfaction, and work-life balance** reduce attrition

  - Employees with **frequent business travel** are more likely to leave

## Machine Learning Summary**

- **Logistic Regression**

   - Accuracy: ~77%

   - ROC-AUC: ~0.80

   - Strong recall for attrition cases (useful for identifying at-risk employees)

- **Random Forest**

  - Accuracy: ~85%

  - Identified key drivers such as Monthly Income, Age, Experience, Overtime, and Satisfaction levels

## Power BI Dashboard

The Power BI dashboard consists of **three professional pages:**

**1. Executive Summary**

  - Total Employees

  - Employees Left vs Stayed

  - Attrition Rate (%)

  - Attrition by Age Group

  - Attrition by Salary Range

  - Attrition by Overtime

**2. Workforce & Job Analysis**

  - Attrition by Department

  - Attrition by Job Role

  - Attrition by Job Level

  - Attrition by Gender & Marital Status

**3. Experience & Engagement Analysis**

  - Attrition by Experience Bucket

  - Attrition by Years at Company

  - Attrition by Job Satisfaction

  - Attrition by Job Involvement

  - Attrition by Work-Life Balance

## Dashboard Preview

### Executive Summary
![Executive Summary](screenshots/page1_executive_summary.png)

### Workforce & Job Analysis
![Workforce Analysis](screenshots/page2_workforce_analysis.png)

### Experience, Engagement & Work Conditions
![Experience & Engagement](screenshots/page3_experience_engagement.png)


## Repository Structure

Employee-Attrition-EDA-ML-PowerBI/
│
├── data/              # Raw & cleaned datasets
├── notebooks/         # Jupyter notebook (EDA + ML)
├── power_bi/          # Power BI dashboard (.pbix)
├── screenshots/       # Dashboard screenshots
└── README.md

## Business Value
This project demonstrates how data-driven analysis can help HR teams:

 - Identify high-risk employee segments

 - Design targeted retention strategies

 - Reduce hiring and training costs

 - Improve employee engagement and satisfaction

## Author

**Gaurav Singh**

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning
