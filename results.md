

## Results at a Glance: 

The data is loaded and preprocessed apropri and the  features matrix X is decomposed using SVD decomposition. The logaritmic distribution of the singular values is shown as 


![Figure1](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/singular_log.JPG)


It is noticed that the most information is gained from the first five features. 
Three classifiers were trained in order to classify the cardiovascular disease.

### The residuals of the three Classifiers (LS,Ridge,LASSO)
![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/resd_ls_r_lasso.JPG)
### The Accuracy % of the three Classifiers (LS,Ridge,LASSO)
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/Accuracy_LS_R_LASSO.JPG)

The most accurate classifier is the one trained using the Least Squares solutions with the least residual. However, the LASSO offers a sparse solution with minimal accuracy setbacks.
