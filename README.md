# CloudForensics
This application is detecting cloud attack data - its a part of group project

Cloud Computing is ubiquitous now-a-days because of its scalability, accessibility, and cost-effectiveness. Cyberse curity is one of the biggest challenges in cloud computing as the customer resources are compromised during the attack. The attackers often use Virtual Machines to attack anonymously. In this project, we are proposing the application of various supervised and unsupervised machine learning algorithms for detecting attacks based on the collected evidence. The Evidence Detection in Cloud forensics dataset will be used from IEEE Data Port. The target variables are labeled as the binary state of attack or normal to corresponding virtual machines. We will provide a comparison analysis of the performance of the machine learning models used in this study. 

Multiple ML models were performed for detection system including 
- Linear Regression
- Naive Bayes
- KNN with Genetic Algorithm
- Decision Trees
- Logistic Regression
- XGBoost
- Logistic Regression
- SVM

Although all of the models performed very well on data among all above mentioned approaches XGBoost was the best and NB was the one with the least measures of accuracy.

The performance was measured by:
- Percision
- Recall
- F-1 Score
- Accuracy
- Kappa
