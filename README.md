# Superstore_Project
This project is aimed at predicting sales using machine learning algorithms. We will be exploring two models, Linear Regression and Random Forest Regression, to determine which model performs better in predicting sales accurately. We will also perform hyperparameter tuning on the Random Forest Regression model to further improve its accuracy.
Data

The dataset used for this project is the Sales Dataset, which contains information on sales transactions for a retail company. The dataset includes information such as the customer segment, product category, region, quantity, discount, and profit.

Preprocessing

Before building our models, we performed several preprocessing steps on the dataset, including handling missing values, encoding categorical variables, scaling the numerical features, and splitting the dataset into training and testing sets.

Modelling

We explored two machine learning models, Linear Regression and Random Forest Regression, to predict sales. We evaluated the models using mean squared error (MSE) and R-squared (R2) score. We found that the Random Forest Regression model performed better than the Linear Regression model, with an MSE of 0.19 million compared to 0.50 million for the Linear Regression model. We also performed hyperparameter tuning on the Random Forest Regression model to further improve its accuracy.

Results

Our best performing model was the Random Forest Regression model after hyperparameter tuning, which had an MSE of 0.17 million and an R2 score of 0.77 on the test set.

Deployment

To deploy the model, we can use a cloud-based platform such as AWS or Azure. We can also create a web application using Flask or Django and host it on a cloud platform.

Conclusion

In this project, we explored two machine learning models to predict sales and found that the Random Forest Regression model performed better than the Linear Regression model. We also performed hyperparameter tuning to further improve the accuracy of the Random Forest Regression model. This model can be deployed using cloud-based platforms or a web application to predict sales for the retail company.
