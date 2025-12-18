# Healthcare Data Manipulation

## File Information
- **Program Name:** `healthcare_data_manipulation.ipynb`
- **Author:** Stephen Lew
- **Last Updated:** 12/15/2025
- **Python Version:** 3.14.0

## Description
Built Python-based data pipeline to extract and transform synthetic healthcare claims data from SQL Server and Snowflake using SQLAlchemy, pyodbc, and environment-managed credentials. Implemented reusable database connection functions with f-strings for cross-platform data access.

Performed data enrichment and transformation with pandas and NumPy, including ICD-10 code joins, column renaming, filtering, sorting, feature engineering, and aggregation. Calculated insurance-level claim denial rates and standardized categorical fields using vectorized operations and loop-based transformations.

Key technologies: Python, pandas, NumPy, SQL, SQL Server, Snowflake, SQLAlchemy, healthcare claims, ICD-10 data
