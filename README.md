Real-time Face Detection with OpenCV
Overview

This Python project leverages the power of OpenCV to detect faces in real-time video streams. By employing the Haar Cascade classifier, a robust machine learning-based object detection algorithm, the project accurately identifies and localizes faces within each frame.

Haar Cascade Classifier: Download the haarcascade_frontalface_default.xml file from the OpenCV repository or other reliable sources. Place it in the same directory as your Python script.

The script will start capturing video from your default camera and display the video feed with bounding boxes around detected faces.
How it Works

Video Capture: The script initializes a video capture object to obtain frames from the camera.
Image Processing: Each frame is converted to grayscale for efficient processing.
Face Detection: The Haar Cascade classifier is applied to the grayscale image to detect faces.
Bounding Box: If faces are detected, bounding boxes are drawn around them.
Display: The processed frames with bounding boxes are displayed on the screen.
