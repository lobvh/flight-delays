# flight-delays

This is a binary classification toy-project where the challenge is to predict whether a plane is delayed 15 minutes or more. It's a part of a Kaggle challenge and the main idea is to improve ROC-AUC score. One can argue, but in my opinion ROC-AUC (shortly AUC) "isn't" a metric that is interpretable (read: useful) in some busniess context, apart for example comparing two or more models relative to a random classifier (AUC = 0.5). So, at the same time, I will try to beat the Kaggle baseline in ROC-AUC, but since the dataset is imbalanced I think it would be a valuable opportunity to treat this is as some ficticious 'buisness-problem' where the idea is to find as much delayed flights as possible since those have many impacts on business costs.

Dimensionality of the given dataset is not that big (feature-wise). Target variable is not balanced, and hence serves as a nice toy-example to show that sometimes accuracy might be a 'misleading' metric. Some strategies to 'combat' class-imbalance are proposed. 

The project will be structured in two parts:

//Part I 'Out-of-the-box' 

I am basically doing one of the cardinal sins of Data Science here, and that is: 'diving straight into modeling, without doing any EDA'. The main idea of this part is to give a general overview of what I am planning to do, show how I structure my work and code, and how I'm thinkering ML models. 

// Part II 'With EDA'

Here I will be focusing on using EDA in order to understand problem better, possibly find some features to help my model having more predictive power (feature engineering). 
