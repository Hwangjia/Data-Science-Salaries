# Data-Science-Salaries
Analyzing Data Science Salaries And Comparing Them To The Domestic Average Annual Salary. 
<br>Kaggle link: https://www.kaggle.com/code/jiahwang/fork-of-data-science-salaries-practice

# Data Source
The datasets are readily available on Kaggle and includes the following:
  1. Average Annual Wages by country from OECD
  2. Data Science Job Salaries
  3. ISO Country Codes - Global

Main dataset for Data Science Salaries was obtained from: https://salaries.ai-jobs.net/download/

# Scenario
Assumption is that the data obtained provides (possibly) an accurate representation of the salaries of data scientist.

The objective of this analysis is to identify whether the salaries of data scientist (or data analytics related jobs) are above the average annual salary relative to the Country in which the employee is situated in and in the relevant years.


# Steps related to datasets:
  1. The beginning focuses on the main dataset, Data Science Job Salaries, and further analyzing the observation distributions based on the variables.
  2. Since the company_location variable in the main dataset is listed under a ISO Country code. The ISO Country Codes - Global dataset is used to assist in merging the
     Average Annual Wages by Country from OECD with the initial dataset as a single dataframe.
  3. Finally, the salaries of respondents in main dataset will then be compared with the respective country's average annual salary.
  4. All findings are interpreted through the use of graphs made using the plotly package as shown below.

# Graph examples
![newplot (1)](https://user-images.githubusercontent.com/62349308/187069241-12a2efc6-2709-416e-8aac-6b82709b1c5e.png)
![newplot (2)](https://user-images.githubusercontent.com/62349308/187069265-949cc105-17f3-451a-8116-69b52f45e611.png)
