# Demo of machine learning deployment using Docker

- The dataset that we have in this case is from an online platform about the historical transactions of customers. It contains the data points such as age, total pages viewed, and whether the customer is a new or repeat customer. The output variable contains whether the customer bought the product online or not. So, we are going to train a simple logistic regression model to make the predictions on the test data and later export it for deployment purposes.

- We will execute this process by following these steps:	
- Train the ML model.
- Save and export the ML model.	
- Create a Flask app including the UI layer.	
- Build a custom Docker image for the app.	
- Run the app using a Docker container.	
- Stop the container
