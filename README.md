# About
This project is about analyzing the relationship between salary, job satisfaction and years of programing (a.k.a job experience) of developers from the US. This analysis is based on the data of Stackoverflow’s 2017 Annual Developer Survey (see https://www.kaggle.com/stackoverflow/so-survey-2017/data#). The analysis follows the CRISP-DM process.

The analysis is done in juypter notebook with python 3 and the help of pandas, numpy and seaborn.
You find it in the following file: uda_project1.ipynb

The main question I'm trying to answer is, if salary is a suitable measure to influence ones job satisfaction. I will break down this question with into the following three question:
* Q1: What is the relationship between JobSatisfaction and Salary?
* Q2. What is the relationship between Salary and YearsProgramJob (Experience)?
* Q3: What is the relationship between JobSatisfaction and YearsProgramJob (Experience?)

The key findings are, that there is a correlation between salary and job satisfaction, however the causality is not clear. It is not the result of salary increase based over years of job experience.

See also my medium post with some condensed interpretation: https://medium.com/@252.at.work/salary-expericene-and-job-satisfaction-6b2fb974b849

The analysis is done in jupyter notebook. The survey data is not included in this repository; you will need to download it from the kaggle link above. You will need the following python packages to run this jupyter notebook successfully. (You can install them via pip install <package>)

## Required Python Packages
* jupyter==1.0.0
* matplotlib==3.2.1
* numpy==1.18.2
* pandas==1.0.3
* seaborn==0.10.0
