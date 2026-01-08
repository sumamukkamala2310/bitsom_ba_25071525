# FlexiMart Data Architecture Project

**Student Name:Suma Mukkamala 
**Student ID:BITSom_BA_25071525
**Email:
**Date:02-01-2026

## Project Overview
I have built a complete data solution for FlexiMart retail. The project includes building an ETL pipeline using Python and MySQL (Part 1), analyzing complex product data using MongoDB (Part 2), and creating a Star Schema Data Warehouse for analytics (Part 3).

## Repository Structure
â”œâ”€â”€ part1-database-etl/
â”‚   â”œâ”€â”€ etl_pipeline.py
â”‚   â”œâ”€â”€ schema_documentation.md
â”‚   â”œâ”€â”€ business_queries.sql
â”‚   â””â”€â”€ data_quality_report.txt
â”œâ”€â”€ part2-nosql/
â”‚   â”œâ”€â”€ nosql_analysis.md
â”‚   â”œâ”€â”€ mongodb_operations.js
â”‚   â””â”€â”€ products_catalog.json
â”œâ”€â”€ part3-datawarehouse/
â”‚   â”œâ”€â”€ star_schema_design.md
â”‚   â”œâ”€â”€ warehouse_schema.sql
â”‚   â”œâ”€â”€ warehouse_data.sql
â”‚   â””â”€â”€ analytics_queries.sql
â””â”€â”€ README.md

## Technologies Used
- **Languages:** Python 3.x, SQL, JavaScript
- **Libraries:** pandas, mysql-connector-python
- **Databases:** MySQL 8.0, MongoDB 6.0
- **Tools:** VS Code, MySQL Workbench

## Setup Instructions
1. **Database Setup:** Use `warehouse_schema.sql` to create tables in MySQL.
2. **ETL Pipeline:** Run `etl_pipeline.py` to clean and load data.
3. **Analytics:** Run `analytics_queries.sql` to view business reports.

## Key Learnings
1. Learned how to build a robust ETL pipeline and handle data cleaning using Pandas.
2. Understood the difference between SQL (Structured) and NoSQL (Document-based) databases.
3. Mastered Dimensional Modeling (Star Schema) for efficient data warehousing.

## Challenges Faced
1. **Data Cleaning:** Standardizing phone numbers in Part 1 was tricky because of different formats. I solved it using Python Regex.
2. **Schema Design:** Deciding between Fact and Dimension tables in Part 3 was confusing initially, but the Star Schema approach clarified relationships.
