# Anukriti_Raj_Portfolio

## Project 1: MSBA Summer Capstone Project "Home Credit Default Risk".

### Business problem
Prediction of the Client’s repayment abilities is a challenging task for HomeCredit bank as the company wants not to lose any potential clients who may be capable of on-time loan repayment. The company also wants to empower its clients who may not have sufficient or existent credit history by granting them loans after predicting their repayment abilities, by verifying their alternative data like telco and transactional information, both online and offline.

### Objective
To build and develop a data-driven, credit risk assessment predictive model which evaluates the creditworthiness of customers applying for loans at the Home Credit bank.

### Solution to the business problem
To provide a solution to the aforementioned business problem of lending to customers effectively, our team used the following approach:

1) Data Visualization, Cleaning, and Preprocessing: This included Handling Outliers, missing values, and inconsistencies along with analysing the distribution of various independent variables in the dataset. 
2) Feature Engineering: This step included extraction and creation of meaningful features from the given dataset to provide valuable inputs to the lending model by transforming variables, creating new derived features, and scaling numerical data.
   
3) Handling Imbalanced Data: We also had to address the class imbalance issues, as the loan default cases were significantly lower than the non-default casesby employing intelligent undersampling
   
4) Model Selection and Training with Hyperparameter Tuning: Our team selected multiple models to identify the appropriate machine learning algorithm for credit risk assessment, such as logistic regression, random forests, and light gradient boosting model, and trained them accordingly.

5) Cross-Validation and Evaluation: We then employed cross-validation techniques to validate the performance of the aforementioned predictive models on different subsets of data. We then used evaluation metrics like precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC-ROC) to assess the model's accuracy and reliability.

5) Interpretability and Explainability: Our group then focussed on interpreting the model-based results in a more explainable way, especially in the context of lending decisions. 

On comparison of the performance of these models, the group came to the conclusion that the Light Gradient Boosting Model performed best in terms of Accuracy(72%) and runtime(140.1 sec). This model gave the best result in identifying the probability of a Loan applicant being a defaulter or not based on several features that were identified as major factors in determining the repayment capability of an individual.

My contribution to the project was analyzing Target Variable Distribution, identifying and cleaning missing values, identifying and encoding categorical values, finding relationships between various features and the Target, aligning the train and test dataset, finding the top 10 and last 10 correlation of features with the Target during EDA phase. During the Modeling phase, I mostly worked on the analysis and aligning of Train and Test datasets followed by building of Logistic Regression and Random Forest model. Finally, I ran the models individually on the Kaggle platform to calculate their runtime which helped the group to come to a conclusion of identifying the Best Model for the Business Problem identified in the earlier phase. 

Business Value-
The business problem that we tried to solve here

There were many challenges faced by the group while working on the project like identifying the columns whose removal would cause the least or no impact on our analysis, alignment of Train and Test data in the same ratio as was maintained in the historical dataset, replacing Null values with suitable values in Categorical and Numerical columns, identifying other datasets that could be used for Feature Engineering, building up of various models and introducing hyperparameter tuning in them for getting a better model.

There were many things to learn while working on this project which broadened my thinking as a Data Analyst. Also, figuring out the challenges and overcoming them has given me the confidence to work on any similar kind of issues if they cross my path in the future. Learning the concepts and implementing them practically in a real-world scenario is completely different and I am glad that I got this opportunity to work during my Master's Program.
