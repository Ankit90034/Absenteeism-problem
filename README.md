# Absenteeism-problem

# purpose of project
# Given project finds out the absenteeism of employee in the company
# It finds out the reasons for absenteeisn and absenteeism hours.

#For reaching to our objective first we have load the python's required libraries such as numpy, pandas and matplotlib etc. using following code snippets.
import numpy as np;
import pandas as pd;
import matplotlib.pyplot as plt;
import seaborn as sns;

# Then we will load the Absenteeism-data.csv file to our working directory as follows
file_path = "C:/Users/DELL/Downloads/Absenteeism-data.csv"
raw_csv_data = pd.read_csv(file_path)

# Now we will perform data cleaning activities such as handling the missing values, proper formatting of every column variable and handle the outliers.

# Now we will analyze the data to answer various questions regarding absenteeism.

# Following questions can be answered using our data analysis.
1) What is the average absenteeism time per employee?
2) What are most common reasons for absenteeism?
3) What are the seasonal trends in absenteeism?
4) Which employees have highest absenteeism hours?
5) Does absenteeism vary by age group?
6) Does education level affect absenteeism?
7) Is there a correlation between daily workload and absenteeism?
