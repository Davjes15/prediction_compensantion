# Prediction of Yearly Compensantion based on Skills and Experience

Kaggle hosted an open data scientist competition titled “2018 Kaggle ML & DS Survey Challenge.” 
The purpose of this challenge is to “tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration.” https://www.kaggle.com/kaggle/kaggle-survey-2018
Development of ML models to predict the year compensation of a Data Scientist 

## Getting Started

This README.md file describes the process applied to develop predictive models to approximately forecast the yearly compensation based on a set of variables such as programming skills, major, and experience.

The objectives of this project are:

1. understand and explore employment in the data science community, as represented in a survey conducted by Kaggle.

2. train, validate, and tune multiple regressors that can predict, given a set of survey responses by a data scientist, what a survey respondent’s current yearly compensation is.


### Prerequisites

To run this jupyter notebook, ensure you have installed:
```
!pip install numpy
!pip install pandas
!pip install lxml
!pip install beautifulsoup4
!pip install sklearn

```

### Datasets
The dataset "Kaggle_Salary.csv" is a modified version of the survey results presented by Kaggle in the file "mutiplechoiceResponses.csv." 

```
"Kaggle_Salary.csv" 

```
Description: 

The survey results from 15429 participants are shown in 395 columns, representing survey questions.
Not all questions are answered by each participant, and responses contain various data types.


### Research question
The main research question is:
What could be your yearly compensation (approximate in $USD)?

Moreover, a detailed contrast between developed and developing countries is also provided to highlight disavantages and advantages about the Data Science field in developing countries.


### Notebook structure

In each stage of this project, a detailed description of the pros and cons of a selected approach is discussed as a guide for other researchers that may want to try the same methods.
The jupyter notebooks includes:

```
According to the Country Classification provided by the United Nation, WESP classifies all countries of the world into one of three broad categories: developed economies, economies in transition and developing economies. 
The composition of these groupings is intended to reflect basic economic country conditions. 
Several countries (in particular the economies in transition) have characteristics that could place them in more than one category. For purposes of analysis, the groupings have been made mutually exclusive. 
Based on that information I divided the 58 countries into two groups DEVELOPED COUNTRIES and DEVELOPING COUNTRIES.

```

A. Data Cleaning & Data Encoding

B. Exploratory Analysis & Business Case Analysis (Developed and Developing Countries)

C. Model Preparation

D. Model Implementation

E. Model Tuning (Hyperparameters)
 
F. Test & Discussion of results
