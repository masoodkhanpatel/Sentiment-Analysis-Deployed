# Sentiment Analysis model on SageMaker Deployment 

In this project, we have constructed a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. We have created this model using Amazon's SageMaker service. In addition, we deployed our model and constructed a simple web app which will interact with the deployed model.

We used the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/) for training the RNN.

 ### Requirements and Services:

 - AWS SageMaker
 - AWS Lambda
 - AWS API Gateway


 <img src='Web App Diagram.svg' width=80%>

---

## Steps:
 - Create AWS SageMaker Notebook Instance
 - Preprocess the data in the notebook
 - Define RNN model
 - Train the model using a SageMaker instance
 - Create an endpoint to the model
 - Create a Lamdba function to pass data to the model for inference
 - Create an API Gateway that links to the Lambda function
 - You can now pass data through the API Gateway for inference and receive the response in your mobile app or web app
