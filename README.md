# Exploratory Data Analysis (EDA) & Business Intelligence

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) and Business Intelligence on a customer sales dataset. The goal was to uncover meaningful patterns, answer business questions using SQL, and propose a KPI-based dashboard structure.

This task builds on the cleaned dataset prepared in Task-1 (Data Immersion & Wrangling).

---

## Project Objectives

The objectives of this project were to:

- Perform descriptive statistics and univariate analysis  
- Visualize data distributions using charts  
- Answer business-driven questions using SQL  
- Explore relationships between multiple variables  
- Design a static dashboard mock-up with key metrics  

---

## Dataset Description

The dataset contains customer demographic and transaction information:

| Column Name       | Description                        |
|------------------|------------------------------------|
| Customer_ID      | Unique customer identifier         |
| Customer_Age     | Age of the customer                |
| Gender           | Customer gender                    |
| City             | Customer location                  |
| Purchase_Date    | Date of transaction                |
| Purchase_Amount  | Amount spent per transaction       |

---

## 1. Descriptive Statistics & Univariate Analysis

Using Python (Pandas), I calculated:

- Mean, minimum, and maximum purchase amount  
- Standard deviation of spending  
- Frequency distribution of cities  
- Gender distribution  

Visualizations created:

- Histogram for Purchase Amount  
- Bar chart for City distribution  
- Bar chart for Gender distribution  

These analyses helped in understanding spending patterns and customer distribution.

---

## 2. SQL for Business Questions

The dataset was converted into a SQL table using SQLite to simulate real-world business analysis.

### Business Questions Answered:

1. What are the top 5 cities by total revenue?  
2. What is the average purchase amount by gender?  
3. What is the monthly revenue trend?  
4. Which city has the highest number of customers?  
5. Which age groups contribute the highest revenue?  

SQL concepts used:

- SUM(), AVG(), COUNT()  
- GROUP BY  
- ORDER BY  
- Date-based grouping  
- Filtering and aggregation  

All SQL queries and outputs are included in this repository.

---

## 3. Multivariate Analysis & Correlation

To explore relationships between variables, the following were created:

- Scatter plot (Customer Age vs Purchase Amount)  
- Correlation matrix  
- Pairwise analysis of numerical features  

This helped identify relationships between age and spending behavior. 

---

## Tools & Technologies Used

- Python  
- Pandas  
- SQLite (SQL)  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- Excel / PowerPoint  

---

## Repository Structure

- EDA_notebook.ipynb  
- SQL_queries.sql  
- dashboard_mockup.ppt  
- README.md  

---

## Key Learnings

Through this project, I gained practical experience in:

- Data exploration and visualization  
- SQL-based business analysis  
- Correlation and relationship analysis  
- KPI identification and dashboard planning  
- Connecting data insights to business decisions  

---

## Author

Arshiya Ruksar  

Completed as part of the ApexPlanet Internship – EDA & Business Intelligence Module.
