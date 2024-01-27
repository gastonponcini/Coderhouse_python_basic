# HRIS Dataset: Advancing Gender Representation in Managerial Levels

## Overview

This repository contains an HRIS dataset with information on gender representation in managerial levels for a global company. The dataset comprises 39,626 rows and 21 columns.

## Business Context

The company is committed to fostering diversity, equity, and inclusion, with a focus on advancing women's access to leadership positions. The global goal is to have 40% of women in management positions, with a minimum regional requirement of 20%. Additionally, there's an objective to ensure at least 20% of women in management positions in all functional areas and a target of 33% women leaders in bands 0-III.

## Metrics

1. **Percentage of Women in Management Positions Globally**
2. **Percentage of Women in Management Positions by Region**
3. **Percentage of Women in Management Positions by Functional Area**
4. **Percentage of Women in Management Positions in Bands 0-III**

## Solutions Needed

### 1. Identify Current Status

- Metric 1: Calculate the current global percentage of women in management positions.
- Metric 2: Calculate the regional percentages of women in management positions.
- Metric 3: Analyze the percentage of women in management positions by functional area.
- Metric 4: Assess the percentage of women in management positions in bands 0-III.

### 2. Identify the Gap

- Analyze the difference between the current status and the established targets for each metric.

### 3. Propose Action Focuses

- Provide recommendations and action plans to close the identified gaps. For example, suggest strategies to increase representation in specific regions or functional areas.

## Data Privacy

- This is a complete random dataset and therefore does not represent any company's real data.

## Summary of implemented code

Summary of the provided code:

- Importing Dataset:
Imported the dataset from a CSV file using pandas.
Displayed the first few rows of the DataFrame for data verification.

- Exploring Dataset:
Counted the number of missing values in each column and displayed the result.
Checked the data types of each column and displayed the result.

- Data Cleaning - Removing Inactive Employees:
Counted the number of employees by status ('Active' and 'Inactive').
Removed rows where the 'Status' column is 'Inactive'.
Displayed the updated counts of employees by status.

- ETL Processes - Standardizing Data: Languages:
Counted employees by language.
Replaced variations of Spanish and French with a single value ('Spanish' and 'French').
Displayed the updated counts of employees by language.

- ETL Processes - Standardizing Data: Global Function:
Counted employees by global function.
Converted all entries within the 'Global Function' column to lowercase.
Standardized specific entries like SALES and PROCUREMENT.
Displayed the updated counts of employees by global function.

- ETL Processes - Standardizing Data: Gender:
Counted employees by gender.
Converted all entries within the 'Gender' column to lowercase.
Standardized specific entries like MALE and FEMALE.
Displayed the updated counts of employees by gender.

- ETL Processes - Standardizing Data: Band Equivalence:
Counted employees by band equivalence.
Converted all entries within the 'Band Equivalence' column to lowercase.
Standardized specific entries like VI.
Displayed the updated counts of employees by band equivalence.

- ETL Processes - Standardizing Data: Manager Flag:
Counted employees by Manager Flag.
No changes were needed for this column.

- ETL Processes - Standardizing Data: Zone:
Counted employees by Zone.
No changes were needed for this column.
