# Crowdfunding_ETL
**Submitted by** Kaylyn Valdez-Scott and Alyshia Kiczma **Date:** 14-NOV-2023 **Project Title:** Project 2, Crowdfunding ETL

Purpose of project is to build ETL pipelines using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. 

Through extraction and after transforming the data, we created four CSV files and used the CSV files data to create an ERD and a table schema for SQL. 

For Jupyter Notebook containing extraction and transformation work- see file labeled 'ETL_Mini_Project_AKiczma_KValdezScott.ipynb'
This notebook contains codes for reading excel sheets, taking that information and transforming them into DataFrames, and pulling certain information from the DataFrames. Finally, we export this information into CSV files. 

For CSV files created from the Jupyter Notebook, visit the Resources Folder- there you will find files labeled 'category.csv', 'subcategory.csv', 'contacts.csv', and 'campaign.csv'. 

Lastly, we took these CSV files and created tables through PostgreSQL. 
For the ERD file containing information on primary and foreign keys, see file labeled 'ERD Image.png'. 

To create tables through PostgreSQL, visit file labeled 'crowdfunding_db_schema.sql'. Using this schema, we created four tables and succesfully imported the coresponding CSV files to their table. 

To see the success of the imports, we used SELECT statements on each table to show information. See files labeled 'select_campaign screenshot.png', 'select_category screenshot.png', 'select_contacts screenshot.png', and 'select_subcategory screenshot.png'. 
