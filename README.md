# Vietnam-Traffic-Sign-Detection
The project uses the YOLOv11 model to detect Vietnamese traffic signs.

Dataset: 
## Structure
- `src/Traffic_detection_by_yolov11.ipynb`: Up by Colab
- `src/Data_preprocessing`: Data loading and preprocessing
- `src/Model and train`: Model definition and Training script
- `src/Project metrics`: Metrics

# Vietnam Traffic Sign Detection

Vietnam Traffic Sign Detection uses YOLOv8 for detecting and classifying Vietnamese traffic signs.
This project applies Deep Learning and Computer Vision techniques to support intelligent transportation systems, autonomous vehicles, and safety monitoring applications.

### Model & Dataset

Base model: YOLOv11m (Ultralytics)

Input size: 224x224

Dataset: [Vietnam-Traffic-Sign](https://universe.roboflow.com/vietnam-traffic-sign-detection/vietnam-traffic-sign-detection-2i2j8)

Classes: 59 Vietnamese traffic signs
### Results
| Metric | Score |
|--------|--------|
| mAP@50 | 0.91 |
| mAP@50–95 | 0.81 |
| Precision | 0.95 |
| Recall | 0.91 |
