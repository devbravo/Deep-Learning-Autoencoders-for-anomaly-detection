# Autoencoders for anomaly detection


## Objective:
Autoencoders are used to learn compressed representations of raw data with Encoder
and decoder as sub-parts. As a part of a series of Deep Learning projects, this project
briefs about Autoencoders and its architecture. In this project, we build a deep learning
model based on Autoencoders for Anomaly detection and deploy it using Flask. 

## Aim :
● To understand the theory behind Autoencoders
● To develop a deep learning model based on Autoencoders to learn distributions
and relationships between features of normal transactions
● To deploy the model using Flask

## Data Overview:
The dataset used is a transaction dataset, and it contains information for more than
100K transactions over several features.

## Tech Stack:
➔ Language: Python
➔ Packages: Pandas, Numpy, matplotlib, Keras, Tensorflow
➔ API service: Flask, Gunicorn

## Approach
1. Understand business objective
2. Understand the data using EDA
3. Normalize and clean the data using Imputation
4. Understand idea behind Auto-encoders
5. Build a base auto-encoder model using Keras
6. Tune the model to extract the best performance
7. Extract predictions
8. Serve model as API endpoint using Flask
9. Perform real-time predictions