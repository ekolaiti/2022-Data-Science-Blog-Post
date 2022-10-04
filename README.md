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

Results:   
Question 1. Bash/Shell, SQL, Delphi and C# are more popular with developers that have ‘15 and over’ years of experience, while the ‘less than 15’ years group prefers Python, HTML/CSS and JavaScript.    
For Question 2 and Question 3 I focused on the 10 countries with the most survey responses. I found that:   
Question 2. Living in the USA, Canada or the UK comes with higher pay scales for the same years of experience. On the other end there is Brazil, India, Poland and Spain.   
Question 3. Canada, Poland and the UK have the smallest percentage of fully in-person work, whilst India has the largest.  
    
To run the Jupyter notebook you need to import the following libraries: 
import numpy as np   
import pandas as pd   
import matplotlib.pyplot as plt   
import seaborn as sns   
    
Acknowledgment: A massive thank you to Stack Overflow for allowing access to the data.
