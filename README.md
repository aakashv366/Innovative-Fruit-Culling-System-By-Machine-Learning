# Innovative-Fruit-Culling-System-By-Machine-Learning
- Developed an automated fruit culling system using deep learning and image processing to classify fruits,  detect defects, and ensure real-time quality control.  
- Implemented Convolutional Neural Networks to analyze fruit images in real time with accuracy of 95%. 
- Integrated Raspberry Pi, Logitech Camera, computer vision, and pattern recognition for real-time fruit sorting, reducing manual errors and improving productivity.

1) Core Purpose of the Project : FruitCulling is the process of sorting fruits based on quality, ripeness, or defects, removing the bad ones.
   Objective of Your Project : Automate fruit quality checking using Computer Vision + Machine Learning for faster and accurate sorting.
   Problem Statement : Manual fruit sorting is time-consuming, error-prone, and inconsistent. Our project solves this by using AI to automate the fruit sorting process.

2) Image Capture process : Fruits are placed on a conveyor, and images are captured using a camera (hardware part you worked on).
   Preprocessing : mages are cleaned (resized, color adjusted) using OpenCV.
   Model Training : A Convolutional Neural Network (CNN) was trained on fruit images to classify them as good or bad.
   Prediction & Sorting : The trained model checks new fruit images and classifies them. A signal (from the model) is sent to sort them accordingly (e.g., using a servo motor or actuator).

3) Technologies Used :
   Python – Main programming language.
   TensorFlow/Keras – For building and training CNN model.
   OpenCV – For image processing.
   Hardware – Logitech Camera, Raspberry Pi.
   CNN – For fruit classification (detect good/bad fruits).
   ML – Overall concept for model training and prediction.

5) My Contribution : I primarily handled the hardware setup – ensuring smooth image capture and system stability – and collaborated closely with the software team. Afterward, I studied how the ML model works, 
   especially CNNs for classification, and learned how OpenCV helps in preprocessing.


