﻿#### Object Detection using YOLOv3

#### Introduction
This Python script uses the YOLOv3 (You Only Look Once) deep learning model to perform real-time object detection on a video stream from a specified URL. The script detects and highlights objects in the video frame, such as cats, birds, and dogs, and prints "Hello" to the console if a cat is found.
------------

#### Dependencies
Make sure you have the following dependencies installed:

> OpenCV (cv2)
> NumPy (np)
>urllib

## You can install them using:
> pip install opencv-python numpy

## Usage
> 1-Replace the url variable with the URL of the video stream you want to analyze.

> 2-Ensure you have the YOLOv3 configuration file (yolov3.cfg), weights file (yolov3.weights), and the COCO class names file (coco.names) in the same directory as the script. You can find these files on the official YOLO website.

> 3-Run the script:
    python your_script_name.py


Code Explanation
### 1. Initialization
The script starts by importing necessary libraries and setting up the YOLO model with its configuration and weights.

### 2. Object Detection Function
The findObject function processes the YOLO model's outputs to identify objects and draw bounding boxes around them. It also sets a global variable found_cat to True if a cat is detected.

### 3. Main Loop
The script enters a continuous loop, capturing frames from the video stream, and applying the YOLO model for object detection.

### 4. Display
Detected objects are highlighted with bounding boxes, and the frame is displayed using OpenCV.

### 5. Console Output
If a cat is found (found_cat is True), the script prints "Hello" to the console.

### 6. Exit
Press 'q' to exit the video stream window and close the script.
Notes
Ensure you have a reliable internet connection to fetch the video stream.
Adjust the confidence threshold (confThreshold) and non-maximum suppression threshold (nmsThreshold) based on your requirements.
Feel free to modify and extend the script according to your specific use case!

#### 7. code espcam in file name  CameraWebServer.ino








