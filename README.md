📊 Hospital Data Analysis — SQL Project

This project contains a comprehensive SQL script with 34 queries designed to analyze hospital-related datasets, including Admissions, Doctors, Patients and Province_Names.
The goal is to demonstrate SQL proficiency across multiple levels — Basic, Intermediate, and Advanced — while deriving meaningful insights from medical records.

🧰 Technologies Used

SQL (MySQL Workbench)

Relational database concepts (Joins, Grouping, Aggregation)

Data cleaning & transformation techniques

🗂️ Query Classification (Basic → Intermediate → Advanced)

Below is the classification of all 34 queries from the SQL script into three levels based on complexity and operational use.

🟦 1. BASIC LEVEL QUERIES

These queries focus on simple filtering, selecting, ordering, and basic conditions.
| Query No. | Description                                         |
| --------: | --------------------------------------------------- |
|     **1** | Select basic patient details based on gender        |
|     **2** | Identify patients without allergies (NULL cleaning) |
|     **3** | Names starting with a specific letter               |
|     **4** | Weight-based filtering using `BETWEEN`              |
|     **5** | Updating NULL values with defaults                  |
|     **6** | Concatenate first and last names                    |
|     **7** | Basic JOIN to show province names                   |
|     **8** | Count patients born in a specific year              |
|     **9** | Patient with the maximum height                     |
|    **10** | Retrieve specific IDs using `IN`                    |
|    **11** | Total number of admissions                          |
|    **12** | Same-day admission & discharge records              |
|    **13** | Count admissions for a specific patient             |
|    **14** | Unique city names for a province                    |
|    **15** | Filtering using multiple conditions                 |
|    **16** | Unique birth years (DISTINCT + ORDER)               |
|    **17** | First names that occur only once                    |
|    **18** | Pattern matching with `LIKE`                        |

🟩 2. INTERMEDIATE LEVEL QUERIES

These queries apply grouping, aggregation, conditional logic, ordering by derived fields, and simple joins.
| Query No. | Description                                         |
| --------: | --------------------------------------------------- |
|    **19** | Join Patients & Admissions to filter a diagnosis    |
|    **20** | Order names by character length                     |
|    **21** | Male vs Female counts using CASE WHEN               |
|    **22** | Patients admitted multiple times for same diagnosis |
|    **23** | City-wise patient counts with sorting               |
|    **24** | Combine Patients + Doctors using `UNION ALL`        |
|    **25** | Allergy popularity analysis                         |
|    **26** | Date range filtering for 1970s                      |
|    **27** | Format full names using UPPER/LOWER + CONCAT        |
|    **28** | Sum of heights per province (HAVING clause)         |
|    **29** | Weight range analysis using MAX – MIN               |
|    **30** | Admissions per day of month                         |
|    **31** | Group patients by weight groups                     |
|    **32** | Calculate obesity boolean using BMI formula         |

🟥 3. ADVANCED LEVEL QUERIES

These involve multiple-table joins, conditional logic, grouping logic, and creating computed fields for secure data processes.
| Query No. | Description                                                             |
| --------: | ----------------------------------------------------------------------- |
|    **33** | Multi-table join (Patients + Admissions + Doctors) with dual conditions |
|    **34** | Generate temporary passwords combining ID + name length + birth year    |

📘 Key Concepts Demonstrated

| Category                     | Concepts Demonstrated |
|-----------------------------|------------------------|
| **Data Retrieval**          | SELECT statements, ordering, filtering, pattern matching (LIKE), DISTINCT usage |
| **Data Cleaning**           | Handling NULL values, updating missing fields, replacing placeholders (e.g., allergies) |
| **Aggregations**            | COUNT, SUM, MAX, MIN, GROUP BY, HAVING, derived groupings (weight brackets) |
| **Date Operations**         | Filtering by year, decade, extracting day from date, sorting by date ranges |
| **String Manipulation**     | CONCAT, CONCAT_WS, UPPER, LOWER, LENGTH, custom formatting of names |
| **Conditional Logic**       | CASE WHEN expressions, Boolean flags (e.g., obesity) |
| **Joins & Relationships**   | INNER JOIN across Patients, Doctors & Admissions tables, multi-table joins |
| **Advanced Filtering**      | Pattern rules (start-end characters, specific lengths), multiple conditions |
| **Union Operations**        | UNION ALL to combine patient & doctor records |
| **Analytical Scenarios**    | City segmentation, diagnosis history, admission frequency analysis |
| **Mathematical Calculations** | BMI formula using POWER & arithmetic operations |
| **Security Logic**          | Temporary password generation using concatenation of fields |


