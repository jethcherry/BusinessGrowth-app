This repository contains a Flask API implementation for serving predictions using a pickled Random Forest Classifier model. Users can make HTTP POST requests to the /predict endpoint with input data in JSON format, and the API returns predicted class labels.

To test the Flask API using Postman, start the Flask server, open Postman, create a new request with the appropriate POST method and endpoint URL (http://localhost:5000/predict), set the request body to raw JSON format, enter your input data, and send the request
