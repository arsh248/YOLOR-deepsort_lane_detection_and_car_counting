## YOLOR Deepsort Lane Detection & Car Counting

This project combines YOLO object detection with lane detection to count cars and analyze traffic flow on roads. It uses the YOLO (You Only Look Once) algorithm for object detection and lane detection techniques to monitor vehicle movement within lanes.

# Features

- Object Detection: Utilizes YOLO algorithm to detect vehicles in the input video stream or image.
- Lane Detection: Identifies and marks lane boundaries to monitor vehicle movement within lanes.
- Car Counting: Tracks and counts the number of cars passing through predefined regions or lanes.
- Speed Estimation: Estimates the speed of vehicles based on their movement between frames.
- Visualization: Provides visual representation of detected objects, lane boundaries, and traffic flow.


# Requirements

- Python (>=3.6)
- PyTorch
- OpenCV
- NumPy
- Deep SORT (for object tracking)
- Other dependencies (refer to requirements.txt)

# Configuration

- --source: Path to the input video stream or image directory.
- --weights: Path to YOLO pre-trained weights file.
- --cfg: Path to YOLO configuration file.
- --lane_cfg: Path to lane detection configuration file.
- --view-img: Flag to display the output images with detections.

