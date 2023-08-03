# Anukriti_Raj_Portfolio

## Project 1: MSBA Summer Capstone Project "Home Credit Default Risk".

##### Table of Contents  
[Business problem](#Businessproblem)  
[Emphasis](#emphasis)  
   
<a name="Businessproblem"/>
### Business problem
Prediction of the Client’s repayment abilities is a challenging task for HomeCredit bank as the company wants not to lose any potential clients who may be capable of on-time loan repayment. The company also wants to empower its clients who may not have sufficient or existent credit history by granting them loans after predicting their repayment abilities, by verifying their alternative data like telco and transactional information, both online and offline.

### Objective
To build and develop a data-driven, credit risk assessment predictive model which evaluates the creditworthiness of customers applying for loans at the Home Credit bank.

### Solution to the business problem
To provide a solution to the aforementioned business problem of lending to customers effectively, our team used the following approach:

1) **Data Visualization, Cleaning, and Preprocessing**: This included handling outliers, missing values, and inconsistencies along with analyzing the distribution of various independent variables in the dataset. 
2) **Feature Engineering**: This step included extraction and creation of meaningful features from the given dataset to provide valuable inputs to the lending model by transforming variables, creating new derived features, and scaling numerical data.
3) **Handling Imbalanced Data**: We also had to address the class imbalance issues, as the loan default cases were significantly lower than the non-default cases by employing intelligent undersampling
4) **Model Selection and Training with Hyperparameter Tuning**: Our team selected multiple models to identify the appropriate machine learning algorithm for credit risk assessment, such as logistic regression, random forests, and light gradient boosting model, and trained them accordingly.
5) **Cross-Validation and Evaluation**: We then employed cross-validation techniques to validate the performance of the aforementioned predictive models on different subsets of data. We then used evaluation metrics like precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC-ROC) to assess the model's accuracy and reliability.
6) **Interpretability and Explainability**: Our group then focussed on interpreting the model-based results in a more explainable way, especially in the context of lending decisions. 
On comparison of the performance of these models, the group came to the conclusion that the Light Gradient Boosting Model performed best in terms of Accuracy(72%) and runtime(140.1 sec). This model gave the best result in identifying the probability of a Loan applicant being a defaulter or not based on several features that were identified as major factors in determining the repayment capability of an individual.

### My contribution to the project
Right from the inception of the project, I contributed across all the stages of this data science project including Data preprocessing, visualization, feature engineering, dataset balancing, model training, cross-validations, and conclusion. I also mentored my teammates on topics such as undersampling methodologies, stratification, hyperparameter tuning, and cross-validations. Enlisting a break-up of the topics I exclusively worked on and spent hours on:

1) **Analyzing Target Variable Distribution**
2) **Identifying and cleaning missing values across variables**
3) **Identifying and encoding categorical values using Label and One Hot Encoder**
4) **Finding correlations between various features and the Target**
5) **Handling a huge imbalance in the dataset** (target variable perspective)
6) **Aligning the train and test dataset**
7) **Training and Hyperparameter Tuning for models** such as Logistic Regression and Random Forest model.
8) **Running models individually on the Kaggle platform, analyzing the accuracy scores and runtime** which finally led our group to conclude on the Best Model for the Business Problem.

### Business Value of our solution
Our solution adds huge value to the business by:

1) **Providing an improved Loan Approval Process which does data-based customer credit assessment**
2) **Streamlining the Loan Approval Process by automating customer evaluations that speed up the decision-making, resulting in faster responses to loan applications, thus enhancing customer satisfaction and loyalty.**
3) **Reducing default rates**: By accurately assessing the loan applicants, the bank can reduce the number of loans granted to high-risk customers, ultimately leading to a decrease in default rates. Lower default rates translate to improved loan portfolio quality and reduced financial losses for the bank.
4) **Increase in profits**: Reducing default rates and identifying low-risk customers will allow the bank to offer better competitive rates to customers with good credit profiles. Attracting low-risk customers will lead to increased loan approval rates, thereby boosting the bank's revenue and profitability.

###  Difficulties that our group encountered
1) **Lack of Domain Expertise and absence of direct interaction with the business**: Understanding the domain-specific context of various independent variables in the dataset was a big challenge to us as we had no one from the business to reach out to get domain expertise. We had to mostly use Google and spend a lot of time establishing the relevance of such variables by using various analytical methods. This was also a blocker during our feature engineering steps.
2) **Data Preprocessing**: Having a team of people who are not seasoned with Python or analytical methods was another challenge that we had to face. For every kind of data inconsistency, we had to research, go through huge function/library documents and face multiple exceptions before achieving the right code snippet.
3) **Model Selection and Hyperparameter Tuning**: Another challenge that needs to be talked about was selecting the most appropriate machine learning algorithm and tuning its hyperparameters. Because we worked out our solution by training 3 models, we came across situations where different algorithms were performing differently on the same dataset, and finding the best combination of the hyperparameters was iterative and resource-intensive.
4) **Overfitting and Underfitting**: Balancing our model's complexity to avoid overfitting (fitting too closely to the training data) or underfitting (lack of ability to capture patterns) was crucial and achieving an optimal balance was really difficult. Also, because the given data set was significantly imbalanced, we had to come up with an intelligent strategy to balance the training dataset to avoid overfitting the majority target class. Digging down to this intelligent strategy was indeed one of the biggest challenges we faced.

### What I learned from this project
As a Business Analyst candidate, there was indeed a lot to learn from this project. Enlisting a few of the major ones below:

1) **Learn to collaborate with others, share ideas, and work collectively to achieve project goals.**
2) **Always have a problem-solving approach** that first breaks down the business problem at the best possible granularity level. Critically analyze how your dataset attributes are going to help you out in achieving the best possible solution
3) **Domain Knowledge and Expertise is the most underrated aspect** for candidates who are still learning Data Science. Getting deeper insights into the business context is very crucial for creating effective data-driven solutions.
4) **Learnt Project Management skills** by working on the capstone project end to end. From setting objectives to creating a plan to managing resources and working in strict timelines the business solution is a complete SDLC deliverable in itself.
5) **Data Understanding**: Understanding the data is a fundamental aspect of data science projects. Most of our time is spent in cleaning, preprocessing, and visualizing data to understand various inconsistencies.
