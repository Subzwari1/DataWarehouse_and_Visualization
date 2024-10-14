## DataWarehouse_and_Visualization

### Project Overview
This project is part of my Master's degree coursework, where I focused on designing and developing a Data Warehouse using a dataset on US Railway Accidents. The project includes:

- Establishing a robust data warehouse schema using PostgreSQL.
- Processing the raw data through an ETL (Extract, Transform, Load) pipeline.
- Performing in-depth data analysis to uncover meaningful insights.
- Visualizing the processed data on Tableau to present key findings to non-technical stakeholders.
- The goal is to enable efficient data management, identify patterns in railway accidents, and visualize insights that can inform decision-making processes.

### Technologies Used

- PostgreSQL: For designing and implementing the data warehouse schema.
- ETL Pipeline: To extract, transform, and load data into the warehouse.
- Python: For data preprocessing and transformation.
- Tableau: For data visualization and creating interactive dashboards.
- SQL: For querying the data warehouse and performing analysis.


### Project Workflow
1. Dataset: The dataset used in this project consists of historical data on US Railway Accidents, including details on the type, location, and severity of accidents.

Data Source: https://www.kaggle.com/datasets/yogidsba/us-highway-railgrade-crossing-accident

2. Data Warehouse Design:

-  Designed an Entity-Relationship Diagram (ERD) and developed the schema in PostgreSQL.
-  Defined fact and dimension tables to store the accident data effectively.

3. ETL Process:
-  Extract: Loaded the raw dataset into a staging area.
-  Transform: Cleaned the data, handled missing values, and structured it into the required format.
-  Load: Imported the transformed data into the PostgreSQL data warehouse.

4. Data Analysis:
-  Used SQL queries to perform in-depth analysis of accident trends, identifying patterns related to location, time, and severity.
-  Generated insights on accident frequency, common causes, and affected regions.
  
5. Data Visualization:

- Created interactive dashboards and charts using Tableau to visualize:
  - Accident trends over time.
  - Geographic distribution of accidents.
  - Types and causes of accidents.
  - Severity and impact analysis.
  - These visualizations provide an intuitive way for non-technical stakeholders to interpret complex data.

### Key Features
- Data Warehouse: A well-structured warehouse schema for efficient data storage and retrieval.
- ETL Pipeline: A robust data pipeline ensuring clean, accurate data for analysis.
- Data Analysis: Deep insights generated from complex data queries.
- Visualizations: User-friendly, interactive dashboards that present key insights.


