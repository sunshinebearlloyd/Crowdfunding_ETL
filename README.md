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

  ## Campaign DataFrame
  Angelo narrowed his research and continued to analyze the categories; breaking them down into subcategories. A total of 24 subcategories were present in the dataset. The first ten subcategories are below.
  
  ![image](https://github.com/sunshinebearlloyd/Crowdfunding_ETL/assets/132225987/1dcbfc79-1e05-4a30-839c-5eb3082ffa04)

  ## Contacts DataFrame
  ## SQL Schema and Queries




