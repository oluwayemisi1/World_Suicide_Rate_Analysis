# Introduction
Suicide rate is a serious public problem. It is the act of intentionally causing one’s own death. The world health organization estimated that over 700,000 dies due to suicide every year. Many suicide happens impulsively in moments of crisis with a breakdown in the ability to deal with the stress of life. suicide was the second leading cause of death among the 25-35 year sold globally in 2016. Hence it is quite clear that suicide is a global concern that should be analyzed.
Hence, this project contains a case study, analysis and visualization of Suicide rate of some part of the country. 

## Contents
1. Aim
2. Data Sourcing 
3. Data Cleaning
4. Exporatory Data Analysis
5. Data Visualization
6. Findings and Recommendation

## Aim
My aim of doing this project is to get valuable and meaningful insight of how the Suicide Rate has increased or decreased across the countries. 

# Resources and code used
**The dataset i used was gottem from Kaggle, which includes (27820 Rows and 10 Columns) and the columns were made of:**
* Country
* year
* sex
* age 
* generation
* suicides_no : The number of suicide.
* population : the Total number of people.
* suicides/100k pop: The number of the death by suicide for a total 100.00 deaths
* country-year
* HDI for year : The Human Development index of the year
* gdp_for_year($) :Domestic Product per capital  
* gdp_per_capita($) : Gross Domestic Product divided by midyear population
* The analyis was done using Python programming language, on jupiter notebook for both analysis and visualization.

**Packages used:**
* PANDAS: i used pandas to import my dataset and handle the messy data , NUMPY: was used it to work on array and for mathmatical operations, SEABORN and MATPLOTLB was used for the visualization 

# Data Cleaning
After downloading the data from GitHub, I needed to clean the data in order to  perform an Exploratory data analysis. First i checked for missing data and discovered there were some missing data i needed to fix which i did using pandas. I renamed some columns which were misspelt and replaced the space in the columns with underscore,i also dropped a duplicated column.I detected outliers and removed it. 

# Exporatory Data Analysis
I looked at the distribution of the data and the value counts for various categorical values. After analyzing the data using python.
**I grouped some columns inorder to get an insight of the data and visualize** 
1. Group by year and Suicide : At what yeat was the suicide number high?
2. Group by Age and Suicide_no : What age commits Suicide more? 
3. Group by Country and population : What Country has the highest number of population?
4. Group by Year and Suicide_pop : In what year was the suicide_pop high?
5. Group by Sex and Suicide_no : what Gender commits suicide more?
6. Group by Generation ad Suicide_no : Which Generation commited Suicide more?

# Data Visualization 
After exploring the data, i then visualized it on Jupiter notebook using python and also on power BI.
Checkout the full project here [Suicide_Rate(1987-2016)](https://github.com/oluwayemisi1/World_Suicide_Rate/blob/main/suicides%20Rate%20(1).ipynb).
![suicide](https://user-images.githubusercontent.com/48946643/185417434-7baac0c7-20d2-4f38-b07e-9ad050a5bfb5.PNG)


# Findings and Recommendations

