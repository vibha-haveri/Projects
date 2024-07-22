# Projects

Welcome to the Data Analysis Projects repository! This repository contains a collection of data analysis projects utilizing various tools and technologies including Excel, Tableau, Python, and Power BI.


This repository is designed to showcase my skills and knowledge in data analysis ,cloud technology, coding and database management using a variety of tools. Each project aims to demonstrate different aspects of data analysis, from data cleaning and processing to visualization and insights generation.

Excel Project

File: excel_dataAnalysis

Description: Analysis of sales profit data of gym equipments to identify trends and insights. 
             Raw data has 1000 rows with couple if brands and equipments 
             Created Pivot table  to summarize the raw data. Worked on the pivot table analysis to calculate year on year growth for each brand and equipments.
             Analyzed the market share for each brand also. Calculated the %  of total  row for each year to know the market share of each brand, also added a graph to enhance the visulization and added a slicer to enhance the filtering of data via category as well.


Python Project

File: dataScript

Description : Python script to extract data from an Excel file, divide it into dataframes, and store it in a database using Python, used libraries like pandas, openpyxl (for reading Excel files), and SQLAlchemy (for interacting with databases).

             Reading the Excel file:
             The read_excel_and_divide function reads an Excel file and divides its content into multiple dataframes, each representing a sheet in the Excel file.
             pd.ExcelFile(file_path) is used to read the Excel file.
             xl.sheet_names gives the names of all the sheets in the Excel file.
             xl.parse(sheet_name) reads each sheet into a dataframe.
            
             Storing dataframes in the database:
             The store_dataframes_to_db function takes the dataframes and a database URI as input.
             It creates a SQLAlchemy engine with the given database URI.
             It loops through each dataframe and stores it in the database using the to_sql method.
             The if_exists='replace' parameter ensures that if a table with the same name already exists, it will be replaced.


Tableau Project

File: tableau_houseSalesinSeattle

Description : The data is house sales data in King county near Seattle area in Washington state. It has all the data of each sold house like buyer name, sex, credit score, salary, house sq foot, age. 
              The entire vizulization is divided into differnt category to analyze differnt aspects.
              Simple Line chart to analyze daily Avg House sales, a geographc map visual represnting the county on the map.
              Histogram to show the distribution of House prices. Filters like year, date, Square foot.
              Combined all the vizulas to create a interactive dashboard with all the above mentioned charts, graphs and filters.
             
