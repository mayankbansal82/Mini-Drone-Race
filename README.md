# Mini Drone Race - Autonomous Navigation Project

## Overview
This project involves developing an  autonomous flight perception and controls system for a DJI Tello drone. The primary objective was to enable the drone to autonomously navigate through sequentially placed gates, showcasing its potential in precision flying, which can be crucial in various applications including sports, surveillance, and research.

## Key Features
- **Autonomous Gate Navigation:** The system allows a DJI Tello drone to autonomously navigate through a series of gates, showcasing advanced flight precision.
- **Custom Blender Dataset & YOLOv8 Integration:** Utilized a custom dataset created with Blender and Gaussian Splatting, combined with the YOLOv8 model for accurate gate segmentation and corner detection.
- **Pose Estimation with PnP Algorithm:** Implemented the Perspective-n-Point (PnP) algorithm to accurately deduce the drone's pose, ensuring smooth and precise passage through each gate.

## Technologies Used
- **Drone Technology:** DJI Tello Drone
- **Dataset Creation and Image Processing:** Blender, Gaussian Splatting
- **Gate Detection and Pose Estimation:** YOLOv8, Perspective-n-Point (PnP) Algorithm
- **Programming Languages and Frameworks:** Python, PyTorch

![Gate Navigation](https://github.com/mayankbansal82/Mini-Drone-Race/blob/main/Images/GaussianSplat.jpeg)
*Gaussian Splat of environment*

![Gate Navigation](https://github.com/mayankbansal82/Mini-Drone-Race/blob/main/Images/Background.png)

*Dataset generated with random background*

![YOLOv8 Segmentation](https://github.com/mayankbansal82/Mini-Drone-Race/blob/main/Images/im.jpeg)
*Test environment*

![YOLOv8 Segmentation](https://github.com/mayankbansal82/Mini-Drone-Race/blob/main/Images/yolo.jpg)
*Gate Segmentation using YOLOv8*

![Pose Estimation](https://github.com/mayankbansal82/Mini-Drone-Race/blob/main/Images/Corners.png)
*Corners for each gate*

## Results

The video for drone passing through the gates can be found ![here](https://youtu.be/8t1Wc6d-NgQ)


