# Data-Analytics-new-Projects
#HR Analytics Dashboard — Employee Attrition Analysis

What This Project Is About

I analyzed HR data to understand why employees leave a company and which departments are most affected. The goal was to turn raw employee data into clear insights that can help with workforce planning.

Tools Used
Python (pandas) — to clean and prepare the data
Jupyter Notebook — to run the cleaning code
Power BI — to build the dashboard and visuals
DAX — to create calculated measures like Attrition Rate %


Dataset
   HR Analytics Dataset by anshika2301 on Kaggle — view dataset here(https://drive.google.com/drive/folders/18mQalCEyZypeV8TJeP3SME_R6qsCS2Og)

It contains information on 1,480 employees including department, job role, tenure, salary, and whether they left the company. The dataset is licensed under CC0 (Public Domain), so it is free to use.

What I Did
    Cleaned the raw data in Python — removed duplicates, filled missing values, fixed data types, and dropped columns with no analytical value
    Exported the cleaned dataset and loaded it into Power BI

Built a dashboard with 5 visuals:
   Workforce Summary card (Total Headcount, Average Tenure, Attrition Rate)
   Headcount by Department
   Attrition Overview (donut chart)
   Attrition by Department
   Average Tenure by Job Role

Key Findings
   About 16% of employees left the company overall
   The Sales department had the highest attrition rate at around 20.6%, compared to 13.8% in R&D
   Sales Representatives had the shortest average tenure of any role at 2.93 years
   HR department also showed a high attrition rate at around 19%

Recommendation
   Since Sales Representatives leave the fastest and the Sales department has the highest turnover, it is worth investigating why. A good starting point would be exit interviews to understand the reasons, checking if pay is competitive with the market, and giving new hires more support in their first year on the job.
