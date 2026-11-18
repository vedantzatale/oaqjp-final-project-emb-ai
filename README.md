# Repository for final project

## Emotion Detector

An AI-based web application that detects the emotions in a piece of text using the Watson NLP library and serves the results through a Flask web interface.

- `EmotionDetection/emotion_detection.py` - calls the Watson NLP emotion model and returns the anger, disgust, fear, joy and sadness scores plus the dominant emotion
- `test_emotion_detection.py` - unit tests for the emotion detector
- `server.py` - Flask web server that deploys the application
