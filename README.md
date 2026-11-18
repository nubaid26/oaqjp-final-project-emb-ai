# Emotion Detector - AI-Based NLP Web Application

This repository contains the final project for **Emotion Detector**, an AI-based web application developed using Python, Flask, and the IBM Watson NLP Emotion Predict library.

## Features
- **Watson NLP Emotion Detection**: Analyzes input text and returns scores for `anger`, `disgust`, `fear`, `joy`, and `sadness`, along with the `dominant_emotion`.
- **Packaged Python Module (`EmotionDetection`)**: Modular package structure with `__init__.py` and `emotion_detection.py`.
- **Unit Testing**: Automated test suite (`test_emotion_detection.py`) covering all five emotion categories.
- **Flask Web Deployment**: Interactive web interface (`server.py`, `templates/index.html`, `static/mywebscript.js`) served on `http://localhost:5000`.
- **Error Handling**: Handles HTTP `400` status codes and blank inputs gracefully with `"Invalid text! Please try again!"`.
- **Static Code Analysis**: Verified with `pylint` achieving a `10.00/10` code quality score.
