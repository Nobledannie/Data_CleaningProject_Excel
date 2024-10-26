# Data_CleaningProject_Excel
Excel_Data_Cleaning_Project
About Dataset
Has 6 columns: Students ID, First_Name, Last_Name, Age, Gender, Course, Enrollment_Date and Total_Payment

DataCleaning Process:
Used "text to column" to separate data into columns across the row using the delimiter "|" 
Some values in the "Course column" were not properly spelt, I used the Spelling function under the review tab to correct the spelling
The values in the "Total_Payment" column were not consistent, I made use of the "REPLACE" function to ensure the values all had the same Currency unit
by replacing the sign and space before the number with "$" sign and then convert the column to Currency.
I used the TRIM function to delete leading space across each column
