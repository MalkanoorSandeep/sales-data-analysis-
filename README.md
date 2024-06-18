**Sales Data Analysis Project**

**Project Overview**

This project involves the cleaning, transformation, and analysis of sales data from a CSV file using Python. The project aims to uncover key insights and trends to inform strategic decisions.

**Project Summary**

The project includes a comprehensive analysis of sales data to understand revenue trends, customer preferences, and occupancy rates. The findings provide actionable insights to improve business strategies and decision-making processes.

**Files**

	•	orders.csv: The original dataset containing raw sales data.
	•	Sales_Analysis.html: An HTML file containing the Jupyter Notebook code used for data cleaning, transformation, analysis, and uploading the data to MySQL.

**Data Cleaning and Transformation**

The Sales_Analysis.html file includes Python code to:

	•	Remove duplicates and handle missing values.
	•	Convert data types and extract relevant columns.
	•	Merge and aggregate data for comprehensive analysis.

**Data Analysis**

The analysis performed in the Sales_Analysis.html file includes:

	1.	Month-over-Month Sales Growth Comparison (2022 vs 2023)
 	2.	Highest Sales Month for Each Category
  3.	Profit Comparison of Sub-categories (2022 vs 2023)
	4.	Top 10 Highest Revenue Generating Products
	5.	Top 5 Selling Products in Each Region

**Data Upload to MySQL**

The project also involves uploading the cleaned and transformed data to a MySQL database. The Sales_Analysis.html file contains the following steps:

	•	Establishing a connection to the MySQL database.
	•	Creating tables and uploading the data.
	•	Performing SQL queries to extract insights.

**Tools & Technologies**

	•	Jupyter Notebook
	•	Python (Pandas, Numpy, Matplotlib, SQLAlchemy)
	•	MySQL
	•	HTML (for presentation of the analysis)

**Requirements**

	•	Python 3.x
	•	pandas
	•	numpy
	•	matplotlib
	•	sqlalchemy
	•	mysqlclient (or pymysql)

**Database Setup**

To upload the data to MySQL, ensure you have a MySQL server running and update the connection details in the Jupyter Notebook. Example connection setup:
from sqlalchemy import create_engine

user = 'your_username'
password = 'your_password'
host = 'localhost'
database = 'sales_data'

engine = create_engine(f'mysql+pymysql://{user}:{password}@{host}/{database}')

**Results**

The results of the analysis and visualizations are included in the Sales_Analysis.html file, which you can open in any web browser to view the output.



   
