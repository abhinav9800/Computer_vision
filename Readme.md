Repositories Used
! git clone https://github.com/mikel-brostrom/boxmot.git

This repository contains the implementations of StrongSORT, BoT-SORT, ByteTracker, and DeepSORT, HybridSort , allowing for flexible and efficient tracking in various scenarios.

Project Overview


This project incorporates advanced object tracking capabilities using BoTSORT and DeepSORT trackers. Each tracker has its own strengths and is utilized to address different tracking scenarios effectively:

BoTSORT
BoTSORT (Balanced Track-Sort) is employed for tracking objects that remain within the frame for extended periods. Its key advantages include:
Robust Tracking: Particularly effective for continuous tracking of objects that do not frequently leave the frame.
High Accuracy: Utilizes appearance features and spatial information to maintain stable tracking.


DeepSORT
DeepSORT (Deep Simple Online and Realtime Tracking) is used for scenarios where objects frequently enter and exit the frame. It excels in:
Handling Occlusions: Capable of re-identifying objects that reappear after disappearing.
Dynamic Tracking: Adapts to changes in object visibility and movement, ensuring consistent tracking even with frequent frame exits and entries.
