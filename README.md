[![CI](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/actions/workflows/cicd.yml)



# IDS706 DataEngineering

_Week 2: Pandas Descriptive Statistics Script_

### 🎯 Objective: 
This project is part of the assignment for week 2 of the course. The main objective of this task is to create a Python script that uses the Pandas library to perform descriptive statistics on a dataset, generate a summary of statistics, and create data visualization that summarize the information.


### 🔍 Dataset: 
For this asigment, we will use the [LinkedIn Tech Jobs dataset](https://www.kaggle.com/datasets/joebeachcapital/linkedin-jobs?resource=download&select=final_data.csv) 

The "LinkedIn Jobs Dataset" is a comprehensive collection of job listings and related information sourced from LinkedIn, one of the world's leading professional networking platforms. This dataset provides valuable insights into job opportunities, job market trends, and various attributes associated with job listings.

### 🧪 Methodology

In this project, the [LinkedInTechJobsDataset.csv](data/LinkedInTechJobsDataset.csv)  was analyzed using a Python script [main.py](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/blob/main/src/script.py) file, which generates the outputs presented in **this Markdown file**

### 📊 Results
We can see certain descriptive statistics of the variables:

- Total_applicants
- Employee_count
- LinkedIn_Followers
  

|          |  Total_applicants |   Employee_count  |LinkedIn_Followers | 
|:---------|------------------:|------------------:|------------------:|
| mean     | 23                | 5178              | 1401891           |
| median   | 8                 | 5000              | 270280            |
| count    | 811               | 811               | 811               |



However, measures of central tendency often conceal the true data distribution, so we create a histogram to visualize its distribution more effectively

![Total_applicants](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/blob/main/output/Total_applicants.png)

![Employee_count](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/blob/main/output/Employee_count.png)

![Total_applicants](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/blob/main/output/LinkedIn_Followers.png)
