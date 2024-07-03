# Amazon-Electronic-Products-Recommendation-System with ALS

Transform the data by splitting each record into fields.
* Visualize your data for your manager (important fields of your data, age group, most rated
items, item categories, age group etc. – according to you); create histogram, bar chart etc.
* Build recommendation engine using collaborative filtering.
* Use %70 of dataset for training, rest of them for testing.
* Use ALS (Alternating Least Squares) for training recommendation model with last 4 digit
of your student number as a “seed”. Also change the parameters of ALS re-run the
algorithm for parameters “rank” (5, 10, 15), “iteration” (5, 10, 15) and “lambda”

(0.01, 0.1). This means 18 different model will be created using specified rank-iteration-
lambda values

* Find and present MSE (Mean Squared Error), RMSE (Root Mean Squared Error) for
performance evaluation of each model and explain them, indicate best model for your
dataset, explain why.
* Return your code as “html” and “ipynb” file.
