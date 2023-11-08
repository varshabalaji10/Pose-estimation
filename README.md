
# Pose Estimation 
# Live and Multiple Pose Estimation

This project combines two major components for pose estimation: live pose estimation and multiple pose estimation. It utilizes the MediaPipe library and YOLO (You Only Look Once) object detection to detect and estimate human poses in images and videos. The live pose estimation provides real-time pose tracking from a webcam feed, while multiple pose estimation processes videos for multiple pose detection.

## Live Pose Estimation

Live pose estimation is used to detect and estimate the pose of a human in real-time. It leverages the MediaPipe library for pose estimation and draws landmarks on the detected pose. The project also provides an interface to interact with the live pose estimation process.

### Prerequisites

To run the live pose estimation code, make sure you have the following libraries installed:

- OpenCV (cv2)
- MediaPipe (mediapipe)

You can install the required libraries using pip, as shown in the code.

### Usage

1. Install the required libraries if you haven't already:

```bash
pip install opencv-python mediapipe
```
Run the provided Python code for live pose estimation. This code captures video from your webcam and performs pose estimation in real-time. You can interact with the live pose estimation process.

The code will display the live webcam feed with pose landmarks drawn on the detected human body. It will also provide a real-time frames-per-second (FPS) measurement.

Press the 'Esc' key (key code 27) to exit the live pose estimation.

# Multiple Pose Estimation
Multiple pose estimation is used to detect and estimate the pose of multiple humans in videos. It utilizes YOLO for object detection to identify human subjects in videos and then applies pose estimation to each detected subject.

### Prerequisites
To run the multiple pose estimation code, make sure you have the following libraries and YOLO files available:

OpenCV (cv2)
NumPy
YOLO weights file (yolov3.weights)
YOLO configuration file (yolov3.cfg)
COCO names file (coco.names)
You need to download the YOLO weights and configuration files as well as the COCO names file and provide their file paths in the code.

### Usage
Download the YOLO weights, configuration, and COCO names files if you haven't already. Provide the file paths in the code.

Run the provided Python code for multiple pose estimation. This code processes videos, detects human subjects using YOLO, and estimates the pose for each detected subject.

The code will display the video with bounding boxes around detected subjects and pose landmarks drawn on each subject's body.

The detected poses and landmarks are printed to the console for each frame.

Press the 'Esc' key (key code 27) to exit the multiple pose estimation.

### Customization
Make sure to customize the code for your specific use case, including adjusting the confidence thresholds for detection, file paths, and interaction with the live pose estimation component.

Please refer to the respective code sections and libraries for detailed documentation and customization options.

### Author
Varsha Balaji

Feel free to reach out for any questions or further assistance.
