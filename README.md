# AgriVision Crop Disease Detection

AI-powered crop disease detection system using Deep Learning and Computer Vision.


# Project Overview

This project identifies plant diseases from crop leaf images using Convolutional Neural Networks (CNN).

The system performs:
- image preprocessing
- disease classification
- CNN model training
- model evaluation


# Dataset

Dataset Used:
PlantVillage Dataset

- Total Classes: 38
- Total Images: 54,000+

# Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab


# Project Structure

```text
AgriVision-CropDiseaseDetection/
│
├── notebooks/
│   └── crop_disease_detection_complete.ipynb
│
├── README.md
└── models/


# Week 1 — Data Acquisition and Exploratory Data Analysis

## Tasks Completed

- Uploaded and extracted PlantVillage dataset
- Performed disease class exploration
- Visualized sample images from multiple disease categories
- Analyzed disease distribution
- Generated dataset statistics
- Examined image dimensions and quality
- Compared healthy and diseased leaf samples

## Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Outcome

Successfully explored and analyzed the PlantVillage dataset, gaining insights into disease categories, image characteristics, and class distributions before model development.

# Week 2 Completed

## Tasks Completed
- Applied Label Encoding and One-Hot Encoding
- Performed Train Validation Test Split
- Applied Data Augmentation
- Built Custom CNN Architecture
- Added Batch Normalization and Dropout Layers
- Implemented Early Stopping and Model Checkpointing
- Trained CNN Model
- Generated Accuracy and Loss Graphs
- Evaluated Model Performance
- Generated Classification Report
- Generated Confusion Matrix
- Saved Trained CNN Model

## Technologies Used
- TensorFlow
- Keras
- CNN
- Deep Learning
- Image Classification

## Output
Successfully trained and evaluated a CNN model for crop disease classification and prepared the model for deployment.

# Week 3 - Transfer Learning using MobileNetV2

## Objective
Improve crop disease classification performance using Transfer Learning with MobileNetV2.

## Tasks Completed

- Imported MobileNetV2 pre-trained model
- Applied Transfer Learning
- Added Global Average Pooling Layer
- Added Dense and Dropout Layers
- Trained the model on PlantVillage Dataset
- Evaluated model performance
- Generated predictions on test dataset
- Created Confusion Matrix
- Compared CNN and MobileNetV2 performance
- Saved trained model as crop_disease_mobilenetv2.h5

## Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Seaborn

## Dataset

PlantVillage Dataset

### Classes

- Tomato Diseases
- Potato Diseases
- Bell Pepper Diseases
- Healthy Plant Categories

Total Classes: 15

## Output

Successfully implemented Transfer Learning for crop disease classification and generated predictions on unseen images.

## Files Generated

- crop_disease_mobilenetv2.h5
- WEEK3.ipynb

## Learning Outcomes

- Understanding Transfer Learning
- Feature Extraction using MobileNetV2
- Fine-Tuning Deep Learning Models
- Performance Evaluation Techniques

# Week 4 - Streamlit Deployment

## Objective

Deploy the trained crop disease detection model as an interactive web application using Streamlit.

## Tasks Completed

- Developed Streamlit Web Application
- Integrated MobileNetV2 Trained Model
- Implemented Image Upload Functionality
- Performed Real-Time Disease Prediction
- Displayed Prediction Confidence Score
- Added Confidence Meter
- Added Farmer Recommendation Section
- Displayed Crop Health Status
- Deployed Application using Streamlit

## Features

### Image Upload
Users can upload crop leaf images.

### Disease Detection
The application predicts crop diseases using the trained deep learning model.

### Confidence Score
Displays prediction confidence percentage.

### Farmer Recommendation
Provides recommendations based on prediction results.

### Crop Health Status
Shows confidence-based crop health assessment.

## Technologies Used

- Streamlit
- TensorFlow
- Keras
- MobileNetV2
- Python

## Files Used

- app.py
- crop_disease_mobilenetv2.h5
- requirements.txt

## Output

Successfully deployed a web application capable of predicting crop diseases from leaf images.

## Future Enhancements

- Weather-based disease prediction
- Mobile Application Deployment
- Multi-language Support
- Fertilizer Recommendation System
- Real-time Farmer Advisory System

## Learning Outcomes

- Model Deployment
- Web Application Development
- User Interface Design
- AI Model Integration

# Author

Gana Shree C V


