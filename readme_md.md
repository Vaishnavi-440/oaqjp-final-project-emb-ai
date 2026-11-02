# Emotion Detection Application

This repository contains an AI-based Emotion Detection web application developed using Python, Flask, and IBM Watson NLP libraries.

## Project Structure
- `EmotionDetection/`: Package containing the core emotion detection logic.
  - `__init__.py`: Package initialization file.
  - `emotion_detection.py`: Interacts with IBM Watson NLP API and formats output.
- `server.py`: Flask application server providing the web interface and API endpoints.
- `test_emotion_detection.py`: Unit tests for verifying the emotion detection functionality.

## Setup & Running
1. Install dependencies:
   ```bash
   pip install flask requests
   ```
2. Run the server:
   ```bash
   python3 server.py
   ```
3. Access the web interface at `http://localhost:5000`.