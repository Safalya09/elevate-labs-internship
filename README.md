#elevate-labs-internship 
#  Netflix Data Cleaning - Elevate Labs Internship Task 1

##  Task Summary
Cleaned the Netflix Movies and TV Shows dataset using Excel. Handled missing values, standardized column names, removed duplicates, and ensured proper data formatting.

##  Files
- `netflix_cleaned.xlsx`: Cleaned dataset
- `README.md`: This documentation

## Key Cleaning Steps
- Replaced all blank cells with "Not Available"
- Removed duplicate rows using Excel’s “Remove Duplicates”
- Standardized inconsistent fields (e.g., duration in rating column)
- Renamed column headers to lowercase with underscores
- Fixed data types for dates and numbers

##  Interview Questions & Answers

1. What are missing values and how do you handle them?  
Missing values are gaps in data where no information is provided. I replaced them with "Not Available" using Excel Find & Replace feature.

2. How do you treat duplicate records?  
 I used “Remove Duplicates” under the Data tab to eliminate repeated rows.

3. Difference between dropna() and fillna() in Pandas?  
- dropna() removes rows or columns with null values.  
- fillna() fills nulls with a specified value like “0” or “Not Available”.

4. What is outlier treatment and why is it important?  
Outlier treatment removes or adjusts unusually high or low values to prevent skewed analysis.

5. Explain the process of standardizing data.  
Standardization means making data consistent, such as fixing text formats .

6. How do you handle inconsistent data formats (e.g., date/time)?
I formatted date fields in Excel to `dd-mm-yyyy` using Format Cells, ensuring all entries matched the format.

7. What are common data cleaning challenges?  
- Inconsistent formats  
- Blank or null cells  
- Duplicates  
- Unexpected data types  

8. How can you check data quality?**  
By reviewing for completeness, consistency, accuracy, and uniqueness by using tools like filters, data validation, and conditional formatting help in Excel.

