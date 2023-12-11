# Facial-emotion-detection
This project utilizes computer vision and deep learning techniques to perform facial emotion analysis in real-time using a webcam. The model recognizes seven different emotions: angry, disgust, fear, happy, sad, surprise, and neutral.

Overview
The code included in this repository consists of Python scripts that perform the following tasks:

Model Loading: Loads a pre-trained deep learning model (best_model.h5) for facial emotion recognition.
Real-time Analysis: Utilizes OpenCV to access the webcam, detect faces, and predict emotions in real-time.
User Interaction: Displays the live video feed with emotion predictions overlaid on detected faces.
Requirements
Python 3.x
OpenCV
Keras with TensorFlow backend
Usage
Ensure all required libraries are installed by running pip install -r requirements.txt.
Run facial_emotion_analysis.py to start the emotion detection process.
Press 'q' to quit the application.
Folder Structure
best_model.h5: Pre-trained deep learning model for facial emotion recognition.
facial_emotion_analysis.py: Main Python script for real-time emotion analysis.
README.md: Information about the project and usage instructions.
Other files: Supporting files and resources.
Contribution
Feel free to contribute by forking this repository, making enhancements, and creating pull requests. All contributions are welcome!
