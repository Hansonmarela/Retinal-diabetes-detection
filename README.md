# INNOVATIVE DIABETES PREDICTION USING RETINA FUNDUS IMAGES

# Project Overview
This project's goal is to create an automated platform for detecting diabetic retinopathy using deep learning algorithms. Users may upload retinal scans to the portal, which will evaluate them and deliver immediate diagnosis. The system uses Convolutional Neural Networks (CNNs) to categorize pictures into different severity levels of diabetic retinopathy, which improves accuracy and reliability over older techniques.

# System Requirements
Software Environment
Python Libraries and Frameworks
TensorFlow, Keras, Flask, NumPy

Development Tools
Jupyter Notebook
Integrated Development Environment (IDE) such as PyCharm or VS Code

# Algorithms
Image Preprocessing: Converts images to a standard size and format, normalizes pixel values.
Convolutional Neural Network: Extracts features from images and classifies them into different categories of diabetic retinopathy.
Prediction and Diagnosis: Uses the trained model to predict the presence and severity of diabetic retinopathy from new images.

# Experimental Workflow
The experimental design consists of training the CNN model on a collection of retinal pictures, verifying its performance, and fine-tuning hyperparameters to increase accuracy. The model is then deployed using Flask to deliver real-time predictions for newly submitted photographs by users.

# Results and Discussion
The model accurately classified the severity levels of diabetic retinopathy. Over 93%. The system delivered fast and accurate diagnoses, making it an invaluable tool for early diagnosis and treatment planning. The use of visualizations helped users understand the diagnosis process better.

# Conclusion
The proposed technique successfully automates the identification of diabetic retinopathy with deep learning, providing a user-friendly, accurate, and dependable method for early detection. This method has the potential to dramatically increase the accessibility and efficacy of diabetic retinopathy screening, especially in resource-constrained areas.

# Usage
To use this project:
1. Clone the repository.
2. Install the required libraries using pip install -r requirements.txt.
3. Run the Flask application with python app.py.
4. Access the web interface at http://localhost:5000.
5. Upload a retinal image and receive an instant diagnosis.
