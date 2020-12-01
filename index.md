## Welcome to the Heart disease diagnositic ML project Page
Cardiovascular disease includes a wide range of conditions affecting heart and arteries. In this project, a
publicly available dataset which consists of 70000 observations of potential patients is obtained from 
[here](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset). The dataset is based on 11 features and
a label of whether the patient observed suffers from a cardiovascular disease (y = 1) or not (y = -1) . The attributes may be
categorized as objective, examination and subjective. Objective attributes are based on factual information,
while the subjective ones are basically information given by the patients themselves.

The main goal of this project is to utilize different machine learning algorithms to obtain a classifier for
predicting cardiovascular disease with reasonable accuracy. The main tasks are preprocessing the dataset,
training a learner using three different algorithms to classify whether a patient has a cardiovascular disease
and comparing the global performance of each algorithm using cross-validation scheme to avoid overfitting.
The dataset is to be divided into 7 sets, each with 10000 datapoints and shall be used interchangeably for
training and evaluation purposes. The algorithms to be learned are as follows:

• **Linear regression with least squares**

• **Ridge Regression and LASSO with cross-validation**

• **K-nearest neighbours**

• **Linear SVM using stochastic Gradient descent**

• **Neural networks with 2 layers**
## Data Processing 

• **The raw data is loaded into a features matrix X and a labels vector y** 

• **Outliers in the data are removed and the gender feature entries are converted into '1' and '-1' ** 

• **The dataset is found to be balanced** 

• **The mean is subtracted from the features matrix X for linear regression classification purposes**

• **The Age,height,weight, api_high and api_low distributions of the postprocessed data are**

![Figure1](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/POSTPROCESS.JPG)

## Modeling Insight

Some Modeling Insights can be found [here](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/gh-pages/results.md)

## The performance metrics of the classifiers tested 
![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/ACCUR_CLASS.JPG)

Last Updated: 12/01/2020
