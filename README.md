NYC Yellow Taxi ETL Pipeline

Description:
This project demonstrates a full ETL (Extract, Transform, Load) pipeline using public NYC Yellow Taxi Trip data. The pipeline efficiently processes large-scale datasets in Google BigQuery, performing data extraction, cleaning, transformation, and loading into a structured table for analysis.

Key Features:

Extract: Pulled NYC Yellow Taxi trips dataset (2019) from BigQuery public datasets into a Pandas DataFrame.

Transform:

Converted timestamp columns to datetime format

Calculated trip duration and tip percentage

Filtered out outliers and invalid records

Engineered new features such as pickup hour, weekday, and aggregated metrics

Load: Loaded the cleaned and enriched data into a BigQuery table (nyc_etl.yellow_taxi_etl) for further querying and analysis.

Scalable & Reproducible: Entire ETL process is reproducible in Google Colab and can handle large datasets efficiently.

Applications:

Can be used for data analysis, dashboard creation, and machine learning modeling.

Demonstrates practical experience with BigQuery, SQL, Pandas, and ETL workflows.

Outcome:
A fully functional ETL pipeline that transforms raw public datasets into structured, queryable, and analytics-ready BigQuery tables.
