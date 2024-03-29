# Red-wine-quality
## Comparison of the logistic regression, decision tree, and random forest models to predict red wine quality in R
In the following project, I applied different machine learning algorithms to predict the quality of a wine. The dataset I used for the project is called Wine Quality Data Set.

The dataset contains 1,599 observations and 12 attributes. Each row describes the physicochemical properties of one bottle of wine. The first 11 independent variables display numeric information about these characteristics, and the last dependent variable reveals the quality of the wine on a scale from 0 (bad quality wine) to 10 (good quality wine) based on sensory data.
Since the outcome variable is ordinal, I chose logistic regression,KNN,Support Vector Machine,Stochastic Gradient Descent,decision trees,Gaussian Naive Bayes Classifier,random forest classifier,Voting Classifier,ADA Boost Classifier,Gradient Boosting Classifier,Stochastic Gradient Boosting and XG Boost to answer the following questions:
1. Which machine learning algorithm will enable the most accurate prediction of wine quality from its physicochemical properties?
2. What physicochemical properties of red wine have the highest impact on its quality?

## Methodology

For this project, I followed the following steps.
### 1. Import the dataset:
In this step, I import the dataset and formated the outcome variable.
### 2. Performed an exploratory data analysis (EDA):
First, I developed a descriptive statistic analysis to examine the independent variables by studying the boxplots and histogram plots etc. of each variable.
### 3. Data preparation:
For this part of the project, I focused on finding the missing values and outliers in the data. In other words, this step was to prepare the data for the prediction models.
### 4. Modeling:
The next step of the project was to develop regression models that will be able to predict the dependent variable. First, I proceed to split the data into train and test set. Further, I train different models.
### 5. Variable importance:
Finally, the last step was to gather the essential variables from the model that reveal the highest accuracy.
