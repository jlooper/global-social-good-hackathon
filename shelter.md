# Shelter animal classification

## Overview

Every year, thousands of dogs and cats are surrendered to shelters or rescued by various organizations. These pets are then advertised on various websites where prospective adopters can discover available pets and contact the shelter. One challenge shelters face is being able to quickly identify the breed of a dog or cat. Machine learning and image recognition can assist in labeling images.

## Success criteria

Create a model which can successfully identify and label images of dogs. Create a web based front end for the model where users can upload images to discover the breed of dog.

### Possible additional challenges

Add support for cat breeds.

## Resources

### Images and training data

A [zip file](https://cs4b826aa5bbb08x4e9ax980.blob.core.windows.net/build/dogs-and-cats.zip) has been created with a collection of pictures of dogs and cats. The CSV files provide information about the breeds, and the images directory contains several hundred images your team can use.

### Azure Custom Vision Service

- [What is Azure Custom Vision Service](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/home)
- [How to build a classifier with Custom Vision Service](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/getting-started-build-a-classifier)
- [Use your model with the Prediction API](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/use-prediction-api)

### Web development

#### Python/Flask

- [Deploying Python Web Applications to Azure](https://medium.com/@GeekTrainer/deploying-python-web-apps-to-azure-app-services-413cc16d4d68)
- [Uploading files to Flask](http://flask.pocoo.org/docs/1.0/patterns/fileuploads/)

#### Node.js

- [Create a Node.js web app in Azure](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-nodejs)
- [Using multer to upload files to Express](https://github.com/expressjs/multer#readme)
