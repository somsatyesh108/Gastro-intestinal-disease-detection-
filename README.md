# Gastro-intestinal-disease-detection-

This project is a Deep Learning-based web application that predicts Gastrointestinal (GI) cancer categories from medical images. It uses a DenseNet121 Convolutional Neural Network (CNN) model to classify images into:

MSS (Microsatellite Stable)

MSIMUT (Microsatellite Instable)

Key Features:
Pre-trained DenseNet Model Integration:
Uses DenseNet121 trained on gastrointestinal histopathological images for accurate predictions.

Streamlit Web Interface:
Simple and user-friendly interface allowing healthcare professionals or researchers to upload medical images and get instant predictions.

Real-time Inference:
Upload images in .jpg, .jpeg, or .png format and receive classification results directly.

Extensible Architecture:
The project includes both the DenseNet model and Inception model weights for further experimentation or extension.

Project Structure:
app.py – Streamlit web application

CNN_Keras.ipynb – Training and model development notebook

DenseNet_model.h5 – Pre-trained DenseNet model

Inseption_model.h5 – Pre-trained Inception model (optional for model comparison)

.gitattributes – LFS configuration for large files

README.md – Project documentation

How to Run:

1. Install dependencies:
pip install -r requirements.txt

2. Run the Streamlit app:
streamlit run app.py

3. Upload an image to get the cancer classification result.



