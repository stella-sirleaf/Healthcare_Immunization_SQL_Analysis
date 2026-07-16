# Healthcare_Immunization_SQL_Analysis
SQL Healthcare Analytics Capstone analyzing immunization programme performance across Asia using PostgreSQL and pgAdmin 4.

Project Overview

This project analyzes immunization programme performance across Asian countries using SQL. The objective was to answer key public health business questions by querying relational data stored in PostgreSQL.

Tools Used
PostgreSQL
pgAdmin 4
SQL
Dataset

The project uses two related tables.

Countries

Contains:

Country ID
Country Name
Region
Population (Millions)
Immunization Records

Contains:

Record ID
Country ID
Vaccine Name
Vaccinations Given
Report Year

The tables are linked through country_id.

Business Questions

The project answers the following questions:

Which vaccine was administered the most?
Which countries administered the highest number of vaccinations?
Which regions administered more than 500,000 vaccine doses?
Which vaccine was administered the least?
Which countries recorded the highest average number of vaccinations per report?

SQL Skills Demonstrated
SELECT
INNER JOIN
GROUP BY
SUM()
AVG()
HAVING
ORDER BY
LIMIT
Key Insights
Influenza recorded the highest vaccination count.
SQL joins were used to combine country information with immunization records.
Aggregate functions identified high-performing countries and regions.
The analysis demonstrates how SQL supports evidence-based public health decision-making.
Project Structure
Healthcare_Immunization_SQL_Analysis/
│
├── Immunization_Programme_Capstone.sql
├── Healthcare_Analysis_SQL_Capstone.pdf
├── README.md
└── Images/


Author

Stella Sirleaf

Healthcare Data Analytics Portfolio
