# Vehicle-Detection-Model

# Vehicle Detection Using YOLOv5

## Description
This project uses YOLOv5 for vehicle detection. It is trained on a custom dataset to identify vehicles in real-time.

## Installation
To run this project locally, follow these steps:
1. Clone this repository: 
   ```bash
   git clone https://github.com/muhammedtariq741/Vehicle-Detection-Model.git
pip install -r requirements.txt
python detect.py --source data/images/car.jpg --weights yolov5s.pt
Model Performance
Precision: 93.7%
Recall: 93.3%
mAP@0.5: 97.2%
