# Exploratory_Data_Analysis


![image](https://user-images.githubusercontent.com/83994337/203661658-065c0ad9-4c0a-4023-93a2-4cfded98d3a9.png)

![image](https://user-images.githubusercontent.com/83994337/203661676-d9860405-ee08-45a2-8ce9-15e6bd08be3c.png)




Exploratory data analysis for a dataset that contains 3 treadmill products

Introduction
The retail store selling the treadmill products is called "Cardio Good Fitness".
The products included in the dataset are 3 treadmill products.
Objective: To do preliminary data analysis for Cardio Good Fitness dataset
Make a customer profile for the products
Use descriptive statistics, univariate and multivariate analysis for the dataset
Generate set of insights and recommendations for the company
Variables List
Product bought by customers - TM195, TM498 and TM798
Age - in years
Gender
Education - in no. of years, of the customer
Relationship status - of the customer
Usage - Avg. # times the customer wants to use the treadmill every week
Fitness - Self rated fitness score of the customer (5 - very fit, 1 - very unfit)
Income - of the customer
Miles- expected to run
The analysis has the following sections:
Loading and importing packages
Removing warnings from the python notebook
Loading the dataset
Preview of the dataset
Pandas profile creation and saving to a file
Checking columns, shape, datatypes, missing values
Descriptive statistics for the dataset
Univariate, bivariate and multivariate analysis for the dataset (observations are under each cell)
Insights gained from the analysis
Recommendations based on the analysis
1. Loading and importing packages
#Installing Pandas profile package
import sys
!{sys.executable} -m pip install pandas-profiling

#Pandas Profiling was used to generate a profile report to get a quick descriptive statistical summary of the data and missing values. 
import pandas_profiling

# Import the necessary packages
import numpy as mp
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
sns.set(color_codes=True) # For background of the graphs
%matplotlib inline

2. Removing warnings from python notebook
#Removing warnings from the notebook
import warnings
warnings.filterwarnings('ignore')
