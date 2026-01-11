# emotion_detection
# Real-Time Emotion Detection (Webcam)

This project detects human emotions in real time using a webcam. It uses OpenCV to capture video frames and DeepFace to analyze facial emotions.

# Features

Real-time webcam emotion detection

Displays dominant emotion on screen

Works even when face detection fails (enforce_detection=False)

# Press Q to quit

# Requirements

Python 3.7+

Webcam

# Libraries Used

opencv-python

deepface

Installation

# Install the required libraries using pip:

pip install opencv-python deepface


DeepFace will automatically download required models on first run.

# How to Run

Save the code as emotion_detection.py and run:

python emotion_detection.py

# Usage

The webcam will open automatically

Face emotions will be detected in real time

The dominant emotion will appear on the video feed

Press Q to exit

How It Works

Captures frames from the webcam

Sends frames to DeepFace.analyze()

Extracts the dominant emotion

Displays emotion text on the screen

Possible Emotions

happy

sad

angry

surprise

fear

disgust

neutral

Limitations

Accuracy depends on lighting and camera quality

May be slow on low-end systems

Works best with a clear frontal face

# License

This project is intended for learning and educational purposes.
