# credit-card-fraud
In this kernal I tired to explain the Credit card fraud with help of Anomaly Detection using Gaussian Distribution.

**Preprocessing steps we are going to explain**
1)Import libraries

2)checked the data types

3)Applied PCA(principle component analysis) and kept threshold to 89%(threshold percentage comes from variance in PCA)

4)Based on threshold percentage compressed the columns

5)After PCA,Applied standardisation to keep all values at one range

6)Split the table into train and test model

7)Applied multivariate gaussian on x_train

8)created thresholds [3,3.5,4] to find out anomalies and computed confusion matrix,classification report

   **0 means Non_fraud , 1 means fraud**
9)But in confusion matrix True Negative count is 0 on [3,3.5,4] due to 1's lies between -0.5 to 1.35 . So in Normal distributionwe cannot find anomalies.


Dataset :https://www.kaggle.com/saiharsha1234/creditcard-fraud-detection . Tools used : Python Libraries used : pandas, numpy, matplot, sklearn, Concepts : PCA,Standardisation,multivariate gaussian,confusion matrix,classification report, Machine Learning Algorithms : Support vector machine .
