Crowd Count and Density Estimation
This project implements a real-time crowd counting system using the YOLOv8 object detection model from the Ultralytics library. It detects and counts the number of people in a live webcam feed, displaying the count directly on the video stream.

Features
Real-time people detection using webcam input

Counts and displays the number of people detected per frame

Utilizes Ultralytics YOLOv8 for high-accuracy object detection

Requirements
Python 3.8 or higher

OpenCV

Ultralytics (YOLO)

A pretrained YOLOv8 model file (YOLO_model.pt)

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/yolo-crowd-counter.git
cd yolo-crowd-counter
Install the required packages:

bash
Copy
Edit
pip install opencv-python ultralytics
Add your YOLOv8 model file (YOLO_model.pt) to the project directory.

Usage
To run the crowd counting system:

bash
Copy
Edit
python main.py
A window will open showing the live webcam feed with bounding boxes around detected people.

The total count of people will be displayed in the top-left corner of the video.

Press q to exit the program.
