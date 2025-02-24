## Helmet Detection Using YOLO

### Project Overview
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

- cvzone: For drawing bounding boxes and adding text annotations.

- Ultralytics: To utilize the YOLO model.

### Project Workflow
- Load Pre-trained Model: Load the pre-trained YOLOv8 model for helmet detection.

- Resize Input Frames: Resize input images or video frames to the required size.

- Object Detection: Pass the frames through the YOLOv8 model to detect helmets.

- Visualization: Use cvzone to draw bounding boxes and add text annotations.

- Store Results: Save the resulting annotated images.

- Evaluation: Evaluate the detections using metrics like confidence scores.
