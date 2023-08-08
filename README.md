## Project Title

Car Sales Analysis Project

## Project Goal

The purpose of this research is to compare and contrast two sets of car sales data in order to draw useful conclusions. To better understand car sales patterns, consumer preferences, and other important criteria, we want to combine and analyze information from these databases by executing data extraction, transformation, and loading (ETL) operations.

## Data Sources

**Dataset 1:** 2023 Car Specifications and Features Dataset
- Description: This data collection contains information about several 2023 vehicle models, including their technical details, available options, and user reviews.

**Dataset 2:** 2023 Car Sales Dataset
- Description: This 2023 car sales dataset includes customer ratings, prices, and sales figures for a variety of vehicle makes and models.

## Steps Followed

1. **Data Extraction:**
   - Extracted data from the provided CSV files using Pandas' read_csv() function.
   - Loaded the data into Pandas data frames for further processing.

2. **Data Transformation:**
   - Cleaned and preprocessed the data to handle missing values, data type conversions, and 
     formatting issues.
   - Performed aggregation operations like calculating average customer ratings and total sales 
     figures.
   - Joined the two datasets using common attributes such as Car Make and Car Model.

3. **Data Loading:**
   - Created a MySQL database to store the cleaned and transformed data.
   - Used the Pandas to_sql() method to load data from data frames into corresponding MySQL 
     tables.
   - Utilized appropriate data types and indexes for efficient storage and retrieval.

4. **Outcome:**
   - Created a new table in the MySQL database that holds the combined and transformed data 
     from both datasets.
   - Derived insights on popular car models based on sales figures and customer ratings.
   - Visualized the data to showcase trends and correlations using Python libraries like 
     Matplotlib and Seaborn.

## Data Samples or Snapshots

Sample from Dataset 1 (Car Specifications and Features):
![Screenshot 2023-08-08 175205](https://github.com/tarun496-oss/Car_sales_analysis/assets/137961701/28930072-dd34-4404-9db1-d29c26fe48f6)

Sample from Dataset 2 (Car Sales):
![Screenshot 2023-08-08 175145](https://github.com/tarun496-oss/Car_sales_analysis/assets/137961701/9f7c9c05-cada-4aaf-96f3-0452ce475284)

## Code Files

- data_extraction.py: Contains code for reading CSV files using Pandas.
- data_transformation.py: Includes data cleaning, aggregation, and join operations.
- data_loading.py: Demonstrates loading data into a MySQL database using Pandas.
- data_analysis.ipynb: Jupyter Notebook showcasing data analysis, visualizations, and insights.

## Future Improvements

- In order to improve the analysis, you should look into adding more details or using more 
  outside data.
- Make use of machine learning methods to forecast sales and consumer tastes.
- Increase the use of visuals and narrative to make your presentation of insights more 
  interesting.

## Conclusion

In order to better understand the automobile business, this project effectively combined and analyzed data on vehicle characteristics and sales. Through the ETL procedure, we were able to examine sales data and consumer feedback to learn more about the most popular automobile models. We now have a clearer picture of the forces shaping 2023 automobile sales thanks to visualizations and data-driven analyses.
