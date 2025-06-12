# Overview

This final project involved building a robust data pipeline to transform the raw Brazilian E-Commerce public dataset by Olist into actionable business insights.
The process encompassed a full ETL (Extract, Transform, Load) cycle. Data was extracted from Kaggle using the Kaggle API and stored in Azure Data Lake Storage Gen2. 
Subsequently, extensive data cleaning and transformations were performed using Python and the pandas library, addressing issues such as missing values, inconsistencies,
and data type conversions across various datasets like sellers, orders, payments, reviews, products, customers, and geolocation. The cleaned data was then loaded into 
Azure Data Lake under a "transform-data" folder in Parquet format, with some tables also loaded into a PostgreSQL database.

The project culminated in the preparation of an analytics-ready dataset designed for business intelligence. Exploratory Data Analysis (EDA) was conducted to understand 
data patterns and identify key relationships, including the visualization of geolocation features and the examination of order statuses. A significant outcome was the 
development of a median-based composite "Seller Reliability Score," which evaluates seller performance using metrics like median review scores, fulfillment rates, and 
delay rates, comparing actual delivery dates against Olist's estimated dates. This score was further aggregated at city and category levels to provide insights into 
operational challenges. [cite_start]The transformed data is now ready for in-depth business analysis and visualization in platforms like Microsoft Fabric, 
enabling data-driven strategic oversight and operational improvements, particularly concerning seller performance and payment trends.
