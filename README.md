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

<img width="634" height="499" alt="Screenshot 2025-11-01 114019" src="https://github.com/user-attachments/assets/5dd7cda5-5195-48d4-a1e5-62c2f87b8c75" />


<img width="638" height="510" alt="Screenshot 2025-11-01 114009" src="https://github.com/user-attachments/assets/3a904c0d-7ff3-4319-a032-f1966bd7d00e" />

<img width="638" height="507" alt="Screenshot 2025-11-01 114001" src="https://github.com/user-attachments/assets/f7abd7d4-c575-479e-b7f1-946cf5ba8031" />
