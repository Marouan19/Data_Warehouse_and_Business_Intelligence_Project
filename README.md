# Data Warehouse and Business Intelligence Project

## Overview
This project implements a comprehensive data warehouse and business intelligence solution for analyzing product sales and supplier performance. It primarily uses Talend for ETL processes, with plans to integrate MySQL for data storage and Power BI for visualization and reporting.

## Project Structure
- `/.settings`: Project settings files
- `/code`: Custom code snippets or scripts
- `/components`: Custom components for Talend
- `/context`: Context files for managing environment-specific variables
- `/documentations`: Project documentation files
- `/images`: Image resources used in the project
- `/joblets`: Reusable Talend joblets
- `/metadata`: Metadata definitions for connections, schemas, etc.
- `/process`: Main Talend job designs
- `/routes`: Talend route designs (if using Talend ESB)
- `/sqlPatterns`: SQL patterns for database operations
- `/.gitignore`: Specifies intentionally untracked files to ignore
- `/.project`: Eclipse project file
- `/recycle_bin.index`: Index of items in the recycle bin
- `/talend.project`: Talend project configuration file

## Technologies Used
- ETL: Talend Open Studio
- Version Control: Git
- Planned:
  - Database: MySQL
  - Reporting: Microsoft Power BI

## Setup Instructions
1. Clone the repository
2. Import the project into Talend Open Studio
3. Configure context variables if necessary
4. Run the main job from the `/process` directory

## Data Sources
- Products: `products.xlsx`
- Suppliers: `suppliers.csv`
- Invoices: `supplier_invoice.csv`
- Product Costs: `product_costs.csv`

## ETL Process
1. Data Extraction from source files
2. Data Cleaning and Standardization
3. Dimension and Fact Table Creation
4. Loading into the target system (to be implemented)

## Planned Data Warehouse Schema
- Fact Table: FACT_SALES
- Dimension Tables: 
  - DIM_PRODUCT
  - DIM_SUPPLIER
  - DIM_TIME

## Key Features
- Supplier invoice analysis by year
- Product cost analysis
- Automated data processing with Talend

## Future Enhancements
- Integration with MySQL database
- Development of Power BI reports including:
  - KPI dashboard
  - Supplier performance analysis
  - Product sales trends
  - Geographical sales distribution


## Authors
- Daghmoumi Marouan

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details

## Acknowledgments
- Talend Open Studio community
