# Real-Time Face and Emotion Detection

This project uses OpenCV and DeepFace to perform real-time face detection and emotion recognition through your webcam.
It detects faces in each frame using OpenCV’s Haar Cascade Classifier and then uses DeepFace to analyze the dominant emotion for each frame.

# Features

Real-time webcam feed processing

Face detection using Haar Cascade (haarcascade_frontalface_default.xml)

Emotion analysis using DeepFace (actions=['emotion'])

Live emotion overlay on detected faces

Press q to stop the camera safely.

# How It Works

Capture Video:
The webcam feed is accessed using cv2.VideoCapture(0).

Detect Faces:
Each frame is converted to grayscale and processed using OpenCV’s Haar Cascade model to locate faces.

Analyze Emotions:
DeepFace analyzes each frame to determine the dominant emotion (e.g., happy, sad, angry, etc.).

Display Results:
Rectangles are drawn around faces, and the detected emotion is displayed in real-time.
