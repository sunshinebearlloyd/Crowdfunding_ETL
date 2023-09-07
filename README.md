# ETL Mini Project 
Project 2 Repository for Group 4

# Overview
The ETL Mini Project was undertaken to practice building an ETL (Extract, Transform, Load) pipeline using Python and Pandas. The project involved data extraction, data transformation, and data cleaning. Each group member had a specific focus within the project:

+ Angelo's focus was on the Crowdfunding portion, where he worked on categorizing crowdfunding projects based on categories and their subcategories.
+ Ashley's responsibility was the Campaign portion, where she cleaned and formatted the data and merged it with the crowdfunding data.
+ Natalie worked on the Contacts portion, gathering and cleaning data from crowdfunding campaigns and creating a DataFrame that includes contact information.
+ Shannon's focus was on gathering our data and information and forming a SQL Database and scehma. Numerous queries were run to confirm database success. 

# Getting Started
To run this project, follow these steps: 
1. Make sure you are working in a development environment. Activate it using:
  + conda activate dev
2. Import the necessary dependencies:
+ import pandas as pd
+ import numpy as np
+ pd.set_option('max_colwidth', 400)
3. Starter files for this project are providied in the Resources folder

# Directory Structure
The project directory structure is organized as follows:

+ Resources: Contains the Excel starter files and CSV files exported from data research.
+ Notebooks: Individual Jupyter notebooks for each group member's work.
+ ETL_Mini_Project_Final.ipynb: The final draft of the code where all individual work is merged.

  # Jupyter Notebook
  ## Crowdfunding Data
  Angelo Lima focused on organizing the Crowdfunding Data to organize the different types of categories and subcategories of crowdfunding campaigns existed. He split the data based on their categories. A total of 9 categories were present in the dataset.
  
    ![image](https://github.com/sunshinebearlloyd/Crowdfunding_ETL/assets/132225987/6281a629-c999-44d3-ad5c-5d211b467c41)

  Angelo narrowed his research and continued to analyze the categories; breaking them down into subcategories. A total of 24 subcategories were present in the dataset. The first ten subcategories are below.
  
  ![image](https://github.com/sunshinebearlloyd/Crowdfunding_ETL/assets/132225987/1dcbfc79-1e05-4a30-839c-5eb3082ffa04)

  ## Campaign DataFrame
  Ashley's responsibilities centered around the Campaign portion of the project. The primary goal was to ensure the data used was clean and in the correct format. Tasks included data cleaning and merging the category_df and subcatefory_df. 

  ## Contacts DataFrame
  Natalie's area of focus centered around the contacts of the Crowdfunding campaigns. Data needed to be cleaned and extracted to provide a dataframe with only the contact_id, first_name, last_name, and email addresses. 
  
  ![image](https://github.com/sunshinebearlloyd/Crowdfunding_ETL/assets/132225987/d2e3572f-7ab9-4e06-92c9-895466266825)

  ## SQL Schema and Queries
  After all data was extracted and cleaned, Shannon pulled together and created a SQL schema via QuickDBD to provide a visual representation of our database. She then uses query statements to populate all tables created and populated correctly. 
  
  ![image](https://github.com/sunshinebearlloyd/Crowdfunding_ETL/assets/132225987/3aecab61-1a60-4244-9d81-d546dcd3a02d)

  It's important to note that each team member had a distinct role that contributed to the overall success of the ETL (Extract, Transform, Load) pipeline project. These roles included data categorization, data cleaning, and data extraction, ensuring that the project's data was well-prepared for further analysis and use. Additionally, the collaborative effort involved merging various datasets to create a cohesive dataset for the project's objectives. The collaboration and coordination of these roles were essential in achieving the project's goals effectively.





