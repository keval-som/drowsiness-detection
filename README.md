# Drowsiness Detection System
## Introduction
This Python project is a real-time drowsiness detection system that uses computer vision techniques to monitor a person's eyes and mouth. It alerts the user when signs of drowsiness are detected.

## Features
Real-time drowsiness detection using a webcam.\
Detection of yawning and heavy eyelid closure.\
Auditory and visual alerts to notify the user.\
Customizable detection thresholds.\
Simple and intuitive usage.

## Prerequisites
Before running the drowsiness detection system, make sure you have the following dependencies installed:\
Python (>= 3.6)\
OpenCV\
dlib\
numpy\
pygame (for auditory alerts)

You can install these packages using pip: \
$ pip install opencv-python dlib numpy pygame

## Configuration
You can configure the drowsiness detection system by modifying the parameters in the drowsiness_detection.py script. Here are some of the key parameters you can customize:

frame_check: The number of consecutive frames required to trigger a drowsiness alert.\
Thresholds (EAR and MOR values): Adjust these thresholds to fine-tune the detection sensitivity.\
Alert sound: Replace the "alarm.mp3" sound file with your preferred alert sound.

## Alerts
Yawning Detection: The system will detect yawning and display an alert message.\
Eye Closure Detection: The system will detect heavy eyelid closure and trigger an alarm sound and message.\
Alert Score: A score is displayed, indicating the level of drowsiness detected.
