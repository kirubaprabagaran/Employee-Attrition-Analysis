# **📊 Employee Attrition Analysis**


**📝 Project Overview**
Employee attrition is a critical challenge for organizations, leading to high replacement costs and loss of institutional knowledge. This project analyzes a comprehensive Human Resources dataset to uncover the primary drivers of employee turnover. By examining demographic, behavioral, and compensation patterns, this analysis provides actionable business recommendations to improve retention strategies.

**🛠️ Tools & Technologies Used**<br>

**Python (Jupyter Notebook)**: Data Validation, Cleaning, and Exploratory Data Analysis (EDA) using pandas, matplotlib, and seaborn.<br>
**Power BI**: Data modeling, DAX measure creation, and interactive dashboard design.<br>
**Markdown**: Documentation and business reporting.

**🗂️ Dataset Description**

The dataset contains employee records detailing demographics, job roles, satisfaction scores, and performance metrics.<br>
**Initial Shape**: 1470 rows, 35 columns.<br>
**Data Cleaning Performed**: Verified 0 missing values and 0 duplicate rows. Dropped zero-variance columns (EmployeeCount, Over18, StandardHours) to optimize the dataset for analysis

**📈 Key Dashboard Features & KPIs**<br>
An interactive executive dashboard was built to track high-level metrics and segment attrition trends:<br>

Core KPIs: Total Employees (1,470), Active Employees (1,233), Inactive Employees (237), and an overall Attrition Rate of 16.12%.<br>

Demographic Segmentation: Attrition filtered by Gender, Age Bins, and Education Field.<br>

Job Role & Satisfaction Matrix: A cross-tabular view of departing employees by their specific roles and self-reported job satisfaction levels.<br>

Behavioral & Compensation Analysis: Visualizations highlighting attrition by Salary Slabs (binned in 2500 increments), OverTime status, and Work-Life Balance ratings.<br>

**💡 Key Business Insights**<br>
The Overtime Burden: 54% of all departing employees were working regular overtime, indicating that workload burnout is a disproportionate driver of turnover.<br>

The Work-Life Balance Paradox: The highest volume of attrition occurred among employees who rated their work-life balance a "3" (Better), demonstrating that flexible scheduling alone cannot retain talent if other factors (like compensation or career growth) are lacking.<br>

Experience Flight Risks: A significant spike in attrition occurs during the early years of an employee's tenure, which tapers off dramatically as they gain more experience.<br>

**📂 Repository Structure**<br>
/data/ - Contains the raw and cleaned HR datasets.<br>

/notebooks/ - Employee_Attrition_Analysis.ipynb containing the Python EDA and Data Cleaning steps.<br>

/dashboard/ - The Power BI .pbix file containing the interactive visualizations.<br>

/docs/ - Data Dictionary and the Final Business Insights & Recommendations Report.<br>

**🚀 How to Use**<br>
Clone this repository to your local machine.<br>

Open the Jupyter Notebook in the /notebooks/ folder to view the initial data exploration.<br>

Open the .pbix file in Power BI Desktop to interact with the dashboard. (Ensure the data source path is updated to your local /data/ directory if necessary).
