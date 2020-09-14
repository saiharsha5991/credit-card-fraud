# credit-card-fraud
In this kernal I tired to explain the Credit card fraud with help of Anomaly Detection using Gaussian Distribution.

**Preprocessing steps we are going to explain**


*)Applied PCA(principle component analysis) and kept threshold to 89%(threshold percentage comes from variance in PCA)

*)Based on threshold percentage compressed the columns

*)After PCA,Applied standardisation to keep all values at one range

*)Split the table into train and test model

*)Applied multivariate gaussian on x_train

*)created thresholds [3,3.5,4] to find out anomalies and computed confusion matrix,classification report

   **0 means Non_fraud , 1 means fraud**
   
*)But in confusion matrix True Negative count is 0 on [3,3.5,4] due to 1's lies between -0.5 to 1.35 . So in Normal distributionwe cannot find anomalies.


Kaggle Notebook Link :https://www.kaggle.com/saiharsha1234/creditcard-fraud-detection .

Programing Language used  : Python Libraries used : pandas, numpy, matplot, sklearn

Concepts : PCA,Standardisation,multivariate gaussian,confusion matrix,classification report

Machine Learning Algorithms : Support vector machine .

WORK IN PROGRESS
