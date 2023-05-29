# Indian-Start-up-Project
As the data expert of your team, you have been tasked with investigating the Indian start-up environment and recommending the optimal course of action for your team's venture into this space.

# Context
The data for this project spans from 2018-2019. Our goal will be to satisfy the processes for handling the data and also provide a detailed analysis of the process. 

We will be looking at these Processes below in a chronolgical order. 
* Asking the relevant questions and stating some hypothesis.
* Cleaning the data. 
* Running Some Exploratory Data Analysis.
* Statistical Testing.
* Answering our Questions with Visualizations.
* Power BI Deployment

# Asking the relevant questions and stating some hypothesis.
## Questions
* Do companies in certain sectors tend to receive more funding than others?
* Is there a correlation between the stage of development of a company and the amount of funding it receives?
* Are companies with more founders more likely to receive larger
amounts of funding?  
* Are there any patterns in the location of a company's headquarters and the amount of funding it receives? 
* Does the number of investors in a company tend to impact the amount of funding it receives? 
* Founders: How many founders are associated with each company? What is the average number of founders?
* What are the top 10 companies with the highest funding?

## Hypothesis
* Startups in the e-commerce and fintech sectors receive more funding compared to Technology sector in India.
* There is a positive correlation between the stage of development of a company and the amount of funding it receives in India.
* Companies with a larger number of founders are more likely to receive higher amounts of funding in India.
* Startups headquartered in major metropolitan areas such as Mumbai, Bangalore, and Delhi are more likely to receive larger amounts of funding in India.
* The number of investors in a company is positively correlated with the amount of funding it receives in India.
* Is there a relationship between the sector of a company and the amount of funding it receives?
* Is there a difference in the average funding received by companies headquartered in different regions?

## Packages & Libraries
* import pandas as pd
* from scipy.stats import pearsonr
* from scipy.stats import ttest_ind
* import scipy.stats as statst
* from scipy.stats import f_oneway
* from sklearn.preprocessing import LabelEncoder
* import seaborn as sns
* import matplotlib.pyplot as plt
* from scipy.stats import mode
* from sklearn.impute import SimpleImputer


## Cleaning the data. 
* Replacing missing values by using mode of the column
* Dropping values and duplicates
* Renaming values using loc method
* Replacing missing values with averages: This was done by accessing the distribution of the data
* Handling missing values by using loc method.
* Creating a date series to spread the data out in a time frame.
* Convert currency from rupees to dollars by writing a function.
* Filling the missing values in the amount column by: converting the structure of the data and filling  * it the distribution of the data with the aid of a histogram and box plot, Then using the median as standard.
* Restructuring the sector column by first creating a several lists of Keywords realted to different sector industries. Then using the pandas 'str.contain()' method to check if any keyword in each appear in the sector column for each row of the dataframe.If so,it will assign it to the corresponding industry label in the new column created for that row. 


## Running Some Exploratory Data Analysis.
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis

# Statistical Testing.
* A Ttest Statiscal method was employed to test if startups in the E-Commerce & Fintech sector received more funding than those in Technology.
* A Pearsonr test was run to access if there is a positive correlation between the stage of development and funding the company receives.
* Another Pearsonr Test was used to check if the number of founders had an influence in the funding received.
* Anova test was employed to test the significant difference between the hypothesis that Startups based in certain areas had a upper hand to the rest.
* A pearsonr test was used as a bases to check the linear relationship of the hypothesis that number of investors in a company is positively related to the funding amount.

# Answering our Questions with Visualizations.
* These were some of the visualizations tools used in the process of answering our questions:
* Violin plot
* Box plot
* Bar chart 
* Scatter plot 
These visualization added a unique insight into the data and the events surrounding the Indian startup ecosystem.It was a satisfactory overview of our hypothesis test and verification of the facts associated with the data.


# Power BI Deployment
