Montgomery County Fleet Equipment Inventory — Data Analysis

This repository contains a two-part data analysis project completed as a final assignment, working with a modified subset of Montgomery County's public Fleet Equipment Inventory dataset (Public Domain license). The scenario follows a Junior Data Analyst in a local government office tasked with cleaning and analyzing fleet inventory data across county departments.

Files

FileDescriptionMontgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsxCleaned and prepared datasetMontgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsxPivot table analysis built on the cleaned data

Part 1: Data Cleaning and Preparation

Starting from a raw CSV export, the following data quality issues were identified and corrected:


Converted the source CSV into a properly formatted Excel workbook
Resized columns so all data is fully visible
Removed blank/empty rows using the Filter feature
Removed duplicate records using Remove Duplicates
Corrected recurring spelling errors in department and equipment class names (e.g., "Enviromnental" → "Environmental")
Removed accidental double-spacing within text fields using Find and Replace
Repaired department names that had been split across two columns during the original data import, using Flash Fill to merge them into a single column


Part 2: Data Analysis with Pivot Tables

Using the cleaned dataset from Part 1, the following analysis was performed:


Formatted the data range as an Excel Table
Calculated summary statistics (Sum, Average, Min, Max, Count) for the Equipment Count column
Built a pivot table summarizing total equipment count by department, sorted in descending order
Created two additional pivot tables to explore the data from different angles:

Pivot Table 2: Department → Equipment Class, showing the breakdown of vehicle types within each department
Pivot Table 3: Equipment Class → Department, showing which departments hold each type of equipment





Tools Used

Excel for the web — including Tables, Find and Replace, Flash Fill, and PivotTables.

Author

Rithika Reejith
