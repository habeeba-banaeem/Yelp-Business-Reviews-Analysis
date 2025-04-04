# Yelp-Business-Reviews-Analysis
# Project Overview

This project involves end-to-end data analysis of Yelp Reviews. The process includes downloading the dataset, processing large files, uploading data to cloud storage, transforming and cleaning it in Snowflake, and executing analytical queries.

# Steps

# 1. Data Acquisition
Downloaded the Yelp Reviews dataset from the official website.
Extracted the compressed zip file on the local desktop.

# 2. Data Preprocessing
The dataset was large, so a Python script was written to split the JSON files into smaller chunks for efficient processing.
![image](https://github.com/user-attachments/assets/d45150ab-34f9-4f9f-a152-6a0b5efd025a)

# 3. Cloud Storage
Created an AWS account.
Uploaded the split JSON files into AWS S3 for secure storage and further processing.
![image](https://github.com/user-attachments/assets/914049eb-5cd2-46d2-81d4-b9bf50eadd65)

# 4. Snowflake Integration
Created a Snowflake account.
Wrote a query to load the data from AWS S3 into Snowflake.
Transformed the uploaded JSON data into a structured tabular format.
![image](https://github.com/user-attachments/assets/1a45a6ab-2172-40ab-a51f-a32d3ab113f6)

# 5. Data Cleaning & Transformation
Cleaned the raw data by handling missing values, normalizing text, and structuring it into a tabular format for analysis.
![image](https://github.com/user-attachments/assets/dd360a3b-96e7-467e-bcff-c8c792ae6201)

# 6. Data Analysis
Executed the following 10 SQL queries in Snowflake to analyze the Yelp Reviews dataset.

Q1. Find number of businessess in each category.
Q2. Find top 10 users who reviewed the most businesses in the "Restaurants" category. 
Q3. Find the most popular categories of businesses based on the number of reviews. 
Q4. Find the top 3 most recent reviews for each business. 
Q5. Find the month with the highest number of reviews. 
Q6. Find the percentage of 5 star reviews of each businesses. 
Q7. Find the top most reviewed businesses in each city. 
Q8. Find the average rating of businesses that have at least 100 reviews. 
Q9. List the top 10 users who have written the most reviews, along with the businesses they reviewed.
Q10. find top 10 businesses with highest positive sentiment reviews. 

# Technologies Used

-- Python (for data preprocessing and file handling)
-- AWS S3 (for cloud storage)
-- Snowflake (for data warehousing and SQL queries)
-- GitHub (for project documentation and version control)

Clone the repository:

git clone https://github.com/yourusername/yelp-reviews-analysis.git

