# Human-Resource-Workforce-Performance---Training-Analytics

HR Workforce, Performance & Training Analytics

![Power-Bi](https://img.shields.io/badge/Tool-Power%20Business_Inteligence-217346?logo=power-Bi&logoColor=white)
![Dashboard](https://img.shields.io/badge/HR_Workforce,Performance_&_Training_Analytics%20Dashboard-blue)
![Data Analysis](https://img.shields.io/badge/Analysis-Data%20Visualization-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# Table of Contents

- Project Overview
- Project Objectives
- Workbook Structure
- Data Preparation and Cleaning
- Key Workforce Metrics
- WorkForce Analysis
- Gender Distribution
- Performance Analysis
- Employee Experience Analysis
- Training and Development Analysis
- Training Cost Analysis
- Tools & Techniques Used
- Project Limitations
- Recommendations
- Conclusion
- Author

---


📊 Project Overview
---
This project is an HR Workforce, Performance & Training Analytics solution built from an Excel dataset containing employee demographics, employment information, performance ratings, engagement and satisfaction measures, and training records.

The workbook is designed to support HR and management analysis across three major areas:

A) Workforce Analysis — employee headcount, employment status, employee types, departments, business units, pay zones, demographics, and tenure-related information.

B) Performance & Employee Experience Analysis — performance scores, employee ratings, engagement, satisfaction, and work-life balance.

C) Training & Development Analysis — training programs, training type, outcomes, duration, and training costs.

The workbook contains two worksheets:

Dirty Dataset — the original/raw dataset.

Cleaned Dataset — the analysis-ready version.

---
🎯 Project Objectives
---

The main objectives of this project are to:

1). Analyze the organization's workforce structure.

2). Monitor active versus terminated employees.

3). Understand employee composition by employment type and classification.

4). Examine workforce distribution across departments, divisions, business units, and pay zones.

5). Analyze employee performance levels.

6). Evaluate employee engagement, satisfaction, and work-life balance.

7). Assess the organization's training programs and training outcomes.

8). Analyze training duration and training expenditure.

9). Identify patterns that may help HR improve employee development and retention.

10). Provide a clean and structured dataset suitable for business intelligence reporting.

---
🗂️ Workbook Structure
---

---
Dataset Size
---

● Records: 2,845

● Columns: 28

● Missing values: 0 across the supplied fields

● Duplicate rows: 0 detected

● Start Date range: 2018-08-07 to 2023-08-06

● Survey Date range: 2022-08-05 to 2023-08-05

● Training Date range: 2022-08-05 to 2023-08-05

---
🧹 Data Preparation & Cleaning
---

The workbook provides both a raw and cleaned worksheet, making the data preparation stage transparent.

---
Cleaning checks performed
---

The cleaned dataset was reviewed for:

● Missing values

● Duplicate records

● Consistent column naming

● Date-field consistency

● Numeric-field consistency

● Categorical-field consistency

● Employee identifier integrity

● Training cost and duration fields

● Employee demographic and workforce attributes

---
Important structural change
---

The raw worksheet contains the field:

● StartDate

The cleaned worksheet standardizes this to:

● Start Date

The remaining field values in the supplied raw and cleaned worksheets are equivalent when compared row-by-row.


---
📈 Key Workforce Metrics
---

---
Based on the cleaned dataset:
---

● Total Employee Records

2,845

● Active Employees

2,458

● Terminated Employees

387

● Termination Rate

13.60%

● Average Employee Age

49.45 years

● Average Employee Rating

2.97 / 5

● Average Engagement Score

2.94 / 5

● Average Satisfaction Score

3.03 / 5

● Average Work-Life Balance Score

2.99 / 5

● Total Training Cost

$1,591,148.63

● Average Training Cost

$559.28

● Average Training Duration

2.97 days

---
👥 Workforce Analysis
---

---
Employee Status
---

The dataset contains:

● 2,458 Active employees

● 387 Terminated employees

● 13.60% termination rate

This metric is used as a high-level indicator of workforce stability.

---
Gender Distribution
---

● Female

1,588

● Male

1,257

Gender distribution was examined alongside department, employee type, performance, and employee experience metrics.

---
⭐ Performance Analysis
---

The Performance Score field contains four performance categories:

● Fully Meets

2,251

● Exceeds

346

● Needs Improvement

162

● PIP

86

-----
## performance questions

-----
1) What percentage of employees fully meet expectations?

2) Which departments have the highest share of Exceeds ratings?

3) Which departments have the highest concentration of Needs Improvement or PIP employees?

4) Does employee engagement correlate with performance?

5) Does training outcome appear to differ by performance category?

6) Are terminated employees concentrated in particular performance groups?

---
😊 Employee Experience Analysis
---

The dataset contains three employee-experience measures:

● Engagement Score

● Satisfaction Score

● Work-Life Balance Score

---
Average values in the supplied dataset are:
---

● Engagement Score

2.94 / 5

● Satisfaction Score

3.03 / 5

● Work-Life Balance Score

2.99 / 5

These measures were analyzed independently into an overall employee-experience indicator.

---
🎓 Training & Development Analysis
---

Training is represented through:

● Training Program Name

● Training Type

● Training Outcome

● Training Duration

● Training Cost

● Training Date

● Training Programs

● Training Program

---
Records
---

● Communication Skills

633

● Project Management

585

● Leadership Development

544

● Technical Skills

543

● Customer Service

540

● Training Type

---
The dataset contains:
---

● 1,421 Internal training records

● 1,424 External training records

---
Training Outcomes
---

● Completed

737

● Incomplete

731

● Passed

709

● Failed

668

---
💰 Training Cost Analysis
---

The dataset contains a Training Cost measure for each record.

---
Key cost metrics
---

Total training cost: $1,591,148.63

Average training cost: $559.28



---
Page 1 — WorkForce Overview 
---


<img width="895" height="504" alt="HR Workforce Overview" src="https://github.com/user-attachments/assets/241bf9fe-feaf-43f4-a38f-8f4b8ba887f1" />


---
KPIs
---

● Total Employees

● Active Employees

● Terminated Employees

● Average Age

● Average Engagement

● Slicers

● Male

● Female

---
Page 2 — Employee Performance & Engagement
---

<img width="898" height="504" alt="Employee Performance   Engagement" src="https://github.com/user-attachments/assets/6571639d-52c9-456c-ad7a-834635e1381f" />

---
KPIs
---

● Average Employee Rating

● Average Performance Score

---
Page 3 — Training & Development Analytics
---

<img width="890" height="502" alt="Training   Development Analysis" src="https://github.com/user-attachments/assets/c216bb23-457f-4476-b6c7-963ee55b9d51" />

---
KPIs
---

● Total Training Cost

● Employees Trained

● Average Training Duration

---
🔎 Business Questions This Project has Answered
---

---
Workforce
---

1) How many employees are currently active?

2) What percentage of employees have been terminated?

3) Which departments have the largest workforce?

4) What is the distribution of employee types?

5) What is the organization's average employee age?

---
Performance
---

1) What percentage of employees exceed expectations?

2) Which departments have the strongest performance?

3) Which departments have the highest performance risk?

4) How does employee rating vary across departments?

5) Is higher engagement associated with stronger performance?

---
Employee Experience
---
1) Which departments have the highest engagement?

2) Which groups report the lowest satisfaction?

3) Which departments have weaker work-life balance?

---
Training
---

1) Which training programs are most frequently used?

2) Which training programs cost the most?

3) Which programs have the highest completion or pass rates?

4) Does training outcome differ by department?

5) How much is being spent on training?

---
🛠️ Tools & Techniques Used
---

This project is primarily built around Microsoft Excel and the use of Power Business Intelligence for visualization.

● Microsoft Excel

● Power BI

---
Excel skills demonstrated
---

● Dax measures

● Data cleaning

● Data validation

● Sorting and filtering

● KPI calculations

● Conditional formatting

● Date analysis

● Percentage calculations

---
📌 Project Limitations
---

The following limitations were considered before using the dataset for formal HR decision-making:

● The accuracy of the analysis depends heavily on the quality of the underlying employee data. Missing values, inconsistent entries, duplicate records, or incorrect classifications could affect KPIs and visualizations.

● the dataset covers a relatively short period, it may not be sufficient to identify long-term workforce trends, employee performance patterns, or changes in training effectiveness.

● Performance scores are often influenced by managerial assessments and predefined evaluation criteria. Therefore, they may not fully capture an employee's actual productivity, potential, teamwork, creativity, or contribution to the organization.

● The dataset does not document the source organization or collection methodology.

● The Training Cost field does not specify its currency.

---
📈 Recommendations
---

● HR should investigate the factors associated with employee turnover, particularly across departments, job roles, tenure groups, and performance levels. Targeted retention initiatives such as career progression, recognition programs, workload reviews, and employee engagement activities can help reduce avoidable attrition.


● Training resources should be allocated based on identified skill gaps and employee performance. Rather than providing the same training to everyone, HR should prioritize departments and employee groups showing lower performance or higher development needs.

● The organization should establish a process for measuring whether training actually improves performance. Pre- and post-training performance indicators can be compared to determine which training programs deliver measurable value.

● Employees with consistently low performance scores should receive structured performance improvement plans, coaching, and regular feedback. High-performing employees should also be recognized and considered for additional responsibilities, promotions, or leadership development.

---
 ⭐ Conclusion
---

The HR Workforce, Performance & Training Analytics project provides a structured framework for analyzing employee demographics, workforce composition, performance, employee experience, and organizational training.

This project demonstrates practical HR Analytics and Business Intelligence skills rather than simple spreadsheet manipulation.



👨‍💻 Author

ABAYIM PRINCEWILL

Data Analyst | Excel | SQL | Power BI | Data Visualization

This project was developed as part of a data analytics portfolio to demonstrate practical skills in data cleaning, exploratory analysis, KPI development, workforce analytics, and business intelligence.

📄 Dataset

File: HR_Workforce,Performance & Training Analytics.xlsx

Primary analysis sheet: Cleaned Dataset

Records: 2,845

Fields: 28













