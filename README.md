### Assignment 1: Data Cleaning and Summarising
#### Introduction
In this assignment, you will examine a (set of) data file(s) and carry out the first steps of the data science process, including the cleaning and exploring of data. You will need to develop and implement appropriate steps, in Jupyter notebook (in the Anaconda version specified in the canvas announcement), to load a data file into memory, clean, process, and analyse it. This assignment is intended to give you practical experience with the typical first steps of the data science process.

#### Task 1: Data Preparation
Have a look at the file Daily Rainfall Climate Data.zip, which is available in Canvas under the Assignments/Assignment 1 section of the course Canvas. This data set is provided by Australian Government - the Bureau of Meteorology, which contains daily rainfall climate data between 2013 and 2023 in ABC city.
Being a careful data scientist, you know that it is vital to carefully check any available data before starting to analyse it. Your task is to prepare the provided data for analysis. You will start by loading the CSV data from the file (using appropriate pandas functions) and checking whether the loaded data is equivalent to the data in the source CSV file. Then, you need to clean the data by using the knowledge we taught in the lectures. You need to deal with all the potential issues/errors in the data appropriately and then write the cleaned data into a comma-separated values (csv) file(s) accordingly, e.g. (file can be named as ‘cleaned version.csv’).
#### Task 2: Data Exploration 
1. Prepare and convert the data in 2014 as a pandas DataFrame with rows as the days in a month and columns as the months in a year (e.g. row 1 contains the rainfall data in the 1st day of each month; row 2 contains the rainfall data in the 2nd day of each month, ...). Then, explore the highest daily rainfall in each month.
2. Explore the data between 2015 and 2017, and analyse them on both a yearly and monthly basis with visualizations.
3. Explore the data, and find the top 3 years with the highest rainfall amount and the top 3 years with the lowest rainfall amount, then compare them.
4. Explore the changes of rainfall in ABC City in the last 10 years.
