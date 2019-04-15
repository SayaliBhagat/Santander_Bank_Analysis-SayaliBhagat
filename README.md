# Santander_Bank_Analysis-SayaliBhagat

In this competition, there are 1.5 years of customers behavior data from Santander bank to predict what new products customers will purchase. The data starts at 2015-01-28 and has monthly records of products a customer has, such as "credit card", "savings account", etc. The goal is to predict what additional products a customer will get in the last month, 2016-06-28, in addition to what they already have at 2016-05-28. These products are the columns named: ind_(xyz)_ult1, which are the columns #25 - #48 in the training data.

Submissions in this competition are evaluated according to the Mean Average Precision @ 7 (MAP@7). It means that it is needed to predict no more than 7 products for every customer. Note that order matters. But it depends. Order matters only if there is at least one incorrect prediction. In other words, if all predictions are correct, it doesn't matter in which order they are given. This makes sense to show up first the most relevant results.

# Abstract
Data exploration and visualization. Trying to understand data, to find some trends in it.
Data preprocessing. Preparing train and test data to put them in models. Thinking about missing values.
Training and predicting. Trying to apply some models.
Some out-of-the-box solution (i.e. XGBoost). Set the result as a baseline score.
Trying to beat the baseline score using Collaborative Filtering in Spark.
In case of enough time, expirements with Neural Networks.
Comparing and Analysis of the Results.
Conclusions.
