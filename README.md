📊 Hospital Data Analysis — SQL Project

This project contains a comprehensive SQL script with 34 queries designed to analyze hospital-related datasets, including Admissions, Doctors, Patients and Province_Names.
The goal is to demonstrate SQL proficiency into Three Levels  — Basic, Intermediate, and Advanced — while deriving meaningful insights from medical records.

🧰 Technologies Used :

SQL (MySQL Workbench)

Relational Database Concepts (Joins, Grouping, Aggregation)

Data Cleaning & Transformation Techniques

🗂️ Query Classification (Basic → Intermediate → Advanced) :

Below is the classification of all 34 Queries from the SQL Script into Three Levels based on Complexity and Operational Use.

🟦 1. BASIC LEVEL QUERIES :

These Queries focus on Simple Filtering, Selecting, Ordering, and Basic Conditions.
| Query No. | Description                                         |
| --------: | --------------------------------------------------- |
|     **1** | Select basic Patient details based on Gender        |
|     **2** | Identify Patients without Allergies (NULL cleaning) |
|     **3** | Names starting with a Specific Letter               |
|     **4** | Weight-Based Filtering using `BETWEEN`              |
|     **5** | Updating NULL values with Defaults                  |
|     **6** | Concatenate First and Last Names                    |
|     **7** | Basic JOIN to show Province Names                   |
|     **8** | Count Patients born in a Specific Year              |
|     **9** | Patient with the Maximum Height                     |
|    **10** | Retrieve Specific IDs using `IN`                    |
|    **11** | Total Numbers of Admissions                          |
|    **12** | Same-Day Admission & Discharge Records              |
|    **13** | Count Admissions for a Specific Patient             |
|    **14** | Unique City Names for a Province                    |
|    **15** | Filtering using Multiple Conditions                 |
|    **16** | Unique Birth-Years (DISTINCT + ORDER)               |
|    **17** | First Names that occur only Once                    |
|    **18** | Pattern matching with `LIKE`                        |

🟩 2. INTERMEDIATE LEVEL QUERIES :

These Queries apply Grouping, Aggregation, Conditional Logic, Ordering by Derived Fields, and Simple Joins.
| Query No. | Description                                         |
| --------: | --------------------------------------------------- |
|     **19** | Join Patients & Admissions to Filter a Diagnosis    |
|     **20** | Order Names by Character Length                     |
|     **21** | Male vs Female Counts using CASE WHEN               |
|     **22** | Patients admitted Multiple Times for same Diagnosis |
|     **23** | City-Wise Patient Counts with Sorting               |
|     **24** | Combine Patients + Doctors using `UNION ALL`        |
|     **25** | Allergy Frequency Analysis                          |
|     **26** | Date range Filtering for 1970s                      |
|     **27** | Format Full Names using UPPER/LOWER + CONCAT        |
|     **28** | Sum of Heights per Province (HAVING clause)         |
|     **29** | Weight-Range Analysis using MAX – MIN               |
|     **30** | Admissions Per-Day of Month                         |
|     **31** | Group Patients by Weight Groups                     |
|     **32** | Calculate Obesity Boolean using BMI Formula         |

🟥 3. ADVANCED LEVEL QUERIES :

These involve Multiple-Table Joins, Conditional Logic, Grouping Logic, and creating Computed Fields for Secured Data Processes.
| Query No. | Description                                                             |
| --------: | ----------------------------------------------------------------------- |
|    **33** | Multi-Table Join (Patients + Admissions + Doctors) with Dual Conditions |
|    **34** | Generate Temporary Passwords combining ID + Name Length + Birth Year   |

📘 Key Concepts Demonstrated :

| Category                     | Concepts Demonstrated |
|-----------------------------|------------------------|
| **Data Retrieval**          | SELECT Statements, Ordering, Filtering, Pattern Matching (LIKE), DISTINCT Usage |
| **Data Cleaning**           | Handling NULL Values, Updating Missing Fields, Replacing Placeholders (e.g., Allergies) |
| **Aggregations**            | COUNT, SUM, MAX, MIN, GROUP BY, HAVING, Derived Grouping (Weight Brackets) |
| **Date Operations**         | Filtering by Year, Decade, Extracting Day from Date, Sorting by Date-Range |
| **String Manipulation**     | CONCAT, CONCAT_WS, UPPER, LOWER, LENGTH, Custom Formatting of Names |
| **Conditional Logic**       | CASE WHEN Expressions, Boolean Flags (e.g., Obesity) |
| **Joins & Relationships**   | INNER JOIN across Patients, Doctors & Admissions Tables, Multi-Table Joins |
| **Advanced Filtering**      | Pattern Rules (Start-End Characters, Specific Lengths), Multiple Conditions |
| **Union Operations**        | UNION ALL to combine Patient & Doctor Records |
| **Analytical Scenarios**    | City Segmentation, Diagnosis History, Admission Frequency Analysis |
| **Mathematical Calculations** | BMI Formula using POWER & Arithmetic Operations |
| **Security Logic**          | Temporary Password Generation using Concatenation of Fields |

🙌 Acknowledgements :

This Project was developed using the dataset provided by Datamites Internship Team and MySQL Workbench to provide Insights for Job Seekers, Recruiters, and Policy Makers.

👉 Here is the complete link of the SQL Script of the Queries : https://github.com/ARPAN-BIANALYST21/SQL_HOSPITAL_DATA_ANALYSIS/blob/5d2bbecb4632412439cd654fb2cffb1dd7664277/HOSPITAL_DATA_ANALYSIS.sql
