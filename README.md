
In this analysis, various data points are taken into account, including loan size, interest rates, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt, and loan status. The objective is to create and assess a model that can determine the creditworthiness of borrowers by analyzing these factors, ultimately helping to assess loan risk.


Logistic Regression Model 1:
.Precision: 93% (in predicting low-risk loans, the model was 100% precise, though the model was only 85% precise in predicting high-risk loans)
.Accuracy: 92%
.Recall: 95% (the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)


Logistic Regression Model 2:
.Precision: 93% (in predicting low-risk loans, the model was 100% precise, though the model was only 84% precise in predicting high-risk loans)
.Accuracy:99%
.Recall:99%

If the model's aim is to assess the probability of high-risk loans, both models fall short of achieving a precision rate exceeding 90%. Among the two, Logistic Regression Model 2 exhibits a lower number of false predictions in the testing data and stands out as the preferred choice due to its impressive accuracy and recall performance
