# 👥 HR Data Analysis using PowerBI

## 📊 Dashboard  

![dashboard](https://github.com/user-attachments/assets/33e29d01-6086-45bf-93e0-4c2aa4b49458)


## 🎯 Objective  

This project seeks to examine employee turnover patterns across multiple dimensions, including educational background, gender, tenure, compensation, and positions. One striking finding reveals medical degree holders leave at a rate of 31.6% - nearly six times higher than those with technical degrees at 5.6%. To develop targeted retention strategies, we need to investigate potential drivers like professional experience, pay scales, and lifestyle factors that may contribute to this disparity. The insights from this data will help the organization improve employee satisfaction, boost retention, and optimize workforce management.

## 🔍 EDA (Exploratory Data Analysis)  

- Conducted an initial assessment of dataset quality, including missing values and inconsistencies.  
- Identified key columns relevant to attrition analysis based on the project's objectives.  
- Standardized data by correcting inconsistencies (e.g., "travelRarely" → "travel_rarely") and ensuring proper data types.  

## 🔄 ETL (Extract Tranform Load)  

### Extract  
- Data was sourced from structured HR records in CSV format, containing employee attributes and historical attrition details.  

### Transform  
- Selected relevant columns that align with the project's objective of understanding attrition drivers.  
- Removed duplicates and handled missing values.  
- Standardized column names for consistency.  
- Corrected data inconsistencies (e.g., fixing typos in categorical values).  
- Transformed datasets into proper data types (e.g., date fields converted to Date format, numerical fields formatted correctly).  
- Removed unnecessary columns such as "YearsWithManager" that did not contribute to meaningful insights.  

### Load  
- The cleaned and transformed data was loaded into Power BI for interactive visualization and analysis.  

## 📈 Analysis  

###  Key Performance Indicators (KPIs):  
- Employee Count  
- Attrition Count  
- Attrition Rate  
- Average Years at Company  
- Average Age  
- Average Salary  

###  Attrition Analysis
- **Attrition by Education (Donut Chart) :** Life Sciences accounted for 41.22% of attrition.  
- **Attrition by Age (Column Chart) :** Employees aged 26-35 have the highest attrition rate (48.95%).  
- **Attrition by Years at Company (Line Chart) :** 1-year experience employees have the highest attrition (59 employees).  
- **Attrition by Salary (Column Chart) :** Employees earning up to $5K experience the highest attrition.  
- **Attrition by Job Role :** Laboratory Technicians have the highest attrition (62 employees).  
- **Attrition by Job Satisfaction Matrix :** Sales Executives report the highest dissatisfaction. 

## 💡 Insights  

- **Attrition Rate and Cost Analysis :** The overall attrition rate is 18.5%, exceeding the industry benchmark of 15%. Estimated annual turnover cost: $384,800 (based on a $5,200 cost per hire and 74 annual departures in a 400-employee company).  

- **Attrition by Department & Job Roles :** Marketing has the highest attrition rate at 25%. Software Developers show a 15% attrition rate, indicating a need for talent retention strategies.  

- **Tenure and Age Group Trends :** Employees within their first 2 years have a 22% attrition rate, stressing the need for better onboarding and early-career development. The 25-34 age group has the highest attrition rate (21%), warranting further investigation.  

## 📝 Suggestions  

- **Enhance Employee Retention Strategies :** Implement initiatives to boost job satisfaction, particularly in high-attrition roles like Laboratory Technicians.  

- **Improve Compensation and Benefits  :** Review salary structures, particularly for employees earning under $5K, to improve retention.  

- **Optimize Hiring & Onboarding Processes :** Reduce the time to replace employees by streamlining recruitment and onboarding.  

- **Focus on Employee Engagement :** Address job dissatisfaction through engagement programs and regular feedback mechanisms.  

- **Develop Retention Plans for High-Risk Groups :** Targeted retention strategies for employees in the 26-35 age group and those with 1-2 years of experience.  

- **Analyze Work-Life Balance :** Investigate whether workload and expectations contribute to high attrition in specific roles.       

---
