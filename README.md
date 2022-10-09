# No-Show Appointment

## Dataset 

The No-Show Appointment dataset contains information collected from
over 100k medical appointments in Brazil. 
Its features include the patient id, appointment id, gender, age, 
neighbourhood (location of hospital), sms_received, scheduled day, appointment day, 
scholarship (for patients enrolled in the Brasillian welfare program), 
four health challenge categories: hypertension, diabetes, alcoholism, and handicap, 
and the no_show feature which tells whether the patient showed up for the appointment or not.
The dataset can be found [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv) on Kaggle.


## Aim of Analysis 

The analysis of the dataset will be used to answer the following questions:

• Do more patients enrolled in the Brasillian welfare program make their appointment? By how much? 

• What age group of patients are less likely to show up for their appointment? 

• Does receiving SMS affect the turn-up of patients? 

• What age group do the majority of patients who do not show up for their appointment and are enrolled in the Brasillian welfare program belong to? 

• What is the proportional distribution of patients in each health challenge category?


## Installation 

``` 
import numpy as np 

import pandas as pd 

import matplotlib.pyplot as plt 

import seaborn as sns 

%matplotlib inline

sns.set_style("darkgrid") 
```


## Summary of Findings 

Exploratory analysis of the data showed that a larger number of 
patients are not enrolled in the Brasilian welfare program, and most patients enrolled in 
the program do not show up for their appointment, particularly adults. 
In each health challenge category, a higher proportion of patients do not show up for their appointment, 
and the majority of patients are hypertensive. 
Also, generally, youths are less likely to show up for their appointment, 
and receiving SMS has no significant positive effect on the outcome of the medical appointment.

