# Real-Time Face Detection with Flask and OpenCV

This project demonstrates real-time face detection using OpenCV and Flask.

## Requirements

- Python 3.x
- OpenCV
- Flask

## Installation
 1-Clone the repository:
 ```sh
git clone https://github.com/AlshaheerSoft2050/faces_detection_flask.git
cd face_detection_flask
 ```
 2-Install the required packages:
 ```sh
pip install opencv-python flask
```
Open your web browser and go to http://127.0.0.1:5000/ to see the real-time face detection in action.

How It Works
The app.py file contains the Flask application.
The generate_frames function captures frames from the webcam, processes them to detect faces, and streams the frames to the browser.
The index.html file is the frontend template that displays the video feed.
