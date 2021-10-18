# Demo of machine learning webapp deployment using Docker

 The dataset that we have in this case is from an online platform about the historical transactions of customers. It contains the data points such as age, total pages viewed, and whether the customer is a new or repeat customer. The output variable contains whether the customer bought the product online or not. So, we are going to train a simple logistic regression model to make the predictions on the test data and later export it for deployment purposes. This project primarily focuses on the buidling the Flask API app and deploying the machine learning webapp through docker image.

## We will execute this process by following these steps:	
- Train the ML model.
- Save and export the ML model.	
- Create a Flask app including the UI layer.	
- Build a custom Docker image for the app.	
- Run the app using a Docker container.	
- Stop the container

- ## To execute this set up, clone the repo in your system and build the image with the command ` docker build -t ml_app_docker .` , Make sure  all the files are in the same directory and command is executed from this directory.
- ## Once the docker image is build, run this command `docker container run -p 5000:5000 ml_app_docker` to run the image.
- ## Install docker desktop or any cloud platform which supports docker will be able to execute the above commands.
- ### Once the docker image is running, you can visit - http://localhost://5000/apidocs to view the application.


Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
