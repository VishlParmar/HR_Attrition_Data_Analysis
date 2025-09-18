HR Attrition Data Analysis & Dashboard  

📌 Project Overview  
Employee attrition — the departure of employees from an organization — poses significant challenges for businesses, impacting productivity, morale, and financial performance.  

This project was conducted to analyze historical employee data and identify key drivers of attrition.  
By leveraging Excel, Python, and Power BI, the goal was to deliver actionable insights, build predictive indicators, and create dashboards to support data-driven HR decision-making.  

🎯 Project Purpose  
- Unlock actionable intelligence from raw HR data.  
- Identify key attrition factors such as job satisfaction, salary, work-life balance, and career growth.  
- Build predictive insights to forecast turnover likelihood.  
- Provide strategic recommendations for reducing attrition and improving employee engagement.  

📂 Dataset  
- Source: https://github.com/VishlParmar/HR_Attrition_Data_Analysis
- Records: 1471 employees  
- Columns Include: Age, Gender, Department, JobRole, MonthlyIncome, WorkLifeBalance, YearsAtCompany, Attrition (Yes/No), etc.  

🔧 Data Processing  

🧹 Data Cleaning & Transformation  
- Standardized categorical values (Department, Job Role).  
- Added a new calculated column `Attrition_Code` (`Yes` → 1, `No` → 0).  
- Handled missing values and ensured data consistency.  

📊 Key Performance Indicators (KPIs)  
- Total Employees  
- Employees Left
- Average Monthly Income  
- Average Age of Employees  

🖥 Tools & Technologies  

1. Microsoft Excel 
- Performed data cleaning, formatting, and pivot analysis.  
- Built an initial HR Attrition Dashboard with KPIs and charts.  
- Actions: Removing duplicates, applying conditional formatting, building Pivot Tables.  

2. Python (Jupyter Notebook)
- Libraries Used: Pandas, Matplotlib, Seaborn, Plotly  
- Steps Performed:  
  - Data loading & transformation  
  - Exploratory Data Analysis (EDA)  
  - Visualizations (histograms, bar charts, stacked charts, boxplots, etc.)  
- Example Insights: Higher attrition in younger employees & employees working overtime.  

3. Power BI  
- Created interactive dashboards with:  
  - Slicers (Gender, Department, Job Role, Education Field)  
  - KPI Cards (Total Employee, Leave Employee, Avg Monthly Income, Avg Age)  
  - Attrition by Department, Job Role, Overtime, and Work-Life Balance  
- Implemented DAX Measures:  
  - Attrition_Code formula  
  - Age Group bucketing  
  - Custom calculated KPIs  

📊 Insights & Findings  
- 42% of attrition occurred among employees with <2 years of tenure.  
- Research & Development had the highest attrition (133 employees left).  
- Employees who worked overtime showed higher attrition percentages.  
- Poor Work-Life Balance strongly correlated with higher attrition.  
- Lower Monthly Income groups had higher turnover rates.  

🚀 Business Impact  
- HR can design early retention programs for employees with <2 years tenure.  
- Focus on improving work-life balance policies to reduce attrition.  
- Salary benchmarking can reduce dissatisfaction among low-income employees.  
- Dashboards provide real-time monitoring for HR managers.  

📸 Dashboard Previews  
- Excel Dashboard (KPI Cards + Charts)  
- Python Visualizations (Histograms, Boxplots, Stacked Charts)  
- Power BI Dashboard (Interactive with slicers & DAX measures)  


🛠 Skills Demonstrated  
- Data Cleaning & Transformation (Excel, Python, SQL)  
- Exploratory Data Analysis (EDA)  
- Interactive Dashboarding (Power BI)  
- DAX Functions & KPI Creation  
- Business Insight Generation  
