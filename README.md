# Election-Exit-Poll-Prediction-and-U.S.A-Presidential-Speech-Analysis-using
## Course Machine Learning  This project is based on 2 case-studies: Vote Prediction and Text Analysis. 
#### 1. The first project is to predict which party a citizen is going to vote for on the basis of their age and according to the answers given by the citizens to the questions asked in a survey conducted. 
#### 2. The second project is based on the analysis of the inaugural U.S.A. Presidential speeches. 
### One has to draw inferences based on the analysis done on these speeches.  
### Skills and Tools ---- Text Mining Analytics, Support Vector Machine - K Nearest Neighbour - Naive Bayes, Ensemble Techniques, Logistic Regression - Linear Discriminant Analysis
![image](https://user-images.githubusercontent.com/87828805/153252428-a571d5e7-e79f-423a-a013-49ce2be804e5.png)


------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/87828805/153252615-735b0fdc-e4cd-497a-82a1-f5a228a0ac0f.png)

From the above Comparisons metrics and models comparison tables we inferred the below followings points 
1) Accuracy – 
•	Highest accuracy is given by XGB model of 89% and lowest by SVM model of 83% for the training dataset.
•	Highest accuracy is given by MNB model of 83% and lowest by SVM model of 80% for the test dataset.
2) AUC – 
•	Bagging is having the highest AUC score of 96% and lowest shown by 5 models which are LR, LDA, KNN, MNB, and SVM Model of equal value of 90% for the train dataset.
•	Highest AUC score is shown by bagging model of 90% and lowest shown by KNN model of 85% for the test dataset.

3) Recall –   1 – Majority and 0 - Minority
•	For minority class bagging classifier performed highest of 86% and lowest perform by the LDA and KNN of about 71% for train dataset.
•	For majority class, XGB model performed highest of about 94% and lowest performed by 81% for train dataset.
•	For minority class LR and SVM performed better of about 82% and lowest performed by KNN of about 60% for the test dataset.
•	For Majority class, KNN performed better of 89% and lowest by SVM of about 79% for the test dataset.

4) F-1 Score – 1 – Majority and 0 - Minority
•	For minority class bagging classifier performed highest of 82% and lowest perform by the MNB of about 73% for train dataset.
•	For majority class, XGB model performed highest of about 92% and lowest performed by SVM of about 87% for train dataset.
•	For minority class LR, MNB and Bagging classifier performed highest of 71% and lowest perform by the KNN of about 64% for test dataset.
•	For Majority class, MNB performed better of 88% and lowest by SVM of about 85% for the test dataset.

------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/87828805/153252870-3605ffd3-92fe-4f2d-a67f-7d87b8a0d146.png)

•	Here 10 fold cross validation has been used. The highest mean accuracy is of KNN train and XGBoost train of about 85%.
•	LDA train is performing the lowest of about 74% of mean accuracy.
•	LDA train has got the highest inconsistency with 20% std deviation. LDA train, SVM train, bagging train, bagging test has got lowest std deviation of 3%.

-------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/87828805/153253346-db33aad0-b95a-45bb-a8a2-044d950ad145.png)

•	Bagging and XGBoost models tend towards defining high variance in train but fails to perform in test, creating over fit models.

•	Gradient boosting models like XGBoost would performs extremely well in the large datasets than the smaller ones.

•	Bootstraps requires high mathematics calculations and may pose low performances challenges.

•	Parametric models like Logistic Regression and Naive Bayes showed better consistency in class predictions and in mathematical calculations also.

•	LDA showed least consistency in 10 fold cross validation and KNN gave the least recall of minority class in train and test dataset.

•	On cross validation Recall across both the target classes and consistent accuracy on both train and test dataset, Logistic Regression, SVM and MNB can be chosen for final model.

As we know from the above , Naïve Bayes test accuracy is 83% and LR, LDA, KNN and XGB is 81% 
And XGB is having the highest train accuracy 89% and least is shown by SVM 83%
### So, overall MNB is chosen as the best optimized model for the dataset.
As the difference between the Train and test accuracy is minimum as compared to other models.
