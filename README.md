# Capstone Project
### By: Dayana Kan

## Contents
1. [Introduction](#introduction)
    - [Problem Statement](#problem_statement)
    - [Dataset](#dataset)
2. [Analysis](#analysis)
    - [Data Cleaning](#data_cleaning)
    - [Exploratory Analysis](#exploratory_analysis)
    - [Modeling](#modeling)
 ​   
## Abstract <a name="introduction"></a>
​
The goal of this analysis is to tell a better story of mental health care today by taking a closer look at survey data on adult mental health service utilization. By building a classification model to predict if an adult receives mental health help or not, I am interested in the reasons that may vary by demographic. Using this binary decision as my target variable, I ran a .... classification model to find the most important features/reasons for getting treatment counseling or not. These features can be used to improve the mental health care system in public health arenas, correctional institutions, education, and job industries by making informed data drive decisions.
​
### Problem Statement <a name="problem_statement"></a>
Can we predict whether an adult receives mental health treatment/counseling or not? 
​
### Dataset <a name="dataset"></a>
The dataset is survey data collected from NSDUH 2018 via SAMHSA open data (https://datafiles.samhsa.gov/study-dataset/national-survey-drug-use-and-health-2018-nsduh-2018-ds0001-nid18758) which was filed in 2019. The observations represent heterogeneous responses to questions specific to mental health service utility, adult mental health, treatment/counseling payment, demographics, etc. 
The size of my initial dataset was (28157, 744) row x column. 
​
## Analysis <a name="analysis"></a>

### Data Cleaning <a name="data_cleaning"></a>
Survey data requires ample data cleaning time to ensure columns reflect only relevant questions and answers. Hence, I dropped recoded questions and 'na' type answers coded as 85=BAD DATA, 94=DON'T KNOW, 97=REFUSED, 98=BLANK, 99=SKIP. 
​
### Exploratory Analysis <a name="exploratory_analysis"></a>

### Modeling <a name="modeling"></a>
My analysis used scipy, matplotlib and seaborn to create barplots, Chi-Sq distribution, and scatter plots to explore the data. I used statsmodels and sklearn to create my classification model and validate it.
