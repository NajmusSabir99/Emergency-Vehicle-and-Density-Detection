Emergency Vehicle Detection & Density Dataset 🚨

This repository contains the dataset used in our project Emergency Vehicle Detection and Traffic Density Estimation via Webcam, where we trained a YOLO-based model on custom-collected data.

The dataset includes emergency vehicles such as ambulance, fire truck, along with normal vehicles, annotated for object detection and density analysis.


📊 Dataset Details

Total Images: 361 (fill in exact number)

Classes:
Ambulance
Fire Truck
Other Vehicles

Annotation Formats Provided:

YOLOv5 PyTorch → for direct retraining with YOLO.

COCO JSON → for general-purpose ML research.

🚀 Usage
YOLO Format

Train YOLOv5/YOLOv8 directly with:

yolo train data=dataset/yolo/data.yaml model=yolov8n.pt epochs=50 imgsz=640

COCO Format

Use the annotations.json and images/ with any COCO-compatible framework.
