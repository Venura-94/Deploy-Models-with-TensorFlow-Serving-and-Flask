# Project Structure

The hands-on project on Deploy Models with TensorFlow Serving and Flask


## Getting Started with the Flask App
- Create a basic, functional web app with Flask.

## Index Template
- Add a template for the index page.
- Add a base template which extends a Bootstrap base template.

## TensorFlow Serving
- Create a docker instance with TensorFlow Serving image.
- Deploy and serve binary classifier model in the docker instance.
- Command - 

## Getting Predictions
- Write a module which sends a post request to the model server with input image tensor.
- Post-process the predictions obtained from the model server.

## Connecting the Model Server to the App
- Create functionality in our app to be able to upload image files.
- Import the inference module created previously in the app and get the predicted class for the uploaded image.

## Displaying the Results in the App
- Create a show.html template, where we will display the uploaded image along with its predicted class.




