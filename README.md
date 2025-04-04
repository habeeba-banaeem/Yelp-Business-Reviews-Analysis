# Yelp-Business-Reviews-Analysis
Project Overview

This project involves end-to-end data analysis of Yelp Reviews. The process includes downloading the dataset, processing large files, uploading data to cloud storage, transforming and cleaning it in Snowflake, and executing analytical queries.

Steps Involved

1. Data Acquisition

Downloaded the Yelp Reviews dataset from the official website.

Extracted the compressed zip file on the local desktop.

2. Data Preprocessing

The dataset was large, so a Python script was written to split the JSON files into smaller chunks for efficient processing.

3. Cloud Storage

Created an AWS account.

Uploaded the split JSON files into AWS S3 for secure storage and further processing.

4. Snowflake Integration

Created a Snowflake account.

Wrote a query to load the data from AWS S3 into Snowflake.

Transformed the uploaded JSON data into a structured tabular format.

5. Data Cleaning & Transformation

Cleaned the raw data by handling missing values, normalizing text, and structuring it into a tabular format for analysis.

6. Data Analysis

Executed 10 SQL queries in Snowflake to analyze the Yelp Reviews dataset.

The queries provided insights such as:

Average rating distribution

Top-rated businesses

Most reviewed businesses

Customer sentiment trends

Frequent keywords in reviews

And more...

Technologies Used

Python (for data preprocessing and file handling)

AWS S3 (for cloud storage)

Snowflake (for data warehousing and SQL queries)

SQL (for data analysis and querying)

GitHub (for project documentation and version control)

Repository Structure

|-- data_preprocessing/    # Python scripts for splitting large JSON files
|-- aws_upload/            # Documentation on AWS S3 upload
|-- snowflake_queries/     # SQL queries executed in Snowflake
|-- insights/              # Analysis results and visualizations
|-- README.md              # Project documentation

How to Use This Repository

Clone the repository:

git clone https://github.com/yourusername/yelp-reviews-analysis.git

Follow the step-by-step process in each folder for preprocessing, uploading, and analyzing the data.

Run the SQL queries in Snowflake to derive insights from the dataset.

Future Enhancements

Automate the data pipeline using Apache Airflow.

Perform sentiment analysis using NLP techniques.

Visualize insights using dashboards like Tableau or Power BI.

Contributing

Feel free to contribute by improving scripts, adding more queries, or enhancing the documentation.
