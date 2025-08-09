# yolo-screw-detection
This project implements a real-time object detection system using YOLOv8/YOLOv11 models to identify and classify screws based on head type (Allen, Hex, Flat) and size (Small, Medium, Large).

The workflow follows a complete Machine Learning pipeline, including:

Data Collection: Custom dataset of 400 images captured manually, ensuring diverse angles and lighting conditions.

Data Annotation: Labeling performed to fit YOLO format.

Model Training: Experiments with different YOLO architectures (YOLOv8m, YOLOv8l, YOLOv11m) and hyperparameters.

Data Augmentation: Applied to improve generalization and robustness.

Evaluation: Model performance assessed through precision, recall, and mAP@0.5:0.95 metrics.

Deployment: Real-time inference with a webcam.

This Proof of Concept (PoC) demonstrates how computer vision and deep learning can be applied to industrial tasks such as manufacturing, inspection, and automation, achieving high accuracy in a controlled environment.
