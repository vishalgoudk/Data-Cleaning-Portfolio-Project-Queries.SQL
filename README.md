# Nashville_Housing Data Cleaning

## Project Overview

This data cleaning project focuses on preparing Nashville housing data for analysis using SQL Server. The dataset, sourced from an Excel file, contains information about properties in Nashville. The data cleaning process is carried out using SQL queries, utilizing various functions and operations to standardize, enhance, and streamline the dataset.

# Tools Used

    SQL Server: Primary database management system for data cleaning.
    Excel File: Source of the raw Nashville housing data.

# Data Cleaning Steps

1. Importing Data

The first step involves importing the raw Nashville housing data from the Excel file into SQL Server, creating a database table for further processing.

2. Standardize Date Format

To ensure consistency, the date format in the dataset is standardized using the UPDATE statement and appropriate functions to transform the date values into a uniform format.

3. Populate Property Address Data

The property address information is populated and standardized using the UPDATE statement and relevant functions to enhance data completeness.

4. Breaking Out Address into Individual Columns

The address information is broken down into individual columns such as street address, city, state, and zip code for better analysis and organization. This is achieved using functions like SUBSTRING and PARSENAME.

5. Remove Duplicates

Duplicates in the dataset are identified and removed using the DELETE statement with a self-join operation to retain only unique records.

6. Delete Unused Columns

Columns that are deemed unnecessary for analysis are deleted from the dataset using the DROP COLUMN statement.

# Functions Used

    Alter Table: Used to modify the structure of the database table.
    
    Update Table: Employed to update existing data based on specific conditions or transformations.
    
    Self Join: Used to compare rows within the same table for duplicate removal.
    
    Substring: Extracts a substring from a specified position in a string.
    
    ParseName: Extracts the specified part of a delimited string.
    
    CASE Statement: Implements conditional logic to modify or create columns based on specified criteria.
    
    CTE (Common Table Expression): Utilized for creating temporary result sets to simplify complex queries.
    Delete: Removes rows from a table based on specified conditions.
    
    Drop Column: Eliminates specified columns from the table structure.

# Conclusion

The Nashville housing data cleaning project ensures that the dataset is standardized, enriched, and organized for further analysis. By employing SQL queries and various functions, the data is transformed into a more structured and insightful format, eliminating inconsistencies and redundancies. The cleaned dataset is now ready for exploratory data analysis, reporting, and other analytical tasks.
