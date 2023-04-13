# Object-Detection-Tracking-Yolo-DeepSort
## About The Project
One way to achieve precise object tracking is by combining YOLOv4, Deep SORT, and TensorFlow. This involves using the detections obtained from YOLOv4 and feeding them into Deep SORT, which uses a deep association metric to create a real-time and accurate object tracker. In this repo, we focus on one class and try to improve on top of it. Initially developed for tracking people in the MARS dataset, the original Deep SORT algorithm was designed with a feature extractor trained specifically for humans. However, since we need to track birds, we require an equivalent feature extractor tailored to them. To achieve this, we train a Siamese network.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* https://github.com/theAIGuysCode/yolov4-deepsort
* https://github.com/abhyantrika/nanonets_object_tracking
