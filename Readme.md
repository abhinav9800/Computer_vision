Repositories Used

https://github.com/mikel-brostrom/boxmot.git

This repository contains the implementations of StrongSORT, BoT-SORT, ByteTracker, and DeepSORT, HybridSort , allowing for flexible and efficient tracking in various scenarios.

https://github.com/IDEA-Research/GroundingDINO.git



Project Overview

Auto-Annotation with GroundingDINO

GroundingDINO is utilized to automatically annotate images, streamlining the data preparation process by generating accurate bounding boxes and labels. This approach significantly reduces the manual effort involved in labeling large datasets.

Object Detection with YOLOv8

The YOLOv8 model is trained for object detection tasks, utilizing the auto-annotated images. YOLOv8 is selected for its state-of-the-art performance in terms of speed and accuracy, making it an ideal choice for real-time object detection applications.

Object Tracking 

This project incorporates advanced object tracking capabilities using BoTSORT and DeepSORT trackers. Each tracker has its own strengths and is utilized to address different tracking scenarios effectively:

BoTSORT

BoTSORT (Balanced Track-Sort) is applied to videos where objects remain within the frame for extended periods. Its key advantages include:

Robust Tracking: Effective for continuously tracking objects that do not frequently leave the frame.
High Accuracy: Combines appearance features and spatial information to maintain stable tracking.


DeepSORT

DeepSORT (Deep Simple Online and Realtime Tracking) is applied to videos where objects frequently enter and exit the frame. It excels in:

Handling Occlusions: Capable of re-identifying objects that reappear after disappearing.
Dynamic Tracking: Adapts to changes in object visibility and movement, ensuring consistent tracking despite frequent frame exits and reentries.
