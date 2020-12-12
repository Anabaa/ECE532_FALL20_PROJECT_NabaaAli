

## Modeling Insight: 

The data is loaded and preprocessed apropri and the  mean-subtracted features matrix X is decomposed using SVD decomposition. The logaritmic distribution of the singular values is shown as 


![Figure1](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/singular_log.JPG)


It is noticed that the most information is gained from the first five singular values. 


### Least squares, Ridge and LASSO regression 
The least squares classifier performed on with an average error rate of 27.54 % and the residual 〖||Xw-y||〗_2= 86.84 (Cross-validation with data split into 7 sets)
Ridge regression was used to train a classifier to ensure minimal sensitivity to noise and small disturbances. Cross validation was used to choose the optimum penalty 
(λ value). The average error rate for ridge regression is equal to 27.48 % and the residual 〖||Xw-y||〗_2 = 86.99 . 	To obtain a sparse solution, LASSO classifier was trained using iterative thresholding and cross validation to choose the optimum penalty (λ value). The error rate for this classifier is 28.03% and the squared residual is 88.29. Although the average error % and the squared residual both increased compared to ridge regression and LS, Interestingly the sparsity of the weights vector w was equa to 8. In other words, 4 features are sufficient for classification purposes with minimal accuracy setbacks.

### LS with 8 features
The 8 features selected using LASSO regression were trained using the Least squares (Debiasing) and the average error % is equal to 27.58 %. The selected features are age,height,weight, api_high,api_low,Cholestrol,Glucose and physical activity. 

### Linear SVM 
A Linear SVM classifier was trained using all the features and  SGD along with cross validation to select optimum regularization value. The average error for SVM is 28.64 % 
### Neural Networks 

Two biologically-inspired neural networks were deployed to classify the samples using SGD and the logistic activation function. The networks are depicted as follows: 

![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/NN2.JPG)
The performance of the first network using 11 nodes in the hidden layer and a learning rate of 0.01 can be seen below in ![Figure3](a) 
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/1NN_PER.JPG)
The performance of the second network using 11 nodes in each hidden layer and a learning rate of 0.01 can be seen below in ![Figure3](b) 
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/2NN_PER.JPG)

### The residuals of classifiers tested
![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/Residuals.JPG)
### The Accuracy % of classifiers tested
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/Accuracy_final.JPG)

The results  prove that neural networks achieved optimal performance metrics,
while SVM performed the worst on the dataset in consideration. The central shortcoming of the
neural networks was that they trained slowly, and using batch stochastic gradient descent might
expedite the training process. It was noticed that the accuracy of the classifiers throughout this project,
peaked at 73.5%. This performance may be due to the nature of the dataset itself, and therefore
further accuracy gains may be achieved, if the dataset included:
• features such as race, specific genes, family medical history, intesity of pyshical activity, etc.
• A gender-balanced dataset.
• Numerical values implying the smoking intesity and the level of alcoholic consumption.
A final note would be that all the results are easily reproducible using the codes published on the
project’s public repository.



Last Updated : 12/12/2020
