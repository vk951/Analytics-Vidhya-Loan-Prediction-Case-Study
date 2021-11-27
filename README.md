# Analytics-Vidhya-Loan-Prediction-Case-Study
Loan Prediction Case Study-Create a ML model that will determine whether the loan for particular customer requests based on provided data from bank database account should be approved or not
![image](https://user-images.githubusercontent.com/80028817/143680314-c98f9058-6d87-4107-874e-a9537adaece5.png)
Data were provided  such as Loan ID, Gender , Married status, Applicant Income, Coapplicant income, Property area status, Credit History Status and Loan_Status_Approval data for the train data.


Tasks Performed
 i)Data Cleaning and missing data values putting
 ii)Finding the attribute which is not important for our data such as Loan Id and Gender according to me dosen't goes for making of decision of Loan approval.
 iii)Checking if missing data values are there then replace it with appropriate values eeither using mean or using research on data we can find out which data vallues may be appropriate to fill the gaps.
 iv)Label Encoding for categorical variables to convert the string in the form of integer values which will be easy for ML models to process and optimise.
 v)Applying ML model and check the accuracy score and take out the predicted result according to the model and check it with the Analytics Vidhya Solution Checker to find out the accuracy of the coming result from the model.
 I have used Random Forest Classifier , Logitic Regression Classifier and Support Vector Machines Support Classifier and i found the Logistic Regression is providing the optimised result with 0.78333333333333 according to the data prepared and also according to the attributes we choose for classification all the above three classification models are giving the result in the range of0.71-0.78 on the scale of 1
 
