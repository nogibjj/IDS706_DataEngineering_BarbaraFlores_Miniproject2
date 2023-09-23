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
If we calculate some descriptive statistics, we obtain the following:

![aggregated_stats](https://raw.githubusercontent.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/main/aggregated_stats.png)

What can we observe regarding the required level of the job postings?"

![Involvement](https://raw.githubusercontent.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/main/output/Involvement.png)

We see that the majority of job postings are for mid-senior and entry-level positions.

A question that arises when analyzing this dataset is: What are the most demanded skills in technology job postings? This can be visualized in the following chart. It is worth mentioning that this chart represents the total requirements for a specific skill out of a total of 811 records in the dataset.

![skills](https://raw.githubusercontent.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/main/skills.png)

We can see that from this sample of job postings, the most demanded skills or tools are AI, UI, Excel, SQL, and Java

### 👥 Histogram of total number of applicants per job posting

![Total_applicants](https://github.com/nogibjj/IDS706_DataEngineering_BarbaraFlores_Miniproject2/blob/main/output/Total_applicants.png)

From the histogram, it is evident that the majority of job postings have more than 500 applicants. This underscores the importance of having a professional profile that can stand out among other applicants.
