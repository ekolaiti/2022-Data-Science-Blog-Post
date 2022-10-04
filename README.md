**2022 Data Science Blog Post**. 
  
Description:  
The 2022 Stack Overflow Annual Developer Survey has over 70,000 responses collected from more than 180 countries. I performed data analysis of the survey responses to look into how the country of residence can affect salary and working conditions, and what programming language preferences are recorded in relation to years of professional experience. In specific the aim of this analysis is to answer the following 3 questions:  
    - Question 1. Which programming languages are used by the most experienced developers?  
    - Question 2. How does the country of residence relate to salary and years of professional experience?  
    - Question 3. How flexible are the working conditions in the different countries?   
    
The findings of this data analysis are presented in this blog post:  
https://medium.com/@irene.kolaiti/its-where-you-live-not-what-you-know-5ed4b8c62ec3
  
This repository includes besides this README file the following file:  
blog_09_2022.ipynb - A Jypyter notebook with the data analysis steps that I followed for this project.  
  
I tried repeatedly to upload the survey data but I couldn't synch the data files into this repository. 
Please download the following csv files with the survey raw data and schema from the following link: 
Go to https://insights.stackoverflow.com/survey download stack-overflow-developer-survey-2022 and then unzip and copy these two files in the same place that you have the Jupyter notebook.   
1 - survey_results_public.csv - CSV file with main survey results, one respondent per row and one column per answer.   
2 - survey_results_schema.csv - CSV file with survey schema, i.e., the questions that correspond to each column name.   

* Findings  
    * Q1 - Javascript, HTML/CSS and SQL are the top three languages used overall. Bash/Shell, SQL, Delphi and C# are more popular with the ‘15 and over’ developers, while the ‘less than 15’ years group shows preference for Python, HTML/CSS and JavaScript.  
    * Q2 - The country of residence has a significant impact on the salary that professionals with the same years of experience earn. Higer payscales are recorded for the USA, Canada, and the UK compared to Brazil, India, Poland and Spain.  
    * Q3 - Working fully remotely or hybird (some remote, some in-person) is the dominant working pattern recorded for all of the countries. For 2022 Canada, Poland and the UK have the smallest percentage of fully in-person work, whilst India has the largest percentage.   
    
To run the Jupyter notebook you need to import the following libraries: 
import numpy as np   
import pandas as pd   
import matplotlib.pyplot as plt   
import seaborn as sns   
    
Acknowledgment: A massive thank you to Stack Overflow for allowing access to the data.
