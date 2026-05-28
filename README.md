# Montgomery Fleet Equipment Analysis (IBM Certification Project)
Data cleaning and analysis of government fleet inventory using Excel/SQL-style pivot analysis.
------------------------------------------------------------------------------------------------------

! Overview
This project was completed as part of the IBM Data Analyst certification. 
The objective was to clean raw government fleet equipment data and perform structured analysis using Excel PivotTables.

The workflow followed a real-world data analyst process:
**Data Cleaning → Data Formatting → Pivot Table Analysis → Insights Generation**
-----------------------------------------------------------------------------------------------------

**Dataset**

The dataset contains government fleet equipment records, including:
- Department information
- Equipment class/type
- Equipment counts

Two versions:
- Raw, Uncleaned source data
- Cleaned, processed, and analysis-ready data
-----------------------------------------------------------------------------------------------------

**Data Cleaning Process**

The following steps were performed to clean the dataset:

Part 1
1. Column Formatting
- Adjusted column widths for readability

2. Missing Data Handling
- Identified and removed empty rows using filter functionality

3. Duplicate Removal
- Removed duplicate records using Excel duplicate detection tools

4. Data Quality Fixes
- Corrected spelling errors in dataset fields
- Removed unnecessary whitespace using Find & Replace (double spaces)

5. Department Field Correction
- Fixed split department names using Flash Fill
- Consolidated department names into a single column
- Removed redundant columns created during import

Part 2
1. Data Formatting
- Converted the dataset into an Excel Table for structured analysis

2. Summary Statistics (AutoSum)
Key metrics calculated for Equipment Count:

- SUM: Total equipment count
- AVERAGE: Mean equipment count
- MIN: Minimum value
- MAX: Maximum value
- COUNT: Total number of records

3. Created Pivot Tables

Pivot Table 1: Displays the sum of equipment count by department
- Department in Rows
- Equipment Count in Values (Sum)
- Sorted in descending order

Pivot Table 2
- Department as the main row field
- Equipment Class nested under Department
- Sorted and filtered to show the Transportation category


Pivot Table 3
- Equipment Class as the main row field
- Department nested underneath
- Focused analysis on the CUV category
----------------------------------------------------------------------------------------------------------


**Key Insights**
- Equipment distribution varies significantly across departments
- The transportation category is the most dominant classification
- CUV equipment shows concentrated usage across specific departments


**Tools Used**
- Microsoft Excel
- Pivot Tables
- Flash Fill
- Conditional Formatting
- AutoSum
- Data Cleaning Techniques


**Conclusion**
This project demonstrates end-to-end data cleaning and structured analysis using Excel. It reflects real-world data analyst tasks, including data preparation, transformation, and pivot-based reporting.
