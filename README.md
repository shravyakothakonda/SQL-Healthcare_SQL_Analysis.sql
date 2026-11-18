Healthcare SQL Analytics Project
Overview
This project demonstrates the use of SQL to analyze a healthcare dataset containing 55,500 patient records.

SQL Queries
Total Patients
SELECT COUNT(*) AS Total_Patients
FROM Patients;*```

### Average Age

```sql
SELEC* AVG(Age) AS Average_A*e
FROM Patients;
Medical *ondition Distribution
SELECT Medical_Condition,
       COUNT(*) AS Patient_Count
FROM Patients
GROUP BY Medical_Condition
ORDER BY Patient_Count DESC;
Gender Distribution
SELECT Gender,
       COUNT(*) AS Patient_Count
FROM Patients
*ROUP BY Gender;
*## Admission Type Analysis

       COUNT(*) AS Admission_Count
FROM Patients
GROUP BY Admission_Type
ORDER BY Admission_Count DESC;
Findings
Arthritis was the most common medical condition.
The dataset contained 55,500 patient records.
Elective admissions were the most common admission type.
Obesity had the highest average billing amount.
Skills Demonstrated
SQL
Healthcare Analytics
Data Analysis
Business Intelligence
