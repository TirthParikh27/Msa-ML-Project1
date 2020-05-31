# Msa-ML-Project1
Microsoft Student Accelerator Bootcamp 1 project - AI &amp; Machine learning  

spamClassifier.pkl is the package includeing a Tuned Random Forest Regressor Model
Final accuracy on the data in Msa.csv = 95.76%

Steps followed:
0) Arranged the text data from the .names & .data into a .csv file using microsoft excell
1) Loading the data from Msa.csv 
2) Analysing and visualising the data
3) spliting the data into train/test set 80/20
4) Using Gaussian Naive bytes algorithm 
5) comparing it with other algorithms , the accuracy were as follows:
    Gaussian Naive bytes = 81%
    Support Vector machines = 66%
    Decision Tree Classifier = 90%
    Random Forest Classifier = 95.6%
6) Selected to go with Random Forest Classifier
7) Tuned the hyperparameters with GridSearchCV
8) Achiving final accuracy of 95.76%
9) Confusion matrix
10) Packaging the final tuned model in SpamClassifier.pkl
