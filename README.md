# object_count-using-pyton
This project is a Python-based real-time object detection system that uses the YOLOv8 model to count all detected objects and specifically track the number of people visible through your webcam. It's an efficient and simple application built using OpenCV and Ultralytics YOLOv8
# 🛠 Requirements
-Python 3.8+

-Ultralytics YOLO

-OpenCV

-NumPy
# Features
-Real-time object detection via webcam

-Counts total number of detected objects per frame

-Separately tracks the number of detected persons

-Displays labeled bounding boxes and live count overlays

-Built using YOLOv8 from Ultralytics
# Install dependencies:

-bash
-Copy code
-pip install ultralytics opencv-python
# ▶ How to Run
1.Clone this repository.

2.Make sure your webcam is connected.

3.Run the script:

-bash
-Copy code
-python object_count.py
4.Press q to quit the live feed.
