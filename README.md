## HR Analytics --- Employee Attrition & Workforce Dashboard

Project Overview

This project analyzes employee data to understand employee attrition,
workforce characteristics, job satisfaction, compensation, overtime,
work-life balance, and department-level trends.

The dashboard was built in Microsoft Power BI to transform HR data
into interactive KPIs and visual insights that can help HR teams
identify areas where employee retention may need attention.

 Business Problem

Employee attrition can increase recruitment costs, reduce productivity,
and affect team stability.

This project aims to answer questions such as:

What is the overall employee attrition rate?

Which departments and job roles have the highest attrition?

Does overtime relate to higher employee attrition?

Which age groups have higher attrition?

How does work-life balance relate to employee retention?

How do job satisfaction and compensation factors vary across
employees?

Which employee groups may require additional retention attention?

Tools & Technologies

Power BI --- Dashboard development and data visualization

Power Query --- Data preparation and transformation

DAX --- KPI and analytical measures

CSV --- Source dataset

Data Analysis --- Attrition and workforce analysis

 Dataset

The dataset contains 1,480 employee records and 37 attributes
covering areas such as:

Employee demographics

Department and job role

Attrition

Business travel

Overtime

Monthly income and salary slab

Job satisfaction

Environment satisfaction

Work-life balance

Job involvement

Performance rating

Total experience

Years at company

Years in current role

Years since promotion

Years with current manager

Training

Marital status

Data Preparation

The dataset was reviewed and prepared for analysis by checking:

Duplicate employee records

Missing values

Inconsistent category labels

Data types

Numeric and categorical fields

Attrition and workforce metrics

Data quality items identified

2 duplicate records were identified and should be removed before
the final published dashboard.

BusinessTravel contains both Travel_Rarely and TravelRarely;
these should be standardized into one category.

YearsWithCurrManager contains 61 missing values and should be
handled appropriately based on the analysis requirement.

Note: The Power BI dashboard should reflect these cleaning steps
before the final portfolio version is published.

Dashboard

The Power BI dashboard provides an interactive view of employee
attrition and workforce trends.

Key KPIs

Total Employees: 1,480

Active Employees: 1,239

Employees Lost to Attrition: 241

Overall Attrition Rate: 16.3%

Average Age: 36.9 years

Average Salary Hike: 15.2%

Average Total Experience: 11.3 years

Dashboard Analysis

The dashboard covers:

Department-wise attrition

Job role analysis

Salary slab analysis

Age-group analysis

Job satisfaction

Work-life balance

Overtime

Employee experience

Workforce distribution

Interactive filtering by department and employee characteristics

Dashboard Preview
![HR Analytics Dashboard](Screenshot%202026-08-19%20234016.png)



Key Insights

1. Overtime is strongly associated with attrition

Employees working overtime have an attrition rate of approximately
31.2%, compared with 10.4% among employees who do not work
overtime.

This suggests that workload and overtime should be investigated as
potential retention factors.

2. Attrition varies significantly by job role

The highest attrition rates are concentrated in several roles:

Job Role                  Attrition Rate

Sales Representative               40.5%
Human Resources                    25.9%
Laboratory Technician              23.6%
Sales Executive                    17.6%
Research Scientist                 16.4%

Sales Representatives have the highest attrition rate in the dataset.

3. Younger employees show higher attrition

The 18--25 age group has an attrition rate of approximately
36.6%, followed by the 26--35 group at 19.3%.

This indicates that early-career employees may require stronger
onboarding, career-development, engagement, and retention initiatives.

4. Attrition differs across departments

The highest department-level attrition rates are observed in:

Human Resources --- 26.8%

Sales --- 25.2%

Administration --- 20.7%

IT --- 17.8%

These departments can be prioritized for deeper investigation.

5. Marital status is associated with different attrition levels

Single employees have an attrition rate of approximately 21.7%,
compared with 11.5% among married employees.

This is an observed association in the dataset and should not be
interpreted as a direct cause of attrition.

