This project demonstrates image recognition using a Convolutional Neural Network (CNN) trained on the MNIST dataset of handwritten digits. It includes:

Model Training: Training a CNN using TensorFlow/Keras to classify handwritten digits.
Model Deployment: Deployment of the trained model using Flask, allowing users to upload images for real-time predictions.
Google Colab Integration: The project includes scripts adapted for Google Colab, enabling seamless training and testing of the model in a cloud-based environment.
Key Features:
CNN Architecture: Utilizes a simple CNN architecture with Conv2D, MaxPooling2D, and Dense layers.
Flask API: Provides a RESTful API endpoint for predicting digits from uploaded images.
Ngrok Integration: Temporarily exposes the Flask app via a public URL for testing and demonstration purposes.
Usage:
Train the model using the provided Google Colab notebook.
Deploy the model locally or temporarily using Flask and ngrok.
Send image files to the API endpoint (/predict) to receive predictions.
This project serves as an educational resource for understanding CNNs, model deployment with Flask, and integration with cloud-based platforms like Google Colab.
