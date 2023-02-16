# Crowdfunding-ETL
## Purpose:
The purpose of this module is to use ETL process by cleaning, restructuring,  formatting, filtering, and splitting the data and load the dataset as CSV files into SQL database.

## Results:
There were many methods used for ETL process such as Python, Pandas, Jupyter Notebook, and a PostgreSQL database.
•	Extracting and transforming the data from the large Excel file into four separate CSV files
•	Creating a PostgreSQL database and tables by using an ERD
•	Loading the CSV files into the database
•	Performing SQL queries to generate reports for stakeholders.

- backers_info was imported from crowdfunding info sheet with the following result as shown below
![image](https://user-images.githubusercontent.com/120526544/219506367-e5c6841b-63ed-477b-a2b9-36238ecd6530.png)

 
- The below data shows the formatted version of the dataframe in list of columns that is readable.
 ![image](https://user-images.githubusercontent.com/120526544/219506404-79cdb90d-1024-4874-a7d3-05cfc7b6e97a.png)


- I created an ERD and Table Schema and Load the Data
The ERD model shows the connection between the csv files before loading the data into SQL.

![image](https://user-images.githubusercontent.com/120526544/219506443-8e70bae4-54b4-4b9f-bacd-d66caceeb5d5.png)

 
- The last step was to create new table that shows email contacts remaining goal amount and email backers remaining goal amount that contains the email addresses of the backers, the first and the last name of each backer, the cf_id, the company name, the description, the end date of the campaign, and the remaining amount of the campaign goal as "Left of Goal
 
![image](https://user-images.githubusercontent.com/120526544/219506484-b80c69c8-cf85-4dc5-b860-2483e0c71f5b.png)
