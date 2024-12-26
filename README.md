# AI-project in Linear Regression 
My first experience with machine learning involved developing a linear regression model using Python in PyCharm. The dataset I used was sourced online. The primary reason I chose to start with linear regression was to familiarize myself with fundamental concepts of machine learning, gain a deeper understanding of the model development process, and practically apply the knowledge I had acquired from the courses I was attending.

# Building the model
In my first machine learning project, I worked with a dataset related to the solubility of chemical compounds. The goal was to create a model that could predict the solubility of these compounds. Initially, I imported the dataset and defined my data frame. After that, I split the data into training and testing sets using an 80-20 ratio, with 80% for training and 20% for testing, in order to ensure proper evaluation of the model's performance. 



Next, I trained the model and applied it to the test set to evaluate its performance. To assess this, I calculated the Mean Squared Error (MSE) and R-squared values for both the training and test sets, in order to determine how well the model was performing. As expected, the model was performing well.

However, I decided to apply another ML Model, Random Forest, to compare which one would be more suitable for my data. After comparing, I realized that the linear regression model was the better choice.

Finally, I visualized the relationship between the experimental LogS values (y_train) and the predicted values from the linear regression model (y_lr_train_pred) to better understand the model's performance.

