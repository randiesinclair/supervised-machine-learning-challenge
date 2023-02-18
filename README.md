# Supervised Machine Learning

In this project, we aim to classify the risk level of loans using machine learning models. We will be using data from lending services companies and comparing the performance of two popular models: Logistic Regression and Random Forest Classifier.

To begin, we will predict which model we think will perform better and justify our prediction based on information about the models. Next, we will split the data into training and testing sets, and create a features DataFrame and a labels set using the loan_status column.

We will then create and fit both the Logistic Regression and Random Forest Classifier models using the training data. The models will be evaluated based on their accuracy scores, confusion matrix, and classification report.

Finally, we will compare the actual performance of the two models and see if it matches our initial prediction. By the end of the project, we will have gained hands-on experience in building, training, and evaluating machine learning models for classification tasks.

# Technical Skills
- Machine Learning
- Building and training models
- Logistic Regression model
- Random Forest Classifier model
- Data Analysis

# Parameters
### Retrieve the Data
- Import the lending_data.csv file as a Pandas dataframe
- Confirm that the import was successful by displaying the dataframe
<img src="https://user-images.githubusercontent.com/109693942/219884182-986898f2-cc07-4843-8c95-b495370a7e74.png" width="50%" height="50%">

### Predict Model Performance
- Make a prediction on which model will perform better on the data
- Justify the prediction with information about the models
<img src="https://user-images.githubusercontent.com/109693942/219884519-068ed6bc-1ed7-4a47-bfcb-dba8e1da9aca.png" width="80%" height="80%">

### Split the Data into Training and Testing Sets
- Create the features DataFrame, X, by removing the loan_status column
- Create y, the labels set, by using the loan_status column
- Split the data into training and testing datasets by using the train_test_split function
<img src="https://user-images.githubusercontent.com/109693942/219884637-3c726e4f-63ca-4f3e-b244-2d051e0333a4.png" width="90%" height="90%">

### Create, Fit and Compare Models
- Create and train a Logistic Regression model
- Score the Logistic Regression model
- Create and train a Random Forest Classifier model
- Score a Random Forest Classifier model
- State which model performed better
- Compare the actual model performance with your predictions

![image](https://user-images.githubusercontent.com/109693942/219885236-1286c881-4363-41ef-a399-90cfcef44f50.png)
