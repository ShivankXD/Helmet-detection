## Helmet-detection using YOLO 

**Project Overview**
This project aims to detect helmets in images and videos using the YOLO (You Only Look Once) object detection algorithm. The primary objective is to enhance safety by ensuring that individuals are wearing helmets in various environments, such as construction sites or while riding motorcycles.


### Features
- Real-time Detection: Utilizes the YOLO model to detect helmets in real-time from video feeds or images.

- High Accuracy: Trained on a diverse dataset to achieve high accuracy in detecting helmets.

- Scalability: Can be extended to detect other safety equipment like gloves or safety glasses.

- Visualization: Provides annotated images and videos with detected helmets highlighted.


### Tools and Technologies
- Python: The primary programming language used for the project.

- OpenCV: For image and video processing.

- YOLOv8: The object detection model used for helmet detection.

- Supervision: For visualizing object detection and annotations.

- Ultralytics: To utilize the YOLO model.


### Project Workflow
1. Load Pre-trained Model: Load the pre-trained YOLOv8 model for helmet detection.

2. Resize Input Frames: Resize input images or video frames to the required size.

3. Object Detection: Pass the frames through the YOLOv8 model to detect helmets.

4. Visualization: Use the Supervision package to visualize the detections on the images.

5. Store Results: Save the resulting annotated images and generate a CSV file containing detection information.

6. Evaluation: Evaluate the detections using a confusion matrix and calculate accuracy and loss metrics.


