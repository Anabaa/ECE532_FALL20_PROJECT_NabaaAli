## Welcome to the Heart disease diagnositic ML project Page
Every year, more than half a million Americans die from CVD’S, that’s about 25% of total deaths.[2]
Cardiovascular diseases include a wide range of conditions mostly affecting the heart and arteries.
Individuals at risk of CVD often experience raised blood pressure, glucose, and LDL (cholesterol)
levels as well as excessive alcohol consumption and obesity. Early classification of CVD may help
in preventing premature death, save resources, and increase productivity. In this project, a publicly
available dataset which consists of 70000 observations of examined individuals is obtained from:
[here](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset). 

The dataset is based on the 11 features  and a corresponding label of whether the patient
observed, suffer from cardiovascular disease or not. The features were categorized as objective,
examination, and subjective. Objective features are based on factual information, while the subjective
ones are basically the information given by the patients themselves.


The main goal of this project is to utilize different machine learning algorithms to train several binary
classifiers and predict cardiovascular diseases among individuals with reasonable accuracy. Tasks to
be performed include preprocessing, training three classifiers and comparing the global performance
of each trained classifier. Overfitting occurs when the classifier learns a lot about the training data
and fails to generalize on new points. Cross-validation was used to assess how well each classifier
generalizes beyond training data and thus minimize overfitting. Accordingly, the samples were
divided into 7 datasets such that each set is used interchangeably for training and evaluation purposes.
• **Linear regression with least squares**

• **Ridge Regression and LASSO with cross-validation**

• **Linear SVM using stochastic Gradient descent**

• **Neural networks with 1 and 2 hidden layers**

## Data Processing 

The downloaded dataset contains 70000 samples, none of which have missing entries. However, it
may contain duplicate samples or input errors due to human error. So, the dataset was checked for
duplicates, and 24 duplicate samples were excluded. Additionally, some erroneous samples were
omitted as they contained unrealistic entries and special cases (dwarfism and ultra-tall individuals),
as they have their patterns and tendencies when it comes to anatomy and general wellness[3]. For
instance, people suffering from dwarfism have a ten-fold increased risk of suffering from CVD’s. The
criteria showed in Table 2 was used for outliers omission.

![Figure1](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/PREPROCESSING_V.JPG)

## Modeling Insight and Results 

Some Modeling Insights and results can be found [here](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/gh-pages/results.md)

## The performance metrics of the classifiers tested 
![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/Accuracy_final.JPG)

Last Updated: 12/12/2020
