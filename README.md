# Anukriti_Raj_Portfolio

Repository containing portfolio of data science projects completed for academic, self learning, and professional purposes. Presented in the form of Jupyter Notebooks.

## Project 1: MSBA Summer Capstone Project "Home Credit Default Risk".

### Table of Contents  
*[Project 1: MSBA Summer Capstone Project "Home Credit Default Risk"](#Project1)

   *[Business problem](#Businessproblem1)  
   *[Objective](#objective1)   
   *[Solution to the business problem](#solution1)   
   *[My contribution to the project](#contribution1)   
   *[Business Value of our solution](#businessvalue1)   
   *[Difficulties that our group encountered](#difficulties1)   
   *[What I learned from this project](#learning1)   

*[Project 2: MSBA Fall Capstone Project "Predicting Daily Forecast for Maverik's new store's first-year sales](#Project2)

   *[Business problem](#Businessproblem2)  
   *[Objective](#objective2)   
   *[Solution to the business problem](#solution2)   
   *[My contribution to the project](#contribution2)   
   *[Business Value of our solution](#businessvalue2)   
   *[Difficulties that our group encountered](#difficulties2)   
   *[What I learned from this project](#learning2) 
   
<a name="Project1"/></a>
## Project 1: MSBA Summer Capstone Project "Home Credit Default Risk"

<a name="Businessproblem1"/></a>
### Business problem
Prediction of the Client’s repayment abilities is a challenging task for HomeCredit bank as the company wants not to lose any potential clients who may be capable of on-time loan repayment. The company also wants to empower its clients who may not have sufficient or existent credit history by granting them loans after predicting their repayment abilities, by verifying their alternative data like telco and transactional information, both online and offline.

<a name="objective1"/></a>
### Objective
To build and develop a data-driven, credit risk assessment predictive model which evaluates the creditworthiness of customers applying for loans at the Home Credit bank.

<a name="solution1"/></a>
### Solution to the business problem
To provide a solution to the aforementioned business problem of lending to customers effectively, our team used the following approach:

1) **Data Visualization, Cleaning, and Preprocessing**: This included handling outliers, missing values, and inconsistencies along with analyzing the distribution of various independent variables in the dataset. 
2) **Feature Engineering**: This step included extraction and creation of meaningful features from the given dataset to provide valuable inputs to the lending model by transforming variables, creating new derived features, and scaling numerical data.
3) **Handling Imbalanced Data**: We also had to address the class imbalance issues, as the loan default cases were significantly lower than the non-default cases by employing intelligent undersampling
4) **Model Selection and Training with Hyperparameter Tuning**: Our team selected multiple models to identify the appropriate machine learning algorithm for credit risk assessment, such as logistic regression, random forests, and light gradient boosting model, and trained them accordingly.
5) **Cross-Validation and Evaluation**: We then employed cross-validation techniques to validate the performance of the aforementioned predictive models on different subsets of data. We then used evaluation metrics like precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC-ROC) to assess the model's accuracy and reliability.
6) **Interpretability and Explainability**: Our group then focussed on interpreting the model-based results in a more explainable way, especially in the context of lending decisions. 
On comparison of the performance of these models, the group came to the conclusion that the Light Gradient Boosting Model performed best in terms of Accuracy(72%) and runtime(140.1 sec). This model gave the best result in identifying the probability of a Loan applicant being a defaulter or not based on several features that were identified as major factors in determining the repayment capability of an individual.

<a name="contribution1"/></a>
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

<a name="businessvalue1"/></a>
### Business Value of our solution
Our solution adds huge value to the business by:

1) **Providing an improved Loan Approval Process which does data-based customer credit assessment**
2) **Streamlining the Loan Approval Process by automating customer evaluations that speed up the decision-making, resulting in faster responses to loan applications, thus enhancing customer satisfaction and loyalty.**
3) **Reducing default rates**: By accurately assessing the loan applicants, the bank can reduce the number of loans granted to high-risk customers, ultimately leading to a decrease in default rates. Lower default rates translate to improved loan portfolio quality and reduced financial losses for the bank.
4) **Increase in profits**: Reducing default rates and identifying low-risk customers will allow the bank to offer better competitive rates to customers with good credit profiles. Attracting low-risk customers will lead to increased loan approval rates, thereby boosting the bank's revenue and profitability.

<a name="difficulties1"/></a>
###  Difficulties that our group encountered
1) **Lack of Domain Expertise and absence of direct interaction with the business**: Understanding the domain-specific context of various independent variables in the dataset was a big challenge to us as we had no one from the business to reach out to get domain expertise. We had to mostly use Google and spend a lot of time establishing the relevance of such variables by using various analytical methods. This was also a blocker during our feature engineering steps.
2) **Data Preprocessing**: Having a team of people who are not seasoned with Python or analytical methods was another challenge that we had to face. For every kind of data inconsistency, we had to research, go through huge function/library documents and face multiple exceptions before achieving the right code snippet.
3) **Model Selection and Hyperparameter Tuning**: Another challenge that needs to be talked about was selecting the most appropriate machine learning algorithm and tuning its hyperparameters. Because we worked out our solution by training 3 models, we came across situations where different algorithms were performing differently on the same dataset, and finding the best combination of the hyperparameters was iterative and resource-intensive.
4) **Overfitting and Underfitting**: Balancing our model's complexity to avoid overfitting (fitting too closely to the training data) or underfitting (lack of ability to capture patterns) was crucial and achieving an optimal balance was really difficult. Also, because the given data set was significantly imbalanced, we had to come up with an intelligent strategy to balance the training dataset to avoid overfitting the majority target class. Digging down to this intelligent strategy was indeed one of the biggest challenges we faced.

<a name="learning1"/></a>
### What I learned from this project
As a Business Analyst candidate, there was indeed a lot to learn from this project. Enlisting a few of the major ones below:

1) **Learn to collaborate with others, share ideas, and work collectively to achieve project goals.**
2) **Always have a problem-solving approach** that first breaks down the business problem at the best possible granularity level. Critically analyze how your dataset attributes are going to help you out in achieving the best possible solution
3) **Domain Knowledge and Expertise is the most underrated aspect** for candidates who are still learning Data Science. Getting deeper insights into the business context is very crucial for creating effective data-driven solutions.
4) **Learnt Project Management skills** by working on the capstone project end to end. From setting objectives to creating a plan to managing resources and working in strict timelines the business solution is a complete SDLC deliverable in itself.
5) **Data Understanding**: Understanding the data is a fundamental aspect of data science projects. Most of our time is spent in cleaning, preprocessing, and visualizing data to understand various inconsistencies.

<a name="Project2"/></a>
## Project 2: MSBA Fall Capstone Project "Predicting Daily Forecast for Maverik's new store's first-year sales"

<a name="Businessproblem2"/></a>
### Business problem

Maverik faces the challenge of accurately forecasting the first-year sales of 30 new stores annually in different locations. Achieving precise predictions is crucial for developing a robust Return on Investment (ROI) document. Improved forecasting will empower the company to make informed decisions, optimize resource allocation, and enhance overall financial performance for sustained growth and success.

<a name="objective2"/></a>
### Objective
Create a data-driven, time-series predictive model to assess the initial-year sales of diesel, unleaded, food, and in-store items in new Maverik stores. Incorporate network-wide seasonality patterns and diverse sales metrics for accurate forecasting.

<a name="solution2"/></a>
### Solution to the business problem
To provide a solution to the aforementioned business problem of accurately predicting store sales, our team used the following approach:

1) **Data Visualization, Cleaning, and Preprocessing**: This involved addressing outliers, missing values, and inconsistencies, alongside studying the distribution of various independent variables in the dataset.
2) **Feature Engineering**:This step focused on extracting meaningful features from the dataset to provide valuable inputs for the forecasting model. It included transforming variables, creating new derived features, and binning numerical data.
3) **Model Selection and Training with Hyperparameter Tuning**: Our team selected multiple models to identify the appropriate machine learning algorithm for forecasting sales of various target variables, such as Prophet, SARIMA, and Extreme Gradient Boosting model, and trained them accordingly.
4) **Cross-Validation and Evaluation**: We then employed cross-validation techniques to validate the performance of the aforementioned predictive models on different subsets of data. We then used evaluation metrics like Mean Absolute Error, Mean Squared Error, and R-squared error to assess the model's accuracy and reliability.
5) **Interpretability and Explainability**: Our group then focussed on interpreting the model-based results in a more explainable way, especially in the context of forecasting new store sales for the first year. 
On comparison of the performance of these models, the group came to the conclusion that the Extreme Gradient Boosting Model performed better in forecasting compared to other models in terms of MEand Absolute and Squared error. This model gave the best result in forecasting the first-year sales of any New Maverik store.

<a name="contribution2"/></a>
### My contribution to the project
Right from the inception of the project, I contributed across all the stages of this data science project including Data preprocessing, visualization, feature engineering, model training, cross-validations, and conclusion. I also mentored my teammates on topics such as explaining the graphs created using various parameters during Exploratory Data Analysis Phase, hyperparameter tuning, and cross-validations. Enlisting a break-up of the topics I exclusively worked on and spent hours on:

1) **Analyzing Datasets provided to identify zero-variance variables**
2) **Identifying and cleaning missing values across variables**
3) **Identifying and encoding categorical values using Label and One Hot Encoder**
4) **Plotting various easy to understand graphs to obtain meaningful relationships between the dependent and independent variables**
5) **Finding correlations between various features and the Target**
6) **Training and Hyperparameter Tuning for models** 

<a name="businessvalue2"/></a>
### Business Value of our solution
Our solution adds huge value to the business by:

1) **Providing an accurate forecast of first-year sales for the new stores opened by Maverik**
2) **Inventory Optimization**: Sales forecasting will lead to supporting inventory optimization, reducing holding costs, and minimizing the risk of excess or obsolete inventory.
3) **Enhanced Planning and Resource Allocation**: Improved forecasting will aid in allocating resources more effectively, ensuring the right amount of manpower and materials are available when needed.
4) **Optimized Pricing Strategies**: The time series forecast model will enable business to implement dynamic pricing strategies, optimizing product pricing based on real-time market demand, and maximizing revenue.
5) **Financial Planning and Budgeting**: Improved forecasting will support better financial planning, allowing for more accurate budgeting and allocation of resources.

<a name="difficulties2"/></a>
###  Difficulties that our group encountered
1) **Exploring Models for Time Series Forecast**: Time Series Forecast model was a new domain of predictive model for us where we had to explore various models like ARIMA, SARIMA, Prophet and many others to come up with the best model that would suit Business Requirements.
2) **Data Preprocessing**: Having a team of people who are not seasoned with Python or analytical methods was another challenge that we had to face. For every kind of data inconsistency, we had to research, go through huge function/library documents and face multiple exceptions before achieving the right code snippet.
3) **Understanding and implementing terms like Seasonality, Trends, Lags and other terms**: Practical implementation of many forecasting model terms like Seasonality, Trend, Lags, etc. in the code were challenging and took time for us to interpret. 
4) **Model Selection and Hyperparameter Tuning**: Another challenge that needs to be talked about was selecting the most appropriate machine learning algorithm and tuning its hyperparameters. Because we worked out our solution by training 3 models, we came across situations where different algorithms were performing differently on the same dataset, and finding the best combination of the hyperparameters was iterative and resource-intensive.

<a name="learning2"/></a>
### What I learned from this project
As a Business Analyst candidate, there was indeed a lot to learn from this project. Enlisting a few of the major ones below:

1) **Learn to collaborate with others, share ideas, and work collectively to achieve project goals.**
2) **Always have a problem-solving approach** that first breaks down the business problem at the best possible granularity level. Critically analyze how your dataset attributes are going to help you out in achieving the best possible solution
3) **Domain Knowledge and Expertise is the most underrated aspect** for candidates who are still learning Data Science. Getting deeper insights into the business context is very crucial for creating effective data-driven solutions.
4) **Learnt Project Management skills** by working on the capstone project end to end. From setting objectives to creating a plan to managing resources and working in strict timelines the business solution is a complete SDLC deliverable in itself.
5) **Data Understanding**: Understanding the data is a fundamental aspect of data science projects. Most of our time is spent cleaning, preprocessing, and visualizing data to understand various inconsistencies.
6) **Learning new kind of predictive model(Time-series forecasting)**: The data analysis and model creation for the forecast model was completely new, challenging but interesting and it helped me understand the model that we can use for future predictions.

