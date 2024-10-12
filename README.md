# YOLOv8-Object-Detection-on-COCO-2017-Dataset

## Overview
This project demonstrates how to use the YOLOv8 model for object detection on the COCO 2017 dataset. The COCO dataset consists of a variety of images annotated with objects from 80 different categories. YOLOv8, the latest version of the You Only Look Once (YOLO) object detection model, is known for its speed and accuracy in real-time object detection tasks.

## Project Workflow

* 1.**Install Dependencies:**
  * The project requires installing the ultralytics package, which provides easy access to YOLOv8, and other necessary libraries such as OpenCV, NumPy, and Matplotlib.
  _!pip install ultralytics_
* 2.**Model Setup:**
YOLOv8 is loaded using the pre-trained weights yolov8n.pt, which is the lightweight version of the YOLOv8 model.
* 3.**Dataset:**
The COCO 2017 dataset is used, specifically the train2017 and test2017 folders. Random images are selected from these directories for object detection tasks.
* 5.**Image Preprocessing:**
OpenCV is used to load and process the images, converting them from BGR (used by OpenCV) to RGB (used by Matplotlib for visualization).
* 6.**Visualization:**
Detected objects are plotted on the images, with bounding boxes drawn around them and labels indicating the detected class and confidence score.

## Directory Structure
```
/kaggle/input/coco-2017-dataset/  
├── coco2017/
    ├── train2017/     # Training images
    ├── test2017/      # Test images
```
    

## Dependencies
* Python 3.x
* OpenCV
* Matplotlib
* Numpy
* Ultralytics (YOLOv8)

## Results
The project successfully detects objects in random images from the COCO 2017 dataset using YOLOv8. Bounding boxes and labels for each detected object are displayed with confidence scores. Both training and test images were evaluated to showcase the model's detection capabilities.

## References
* [YOLOv8 Documentation](https://github.com/ultralytics/ultralytics)
* [COCO Dataset](https://www.kaggle.com/datasets/sabahesaraki/2017-2017)

