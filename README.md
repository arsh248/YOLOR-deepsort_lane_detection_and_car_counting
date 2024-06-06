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


# 1) Select the area
![WhatsApp Image 2024-06-06 at 4 04 11 PM](https://github.com/arsh248/YOLOR-deepsort_lane_detection_and_car_counting/assets/62460837/eb931370-4582-4adb-95bc-16f10be0cc65)

# 2) Edge detection

![WhatsApp Image 2024-06-06 at 4 03 49 PM](https://github.com/arsh248/YOLOR-deepsort_lane_detection_and_car_counting/assets/62460837/8d8ee02e-b9f2-4a89-b91b-f13892738fe3)

![WhatsApp Image 2024-06-06 at 4 03 50 PM](https://github.com/arsh248/YOLOR-deepsort_lane_detection_and_car_counting/assets/62460837/d956fbe3-55cf-41ff-82ed-79df0a309733)

![WhatsApp Image 2024-06-06 at 4 03 49 PM-2](https://github.com/arsh248/YOLOR-deepsort_lane_detection_and_car_counting/assets/62460837/cb4de06b-e536-4729-9fc6-2c95cc0c3591)


# 3) Final output
![WhatsApp Image 2024-06-06 at 4 04 11 PM-2](https://github.com/arsh248/YOLOR-deepsort_lane_detection_and_car_counting/assets/62460837/4b408833-803b-4e5f-ae03-0b5129241c36)


