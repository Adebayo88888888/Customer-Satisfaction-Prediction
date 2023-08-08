# Predicting-Customer-Satisfaction

Business Understanding
For this activity, we are working as a consultant for an airline. The airline is interested in knowing if a better in-flight entertainment experience leads to higher customer satisfaction. They would like you to construct and evaluate a model that predicts whether a future customer would be satisfied with their services given previous customer feedback about their flight experience.


Data Understanding
The dataset "Invistico Airline.csv" contains information for 129,000 customers who have traveled via the airline agency. It includes 22 columns, with the outcome variable being "satisfaction" (binary - satisfied or not satisfied). Other features include the class of flight, age, flight distance, arrival and departure time.


Modeling and Evaluation
The process began with EDA and data cleaning, and then building a logistic regression model because the outcome is binary (satisfied or not satisfied), we also built some machine learning algorithms including decision tree, random forest, and XGBOOST and tuned the hyper parameters to get the best score possible, we got the champion model to be the tuned random forest with Accuracy of 94%, Precision of 95%, Recall of 94%, and F1 score of 94%.


Conclusion
The predictive model provides valuable insights to the airline agency. Customer satisfaction is highly influenced by 'Inflight entertainment', 'Seat comfort', and 'Ease of Online booking', as indicated by the feature importance plot. Improving these experiences is likely to enhance overall customer satisfaction, leading to a positive impact on the airline's business performance.
