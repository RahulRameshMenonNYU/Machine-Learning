# Machine-Learning
Code and Analysis of Interesting Machine Learning Projects 

# Credit Risk Classification 
Aim- Given instances of customers who default and not, train a machine learning algorithm that is able to predict who may deafult and who might not. The model should be robust (perform well across different metrics - accuracy, precision , recall, f1 scores)
- Train and build a benchmark model for classification task based on Logistic Regression
- Train and build other models based on Random Forest, gradient boost, ada boost and a voting classifier
- For the models that show promise (score well across multiple metrics) on train set cross validation, perform tuning using GridSearchCV
- The Final tuned model can be used to predict on test set. Also ask the benchmark model of Logistic Regression to predict on the test set
- Compare the performance of the tuned model with that of the benchmark model to see improvement in performance.


# Survial Analysis
Given churn data on customers, leverage survival analysis to model customer churn
 - Plot Survival Curves to predict the probability of churn over time
 - Compare survival curves of different customer segments (gender segments or billing segments..)
 - Determine if different segments of the customers (say male/female) churn differently 
 - Utilize log rank test to compare the survival of the customer segments comprehensibly 
   (The logrank test is most likely to detect a difference between groups when the risk of an event 
     is consistently greater for one group than another. )
 
 - Leverage Survival Regression model like semi para (Cox PH model) to model the relationship between churn time and other features
 - Determine the significant factors that drive churn 
 - The fitted model can be used to predict survival functions, ie. survival prob over time
 
 
