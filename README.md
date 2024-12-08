1 Report Introduction 
Stroke, identified as the second leading cause of death worldwide by the World Health 
Organization, accounts for approximately 11% of total global mortality. Recognizing the 
critical impact of strokes on public health, this report focuses on leveraging a dataset to 
predict the likelihood of a patient experiencing a stroke. The dataset incorporates diverse 
patient information, allowing for the development of an AI model trained to estimate the 
probability of a heart stroke occurrence. 



1.1 Dataset identification. 
The Dataset that has been investigated in this report is the “Stroke prediction dataset” 
collected form Kaggle by fedesoriano. This dataset has 11 attributes which contributes in the 
cause of the stroke. 
These attributes are as follows: 

ID: 67 to 72940 (Numerical)  
Defines a user represented by a numerical value as the unique identifier (ID).  

GENDER: Male, Female or Other (Categorical)  
Defines if the user in question is a Male, Female or they identify as another gender.  

AGE: 0 to 100 (Numerical)  
The age of the user in question.  

HYPERTENSION: 0 or 1 (Numerical)  
Defines if the user in question has hypertension or not (High Blood Pressure).  

HEART DISEASE: 0 or 1 (Numerical)  
Defines if the user in question has heart disease or not.  

WORK TYPE: Private, Self-employed, Govt_job, Never_worked and children (Categorical)  
Defines the user in question’s work type, if they’re private, self-employed, government job 
or have never worked; if the user is a child, it will be defined as ‘children’.  

EVER MARRIED: yes or no (Categorical)  
Defines if the user in question has ever been married or not. 

RESIDENCE: Urban or rural (Categorical)  
Defines if the user in question lives in an urban or a rural area.  

AVG GLUCOSE LEVEL: 55 to 272 (Numerical)  
Defines the average glucose level of the user in question.  

BODY MASS INDEX: 10 to 98 (Numerical)  
Defined the body mass index of the user in question.  

SMOKING: formally smoked, never smoked, smokes and Unknown (Categorical)  
3 

This defines the status of the user in question’s smoking activity, if they’re currently 
smoking, formally, never snoke.  

STROKE: 0 or 1 (Numerical)  
This is the target value; it defines if the user in question has had a stroke or not.  
. 
1.2 Supervised learning task identification 
This model focuses on predicting the occurrence of strokes in individuals. It tackles a 
classification problem where the target variable indicates whether a stroke will occur or 
not. Out of the available variables, 10 are directly associated with the prediction of 
strokes. The model utilizes the data from these variables to make predictions regarding 
the likelihood of a stroke occurring. 
