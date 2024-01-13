# Airline-passenger-referral-prediction

# Problem statement -

Data include airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions . Data is scraped is spring 2019 . The main objective is to predict whether passengers will refer the airline to their friends 

# PROJECT SUMMARY -

The project began with data loading , followed by EDA , feature engineering , data cleaning , target encoding , feature selection and model building .

Different models were used , including logistic regression , random forest , naive bayes , decision tree , support vector machine and k nearest neighbour .

Hyperparameter tuning was performed for decision tree , random forest , k- Nearest neighbors , support vector machines , and naive bayes models using the gridsearch cv method to improve accuracy and avoid overfitting

The Gradient Boosting model was fine-tuned by adjusting hyperparameters based on an understanding of the business and problem use cases .

The classification metrics for Recall were given first priority , followed by accuracy and ROC AUC .
Classifier models were created using six different types , all of which provided over 90% accuracy , with logistic Regression giving the best model .
Among the experiment models , SVM was found to be the most accurate with a very small margin .
The most important features were overall rating and value for money , which helped the model predict whether passengers would recommend a particular airline to their friends .
The developed classifier models can be used to predict passenger recommendation and identify influential passenger who can help generate more revenue for airlines .
To grow their business , airlines must provide outstanding cabin service , ground handling , entertaining food , beverages , and comfortable seating .
Data was collected from various sources , including customer reviews and airline websites , to obtain a comprehensive understanding of the airline industry .
Feature engineering was performed to extract relevant information from the raw data , including creating new features suct as the ratio of positive to negative reviews for each airline .
Data cleaning involved dealing the missing data , correcting data inconsistencies and removing irrelevant features .

Target encoding was used to transform categorical variables into numerical ones that can be used in the machine learning models .

Feature selection was done to identify the most important features that have the greatest impact on the target variable , which in this case was whether or not a passenger would recommend the airline .

Different evaluation metrics were used to assess the performance of the models , including precision , recall , accuracy and ROC AUC .
The models were trained and tested using a variety of techniques , such as cross - validation and train-test split ,to ensure their generalized to new data .
Interpretability of the models was also considered , with decision trees being particularly useful for understanding how the models make predictions .
The project concluded with recommendations for airline to focus on improving features that are most important to passengers , such as overall rating and value for money , to increase the likelihood of recommendations and ultimately grow their business .
