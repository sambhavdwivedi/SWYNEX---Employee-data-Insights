# SWYNEX---Employee-data-Insights
cleaning messy data of emplyees in an organization,performing EDA to gain insights.

# Employee Data Insights – End-to-End Data Analytics Project

## Project Overview

This project is an end-to-end **Employee Data Analytics** case study focused on transforming a raw and messy employee dataset into meaningful business insights.

The project follows a complete data analytics workflow, starting with data cleaning and preparation in **Python/Jupyter Notebook**, followed by exploratory data analysis and visualization, and finally the development of an interactive **Power BI dashboard**.

The objective is to understand employee demographics, salary patterns, department performance, remote-work distribution, and city-wise workforce distribution, while presenting the findings in a professional and interactive format.

---

# Project Workflow

Raw CSV Dataset
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Power BI Dashboard
        ↓
Final Analytics Case Study

---

# Task 1 – Data Cleaning & Preparation

### Objective

Clean and prepare the raw employee dataset so that it can be reliably used for analysis and visualization.

### Work Performed

The raw CSV dataset was imported into **Jupyter Notebook using Python and Pandas**.

The dataset was inspected to understand:

- Dataset structure
- Columns and data types
- Missing or inconsistent values
- Employee-related attributes
- Salary and performance information
- Department and city information
- Remote-work information

The data was then cleaned and prepared for further analysis.

### Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

### Output

A cleaned and analysis-ready employee dataset was prepared for Exploratory Data Analysis and Power BI.

---

# Task 2 – Exploratory Data Analysis

### Objective

Explore the cleaned dataset and identify useful patterns, relationships, and business insights.

### Analysis Performed

The employee dataset was analyzed across multiple dimensions, including:

- Employee age distribution
- Department-wise salary
- Department-wise performance rating
- Employee distribution by city
- Remote vs non-remote employees
- High-performer percentage
- Overall salary patterns
- Workforce distribution across age groups

### Key Findings

The dataset contains **300 employees** with a median age of **42 years**.

Approximately **61.67% of employees are classified as high performers**, while **41% of employees work remotely**.

The overall average salary is approximately **$60K**.

Department-wise analysis shows differences in both salary and performance. Sales has an average performance rating of **3.8**, while its average salary is **$56,801**. The Unassigned department has the highest average salary at **$67,838**, with an average performance rating of **3.3**.

The workforce is mainly concentrated in the **31–60 age range**, with 119 employees between 31–45 and 121 employees between 46–60.

### Business Questions Explored

- How large is the workforce?
- What is the typical employee age?
- What percentage of employees are high performers?
- How many employees work remotely?
- Which departments have the highest and lowest average salaries?
- Which departments have the highest performance ratings?
- How is the workforce distributed across different age groups?
- Which cities have the highest employee concentration?
- How do salary and performance vary between departments?

### Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Task 3 – Interactive Dashboard

### Objective

Build a professional and interactive dashboard that converts the analyzed data into an easy-to-understand business reporting interface.

The final dashboard was developed using **Microsoft Power BI**.

### Dashboard KPIs

The dashboard provides key workforce metrics such as:

- Median Age: **42**
- High Performer Percentage: **61.67%**
- Total Employees: **300**
- Remote Employees: **41%**
- Average Salary: **$60K**

### Dashboard Visualizations

The dashboard includes:

- Average Salary by Department
- Total Employees by Age Group
- Total Employees by City and Remote Work
- Department-wise Average Salary
- Department-wise Average Performance Rating
- Department filters
- City filters
- Remote Work filters

### Interactive Features

Users can interact with the dashboard using filters for:

- Department
- City
- Remote Work Status

This allows users to explore the employee dataset from different business perspectives without manually analyzing the underlying data.

---

# Task 4 – Final Data Analytics Project

### Objective

Combine the complete workflow into a final end-to-end data analytics case study.

This project demonstrates how a raw employee dataset can be transformed into actionable business information through a structured analytics process.

### Complete Process

**1. Data Collection**

A raw employee CSV dataset was used as the starting point.

**2. Data Cleaning**

The raw data was inspected, cleaned, and prepared using Python and Jupyter Notebook.

**3. Exploratory Data Analysis**

The cleaned dataset was analyzed to identify workforce, salary, performance, demographic, and remote-work patterns.

**4. Business Insights**

The analysis was converted into meaningful business questions and answers to understand important workforce trends.

**5. Data Visualization**

The analyzed data was visualized using charts and graphs.

**6. Power BI Dashboard**

The final dataset and analytical results were used to create an interactive Power BI dashboard.

**7. Business Reporting**

The dashboard provides a consolidated view of employee demographics, salary, performance, location, and remote-work information.

---

# Key Business Insights

- The organization has **300 employees**.
- The median employee age is **42 years**.
- **61.67%** of employees are classified as high performers.
- **41%** of employees work remotely.
- The overall average salary is approximately **$60K**.
- The **Unassigned** department has the highest average salary at **$67,838**.
- **Sales** has the lowest average salary at **$56,801**.
- **Sales** has the highest average performance rating at **3.8**.
- The overall average performance rating is **3.6**.
- Employees aged **46–60** form the largest age group with **121 employees**.
- Employees aged **18–30** form the smallest age group with **60 employees**.
- The workforce shows noticeable differences in salary and performance across departments.

---

# Technology Stack

### Data Cleaning & Analysis
- Python
- Pandas
- NumPy
- Jupyter Notebook

### Data Visualization & Dashboard
- Microsoft Power BI

### Dataset
- CSV

---

# Project Structure

```text
Employee-Data-Analytics/
│
├── dataset/
│   └── employee_data.csv
│
├── notebook/
│   └── employee_data_analysis.ipynb
│
├── powerbi/
│   └── employee_data_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
