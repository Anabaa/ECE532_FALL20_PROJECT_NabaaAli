

## Modeling Insight: 

The data is loaded and preprocessed apropri and the  mean-subtracted features matrix X is decomposed using SVD decomposition. The logaritmic distribution of the singular values is shown as 


![Figure1](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/singular_log.JPG)


It is noticed that the most information is gained from the first five singular values. 

### K-nearest neighbours 

The KNN algorithm was tested on a randomly selected 200 datapoints for different K values. 
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/K_ERROR.JPG)

from the figure above, K= 14 was selected for obtaining the performance of the KNN on 1800 evaluation datapoints. Larger evaluation datasets were computationally expensive as the KNN algorithm is known to be slow.

### Least squares, Ridge and LASSO regression 
The least squares classifier performed on with an average error rate of 27.54 % and the residual 〖||Xw-y||〗_2= 86.84 (Cross-validation with data split into 7 sets)
Ridge regression was used to train a classifier to ensure minimal sensitivity to noise and small disturbances. Cross validation was used to choose the optimum penalty 
(λ value). The average error rate for ridge regression is equal to 27.48 % and the residual 〖||Xw-y||〗_2 = 86.99 . 	To obtain a sparse solution, LASSO classifier was trained using iterative thresholding and cross validation to choose the optimum penalty (λ value). The error rate for this classifier is 28.03% and the squared residual is 88.29. Although the average error % and the squared residual both increased compared to ridge regression and LS, Interestingly the sparsity of the weights vector w was equa to 8. In other words, 4 features are sufficient for classification purposes with minimal accuracy setbacks.

### LS with 8 features
The 8 features selected using LASSO regression were trained using the Least squares (Debiasing) and the average error % is equal to 27.58 %. The selected features are age,height,weight, api_high,api_low,Cholestrol,Glucose and pyshical activity. 

### Linear SVM 
A Linear SVM classifier was trained using all the features and  SGD along with cross validation to select optimum regularization value. The average error for SVM is 28.64 % 

### The residuals of classifiers tested
![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/RESD_CLASS.JPG)
### The Accuracy % of classifiers tested
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/ACCUR_CLASS.JPG)

Ridge classifier and the LS classifier are almost equal in terms of accuracy with the LS having a slightly smaller squared residual. The SVM and the LASSO are comparable in terms of accuracy.



Last Updated : 12/01/2020
