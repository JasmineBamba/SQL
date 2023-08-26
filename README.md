# SQL Challenge - Employee Data Analysis

## Introduction

Welcome to the SQL Challenge assignment submission, where we embarked on a journey of data modeling, data engineering, and data analysis using employee data from Pewlett Hackard during the 1980s and 1990s.

## Assignment Overview

The completed assignment encompassed the following significant phases:

### Data Modeling

An Entity Relationship Diagram (ERD) was meticulously crafted after an in-depth examination of the provided CSV files. This ERD visually captured the relationships within the data, employing tools like QuickDBD.

![ERD](https://github.com/JasmineBamba/sql-challenge/assets/135666038/9ff1609f-e34b-452d-ba36-b64ac33a6455)


### Data Engineering

Following the design of the ERD, we transitioned into the crucial task of establishing table schemas for the six CSV files. Each table schema was thoughtfully curated, involving the selection of appropriate data types for columns, definition of primary keys for identification, establishment of foreign keys to denote relationships between tables, and application of constraints to ensure data integrity.

To ensure that each primary key was unique, composite keys were adopted when necessary. The creation order of tables was methodically arranged to account for dependencies introduced by foreign keys. Subsequently, the CSV data was methodically imported into the respective SQL tables.

### Data Analysis

The heart of the assignment was brought to light through a series of meticulous SQL queries designed to tackle the provided data analysis questions:

- The employee number, last name, first name, sex, and salary of each employee were extracted.
- A list was generated, highlighting the first name, last name, and hire date of employees hired in 1986.
- Department managers were identified, along with their department number, department name, employee number, last name, and first name.
- Each employee's department number, employee number, last name, first name, and department name were skillfully connected.
- Through a strategic filtering process, employees with the first name "Hercules" and last name starting with "B" were isolated, revealing their first name, last name, and sex.
- Employee lists were curated for both the Sales department and the combined Sales and Development departments, complete with relevant department names.
- Lastly, a frequency distribution was derived for employee last names, descending in order, showcasing the count of employees sharing each last name.

## Repository Structure

- The `EmployeeSQL` directory is the repository's nucleus, housing all crucial project files, including SQL scripts and the imported CSV data.
- An indispensable part of the project, the ERD is visually presented as an image within the repository, named `erd.png`.

## Usage

To engage with the project, follow these steps:

1. Clone this repository to your local environment.
2. Access the `EmployeeSQL` directory to interact with SQL scripts and data.
3. Execute the SQL scripts in a compatible database management system to replicate the tables and perform data analysis queries.

Feel free to navigate through the queries and immerse yourself in the insights extracted from the employee data.

## Conclusion

This SQL Challenge assignment was an educational exploration encompassing data modeling, engineering, and analysis. Through the design of an ERD, meticulous schema creation, precise data import, and thoughtfully formulated queries, an intricate grasp of real-world data manipulation and insight extraction was achieved.
