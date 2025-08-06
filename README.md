# yolov4-custom-functions - Face Detection & People Counting
Program for face prediction and counting how much people there are in an image using YOLOv4. Trained using dataset from Open Image Dataset V6 category Human Face and Person with 1600 pictures for each.

## Features
- Face Prediction from an image
- Counting how much people in an image

## Requirements
- Python 3.6.9
- opencv-python 4.1.1.26
- lxml
- tqdm
- tensorflow 2.3.0 (Non-GPU) atau tensorflow-gpu 2.3.0 (GPU)
- absl-py
- easydict
- matplotlib
- pillow

Notes: Recommended to install requirements using virtual environment in yolov4-custom-functions.
GPU:
``` pip3 install -r requirements.txt```
Non-GPU:
``` pip3 install -r requirements-gpu.txt```

## How to Use
``` python3 detect.py --weights ./checkpoints/custom-416 --size 416 --model yolov4 --images image_path --count ```

_Note: This was part of a 2021 internship project. Code may be slightly outdated_
