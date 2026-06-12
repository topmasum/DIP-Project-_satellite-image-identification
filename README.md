Satellite Image Identification using Deep Learning


Overview



This project is a Deep Learning-based Satellite Image Identification System developed as part of a Digital Image Processing (DIP) project. The system analyzes satellite images and automatically classifies them into predefined land-cover or geographical categories using a trained neural network model built with TensorFlow/Keras.


The project demonstrates the practical application of image processing, machine learning, and computer vision techniques for remote sensing and satellite imagery analysis.

Features

Satellite image classification using Deep Learning

Trained TensorFlow/Keras model

Automated image preprocessing and prediction

Class label mapping using JSON configuration

Support for multiple satellite image categories

Easy model deployment and integration into future applications



Technologies Used

Python

TensorFlow

Keras

NumPy

JSON

Digital Image Processing Techniques


Project Structure

├── satellite_classifier.keras

├── satellite_classifier (new).keras

├── class_names.json

├── class_names (new).json

├── Model code.txt

└── README.md


File Description

File	                                      Description

satellite_classifier.keras	               Trained classification model

satellite_classifier (new).keras	         Updated model version

class_names.json	                         Category labels for predictions

class_names (new).json	                   Updated class label mapping

Model code.txt	                           Model training and implementation code


How It Works


A satellite image is provided as input.

The image is preprocessed to match the model requirements.

The trained neural network extracts visual features from the image.

The model predicts the most probable category.

The predicted class is mapped using the JSON label file.

The final classification result is displayed.


Applications


Land-use classification

Environmental monitoring

Urban planning

Agricultural analysis

Remote sensing research

Geographic information systems (GIS)

Learning Outcomes


Through this project, the following concepts were explored:


Digital Image Processing

Image Classification

Convolutional Neural Networks (CNNs)

TensorFlow/Keras Model Development

Dataset Preparation and Preprocessing

Model Training and Evaluation

Remote Sensing Applications


Future Improvements

Develop a graphical user interface (GUI)

Add real-time image upload functionality

Improve classification accuracy with larger datasets

Deploy as a web application

Integrate with GIS platforms

Add visualization and prediction confidence scores
