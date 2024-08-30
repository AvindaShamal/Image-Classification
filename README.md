# Image-Classification
This project aims to classify images of five selected sports celebrities using machine learning techniques. 

## Table of Contents
- [Introduction](#introduction)
- [Business Requirements](#business-requirements)
- [Data Collection](#data-collection)
- [Data Cleaning and Feature Engineering](#data-cleaning-and-feature-engineering)
- [Model Building](#model-building)
- [Model Fine-Tuning](#model-fine-tuning)
- [Model Export and Flask Server](#model-export-and-flask-server)
- [User Interface](#user-interface)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Introduction
This project focuses on the end-to-end development of a machine learning model for sports celebrity image classification. The goal is to classify images of my five favorite sports celebrities. The model will be trained on a dataset of sports celebrity images and will utilize techniques such as SVM, Logistic Regression, and Random Forest for classification. Throughout this project, I will demonstrate how machine learning projects are executed in a corporate environment, covering all essential steps from data collection to model deployment.

## Business Requirements
The goal is to accurately classify images into one of the five sports celebrities using an efficient and scalable model.

## Data Collection
This section will involve collecting image data of the five chosen sports celebrities. You may also include details about the source of the data and the criteria for selecting images.

## Data Cleaning and Feature Engineering
Using OpenCV, the project will involve face and eyes detection for preprocessing the images. Feature engineering will include techniques like wavelet transforms to enhance model accuracy.

## Model Building
Three different models will be built: Support Vector Machine (SVM), Logistic Regression, and Random Forest. The goal is to compare their performance and choose the best model.

## Model Fine-Tuning
GridSearchCV will be used to fine-tune hyperparameters and improve model performance.

## Model Export and Flask Server
The best-performing model will be exported, and a Python Flask server will be developed to handle HTTP requests, allowing the model to be deployed for real-time predictions.

## User Interface
A user-friendly interface will be built using HTML, CSS, JavaScript, and JQuery, allowing users to upload an image and receive a prediction.

## Requirements
To run this project, you need the following libraries:
- OpenCV
- Scikit-learn
- Joblib
- Flask
- Pandas
- Numpy
- Wavelet

## Usage

- Clone the repository.
- Install all the necessary dependencies.
- Run the Jupyter Notebook to train the model.
- Start the Flask server.
- Access the UI and upload an image to classify it.
  
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
