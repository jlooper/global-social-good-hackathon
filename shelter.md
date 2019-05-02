# Shelter animal classification

## Challenge

Every year, thousands of dogs and cats are surrendered to shelters or rescued by various organizations. These pets are then advertised on various websites where prospective adopters can discover available pets and contact the shelter. One challenge shelters face is being able to quickly identify the breed of a dog or cat. Machine learning and image recognition can assist in labeling images.

## Opportunities

A [large collection of labeled images](https://cs4b826aa5bbb08x4e9ax980.blob.core.windows.net/build/dogs-and-cats.zip) of cats and dogs have been provided. From there, there are a few paths your team could take.

- Use Azure Custom Vision Service to detect cats or dogs in a picture
- Build a custom machine learning model to detect breed
- Create a web application where users could upload a picture and receive a message indicating the type of animal or breed

## Resources

### Images and training data

A [zip file](https://cs4b826aa5bbb08x4e9ax980.blob.core.windows.net/build/dogs-and-cats.zip) has been created with a collection of pictures of dogs and cats. The CSV files provide information about the breeds, and the images directory contains several hundred images your team can use.

### Azure Custom Vision Service

- [What is Azure Custom Vision Service](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/home)
- [How to build a classifier with Custom Vision Service](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/getting-started-build-a-classifier)
- [Use your model with the Prediction API](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/use-prediction-api)

### Machine learning

- [Getting started with machine learning for computer vision](https://notebooks.azure.com/graememalcolmoutlook/projects/mlprimers)
- [Introduction to Azure Data Science Virtual Machine for Linux and Windows](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/overview)
- [Provision the Data Science Virtual Machine for Linux (Ubuntu)](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/dsvm-ubuntu-intro)

### Web development

#### Python/Flask

- [Deploying Python Web Applications to Azure](https://medium.com/@GeekTrainer/deploying-python-web-apps-to-azure-app-services-413cc16d4d68)
- [Uploading files to Flask](http://flask.pocoo.org/docs/1.0/patterns/fileuploads/)

#### Node.js

- [Create a Node.js web app in Azure](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-nodejs)
- [Using multer to upload files to Express](https://github.com/expressjs/multer#readme)
