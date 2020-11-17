

## Results at a Glance: 

The data is loaded and preprocessed apropri and the  features matrix X is decomposed using SVD decomposition. The logaritmic distribution of the singular values is shown as 


![Figure1](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/singular_log.JPG)


It is noticed that the most information is gained from the first five singular values. 
Three classifiers were trained in order to classify the cardiovascular disease.

### The residuals of the three Classifiers (LS,Ridge,LASSO)
![Figure2](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/resd_ls_r_lasso.JPG)
### The Accuracy % of the three Classifiers (LS,Ridge,LASSO)
![Figure3](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/blob/pdf/Accuracy_LS_R_LASSO.JPG)

Ridge classifier and the LS classifier are almost equal in terms of accuracy with the LS having a slightly smaller squared residual. The LASSO algorithm offers a sparse solution (sparsity at optimum penalty ranges between 1 and 4) with a slighlty compromised accuracy.



Last Updated : 11/17/2020
