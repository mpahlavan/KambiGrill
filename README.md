# Assignment for Data Engineer - Data Lake job position at Kambi


## Introduction
This assignment focuses on designing a data warehouse for Kambi Grill, a restaurant that operates a member's only grill. The data warehouse is designed to analyze various aspects related to orders, customers, campaigns, and items to improve business decision-making.

## Project Overview
The goal of this assignment is to create a data warehouse that can handle analytical queries related to gross generated revenue, order statistics, item popularity, customer preferences, and more. The data model follows a star schema structure, enabling efficient querying and analysis.

## Features
- Star schema-based data model for efficient analytical querying.
- ETL process to extract, transform, and load data into the data warehouse.
- SQL queries to answer analytical questions based on the provided data model.

## Data Model Description
The logical data model includes fact and dimension tables, representing the central measures and related attributes. The relationships among the tables enable efficient analytics.

- Fact Table: Orders
- Dimension Tables: Customer, Campaign, Store, Item, OrderStatus, Preference, CustomerPreference
For a detailed description of the tables and their relationships, please refer to the data model section.

## ETL Process Description
The ETL process involves extracting data from various sources, transforming and preparing the data, and loading it into the star schema. The ETL process is essential for keeping the data warehouse up-to-date and ready for analytical querying.

For detailed steps and code related to the ETL process, please refer to the ETL Process section.

## Challenges and Learnings
Throughout this assignment, we encountered challenges related to data modeling, ETL process efficiency, and SQL query optimization. Overcoming these challenges provided valuable learnings in designing effective data warehouses and writing efficient SQL queries.


## Assumptions 
The schema assumes a one-to-many relationship between the fact table and the dimensions, reflecting real-world relationships.
It's assumed that appropriate data cleansing, transformation, and loading processes will be applied to maintain data quality and consistency in the warehouse.


## Trade-Offs and Limitations
These assumptions impact the solution's scope and implementation. I consider one fact table to optimize and not complex the model.


## Contact Information
For any inquiries or feedback regarding this assignment, please contact:
- Email: pahlavan.maryam@gmail.com
