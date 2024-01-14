## Pharmaceutical Database Analysis: Bolton Region

![Pharmaceutical Image](https://github.com/chrisinyama/Pharmaceutical-Database-Analysis/raw/main/Pharmaceutical.jpg)


## Table of Contents

1. [Introduction](#introduction)
2. [Data Import](#data-import)
3. [Query 1: Details of Drugs in Tablet or Capsule Form](#query-1)
4. [Query 2: Total Quantity for Each Prescription](#query-2)
5. [Query 3: Distinct Chemical Substances in the Drugs Table](#query-3)
6. [Query 4: Number of Prescriptions and Cost Statistics by BNF Chapter Code](#query-4)
7. [Query 5: Most Expensive Prescription by Practice](#query-5)
8. [Additional Functionalities](#additional-functionalities)
    - [Query 6: [Description]](#query-6)
    - [Query 7: [Description]](#query-7)
    - ...
9. [Conclusion](#conclusion)

# Introduction

This GitHub repository contains the code and results for the analysis of prescription data from the NHS in England, focusing on the Bolton region. The dataset consists of three related tables: Medical Practice, Drugs, and Prescriptions. The goal is to create a database, import the data, and execute various T-SQL queries to gain insights into medication types, prescribing organizations, and prescription quantities.

## Data Import

### Steps for Creating the Database

1. Create a database named **PrescriptionsDB**.
2. Import three CSV files (Medical_Practice, Drugs, and Prescriptions) into SQL Server Management Studio using the Import data wizard.
3. Modify columns, select accurate schemas, and review summary information.
4. Repeat the steps for each CSV file.

### Primary and Foreign Key Constraints

- Ensure that column names remain the same as in the CSV files.
- Select appropriate data types for tables.
- Add necessary primary keys.
- Write queries to add foreign keys.

### Database Diagram

An ER database diagram illustrates relationships between Medical_Practice, Drugs, and Prescriptions tables.

## Query 1: Details of Drugs in Tablet or Capsule Form

- **Explanation:** Retrieves details of drugs in tablet or capsule form.
- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

## Query 2: Total Quantity for Each Prescription

- **Explanation:** Calculates the total quantity for each prescription and rounds the result to the nearest integer value.
- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

## Query 3: Distinct Chemical Substances in the Drugs Table

- **Explanation:** Retrieves a list of distinct chemical substances in the Drugs table.
- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

## Query 4: Number of Prescriptions and Cost Statistics by BNF Chapter Code

- **Explanation:** Returns the number of prescriptions for each BNF chapter along with average cost, minimum and maximum prescription costs.
- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

## Query 5: Most Expensive Prescription by Practice

- **Explanation:** Retrieves the most expensive prescription prescribed by each practice, sorted in descending order by prescription cost.
- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

## Additional Functionalities

### Query 6: [Description]

- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

### Query 7: [Description]

- **T-SQL Statement:** [T-SQL Code](#)
- **Result Set:** [Result Set](#)

...

# Conclusion

Summarize key findings, insights gained, and potential applications of the results.
