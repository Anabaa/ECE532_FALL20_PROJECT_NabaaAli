# FA20/ECE532/Project Proposal
#Project Description
Cardiovascular disease includes a wide range of conditions affecting heart and arteries. In this project, a publicly available dataset which consists of 70000 observations of potential patients is obtained from https://www.kaggle.com/sulianova/cardiovascular-disease-dataset. The dataset is based on 11 features and a label of whether the patient observed suffers from a cardiovascular disease or not. The attributes may be categorized as objective, examination and subjective. Objective attributes are based on factual information, while the subjective ones are basically information given by the patients themselves. 
The Features and their type/name in csv file/ (unit) are explained as follows:
1.	Age | Objective Feature | age | int (days)
2.	Height | Objective Feature | height | int (cm) |
3.	Weight | Objective Feature | weight | float (kg) |
4.	Gender | Objective Feature | gender | categorical code |
5.	Systolic blood pressure | Examination Feature | ap_hi | int |
6.	Diastolic blood pressure | Examination Feature | ap_lo | int |
7.	Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
8.	Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
9.	Smoking | Subjective Feature | smoke | binary |
10.	Alcohol intake | Subjective Feature | alco | binary |
11.	Physical activity | Subjective Feature | active | binary |
12.	Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

The main goal of this project is to utilize different machine learning algorithms to obtain a classifier for predicting cardiovascular disease with reasonable accuracy. The main tasks are preprocessing the dataset, training a learner using three different algorithms to classify whether a patient has a cardiovascular disease and comparing the global performance of each algorithm using cross-validation scheme to avoid overfitting. The dataset is to be divided into 7 sets, each with 10000 datapoints and shall be used interchangeably for training and evaluation purposes. The algorithms to be learned are as follows: 

•	Linear regression with least squares 

•	K-nearest neighbors with k = 45

•	LASSO regression

•	Support vector machines 

•	Neural networks with 2 layers 

However, Additional algorithms may be implemented to further increase the accuracy of the learner and updates to this proposal may be posted on the GitHub project site. A public repository of the project codes, results and dataset are available at GitHub link: 
https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli



Outline

The dates for completing the tasks and final submission are initially anticipated as in table (1). Deadlines for 1st update, 2nd update and the final report submission are fixed by instructor. 

Table 1: A Rough outline for the project
Task	Anticipated Completion Date
Data Preprocessing and Cleaning	10/23/2020
Linear Regression Using Least Squares	11/03/2020
Lasso Regression	11/14/2020
1st Update	11/15/2020
Neural Network	11/27/2020
2nd Update	11/29/2020
Final Report Submission	12/14/2020


Student Information
University of Wisconsin – Madison 
Name: Ali Nabaa
Class: ECE532/SEC004
Email Address: nabaa@wisc.edu

Acknowledgments 
I would like to express my gratitude to Svetlana Ulianova for making this dataset and the corresponding features description, publicly available on Kaggle. 

References
•	https://www.kaggle.com/sulianova/cardiovascular-disease-dataset.
•	https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli
