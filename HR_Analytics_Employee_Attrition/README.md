# 📊 HR Analytics — Employee Attrition & Performance

## 📌 Project Overview

This project analyzes employee data to understand **employee attrition, retention, compensation, satisfaction, career growth, and overtime patterns**.

The goal is to identify meaningful patterns in the workforce and translate them into **business insights that can help HR teams make better workforce and retention decisions**.

This project was built as part of my **Data Analytics learning journey**, using Python, Pandas, and Matplotlib.

---

## 🎯 Business Problem

Employee turnover can create significant challenges for organizations, including recruitment costs, productivity loss, and the need for continuous hiring and training.

The key questions explored in this project include:

* How many employees are leaving the organization?
* Which departments and job roles have higher attrition?
* Is overtime associated with higher employee turnover?
* How does salary vary across departments, roles, and job levels?
* Are satisfaction and work-life balance related to attrition?
* Does employee tenure differ between employees who stay and those who leave?
* What career-growth patterns can be observed?
* Which workforce factors should HR pay closer attention to?

---

## 📂 Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

The dataset contains information about **1,470 employees** and originally includes **35 features** covering areas such as:

* Employee demographics
* Department and job role
* Salary and compensation
* Job satisfaction
* Work-life balance
* Performance
* Overtime
* Training
* Career growth
* Employee tenure
* Attrition

### Data Cleaning

During preprocessing:

* Checked for missing values
* Checked for duplicate records
* Reviewed data types
* Examined categorical values
* Removed redundant/identifier columns that were not required for analysis

After cleaning, the dataset contained **1,470 rows and 31 columns**.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Matplotlib**
* Jupyter Notebook

### Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Aggregation
* GroupBy Analysis
* Data Filtering
* Statistical Summaries
* Categorical Analysis
* Data Visualization
* Business Insight Generation

---

# 🔎 Analysis Performed

## 1. 👥 Employee Overview

Analyzed:

* Total employees
* Employees who stayed vs. left
* Overall attrition rate
* Overtime percentage
* Average age
* Average monthly income

### Key Finding

The dataset contains **1,470 employees**, with an overall attrition rate of **16.12%**.

---

## 2. 👨‍💼 Employee Demographics

Analyzed:

* Gender distribution
* Department distribution
* Job roles
* Education fields
* Marital status
* Average age by department and gender

### Key Finding

**Research & Development** has the largest workforce, with **961 employees**.

---

## 3. 💰 Salary & Compensation Analysis

Analyzed:

* Average monthly income
* Minimum and maximum salary
* Salary by department
* Salary by job role
* Salary by job level
* Salary variation
* Average salary hike
* Salary hike by job role

### Key Findings

* Average monthly income is approximately **6,502.93**.
* Monthly income increases substantially with job level.
* Level 1 employees have an average monthly income of approximately **2,786.92**, while Level 5 employees average approximately **19,191.83**.
* Managers have the highest average monthly income among job roles.

---

## 4. 🚪 Attrition Analysis

Analyzed employee attrition based on:

* Gender
* Department
* Job role
* Job level
* Overtime
* Marital status
* Distance from home

### Key Finding

Attrition varies across different employee groups, indicating that employee turnover is not evenly distributed across the organization.

---

## 5. 😊 Employee Satisfaction & Performance

Analyzed:

* Job satisfaction
* Environment satisfaction
* Relationship satisfaction
* Work-life balance
* Job involvement
* Performance rating

Also compared satisfaction and work-life balance between employees who **stayed and left**.

### Key Finding

Employee experience varies across different workforce groups, making satisfaction and work-life balance useful areas for HR monitoring.

---

## 6. 🔄 Employee Retention Analysis

Analyzed retention based on:

* Department
* Job role
* Job level
* Overtime
* Business travel
* Marital status
* Employee tenure
* Current role
* Current manager
* Number of companies worked

### Key Findings

Overtime showed one of the strongest retention patterns:

* **No overtime:** 89.56% retention
* **Overtime:** 69.47% retention

Retention also varied significantly across job roles.

For example:

* **Research Director:** 97.50% retention
* **Sales Representative:** 60.24% retention

Employees who stayed also had higher average:

* Years at company: **7.37 vs. 5.13**
* Years in current role: **4.48 vs. 2.90**
* Years with current manager: **4.37 vs. 2.85**

---

## 7. 📈 Career Growth & Experience Analysis

Analyzed:

* Training frequency
* Years at company
* Years in current role
* Years since last promotion
* Years with current manager

### Key Findings

Employees who stayed received slightly more training on average:

* Stayed: **2.83 sessions**
* Left: **2.62 sessions**

However, the difference was relatively small.

Employee tenure and role/manager stability showed stronger retention patterns than training or time since promotion.

---

## 8. ⏰ Overtime & Work-Life Analysis

Analyzed:

* Overtime distribution
* Overtime percentage
* Salary by overtime status
* Job satisfaction by overtime status
* Work-life balance by overtime status
* Attrition by overtime status
* Overtime by department
* Overtime by job level
* Overtime by job role
* Total working experience by overtime status

### ⭐ Key Finding

Overtime employees had a significantly higher attrition rate:

**30.53% vs. 10.44%**

This represents a difference of approximately **20 percentage points**.

However, overtime employees did not have substantially lower job satisfaction:

* No overtime: **2.71**
* Overtime: **2.77**

Work-life balance was slightly lower among overtime employees:

* No overtime: **2.77**
* Overtime: **2.73**

This suggests that overtime is strongly associated with attrition in this dataset, but the relationship cannot be explained by average job satisfaction alone.

---

# 💡 Key Business Insights

### 1. Overtime is an important retention risk indicator

Employees working overtime had an attrition rate of **30.53%**, compared with **10.44%** for employees who did not work overtime.

### 2. Retention differs substantially across job roles

Some roles show much higher retention than others, suggesting that HR may need **role-specific retention strategies**.

### 3. Tenure and workplace stability are associated with higher retention

Employees who stayed generally had longer tenure at the company, more years in their current role, and more years with their current manager.

### 4. Compensation increases strongly with job level

Higher job levels are associated with substantially higher average monthly income, showing a clear relationship between career level and compensation.

### 5. Overtime exposure differs across job roles

Research Scientists had the highest overtime percentage at approximately **33.22%**, while Laboratory Technicians had the lowest at approximately **23.94%**.

---

# 🏢 Business Recommendations

Based on the observed patterns, HR could:

* Investigate workload and overtime patterns in roles with high overtime exposure.
* Review staffing and workload distribution to identify potential sources of excessive overtime.
* Develop targeted retention strategies for job roles with lower retention.
* Strengthen career development and progression opportunities.
* Monitor employee-manager stability and workplace relationships.
* Review compensation structures across job levels and roles.
* Use employee satisfaction and work-life balance metrics alongside attrition data when evaluating retention risks.

> **Important:** These recommendations are based on patterns observed in the dataset. The analysis identifies associations and does not establish that a particular factor directly causes employee attrition.

---

# 📊 Visualizations

The project includes Matplotlib visualizations covering:

* Employee attrition
* Employee distribution by department
* Overtime distribution

Additional visualizations can be developed as part of future iterations of the project.

---

# 📁 Project Structure

```text
HR-Analytics-Employee-Attrition/
│
├── HR_Analytics_Employee_Attrition.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md

```


# 🎓 What I Learned

This project helped me strengthen my practical understanding of:

* Cleaning and preparing real-world datasets
* Using Pandas for exploratory data analysis
* Performing group-based analysis
* Comparing different employee groups
* Identifying meaningful patterns in data
* Creating basic business visualizations
* Translating analytical results into business insights
* Understanding that correlation/association does not necessarily imply causation

Most importantly, I learned that **Data Analytics is not only about writing code — it is about using data to answer business questions and support better decisions.**

---

# 🔮 Future Improvements

Potential future improvements include:

* Creating a more comprehensive Matplotlib dashboard
* Adding interactive visualizations
* Building the analysis in Power BI
* Performing deeper statistical analysis
* Exploring predictive employee attrition modeling
* Adding additional HR metrics and KPIs

---

## 👩‍💻 Author

**Pallavi**

Aspiring Data Analyst | Python | Pandas | Data Visualization | Data Analytics

---

⭐ If you found this project useful, feel free to explore the repository and share your feedback.
