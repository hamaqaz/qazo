# Qazo
Qazo is a neural network aim assist that uses real-time object detection accelerated with CUDA on Nvidia GPUs.

## About

Qazo can be modified to work with a variety of FPS games; however, it is currently configured for Fortnite. Besides being general purpose, the main advantage of using Lunar is that it does not meddle with the memory of other processes.

The basis of Qazos's player detection is the [YOLOv5](https://github.com/ultralytics/yolov5) architecture written in PyTorch.

A demo video (outdated) can be found [here](https://www.youtube.com/watch?v=XDAcQNUuT84).

![thumbnail](https://cdn.discordapp.com/attachments/1158454617596768307/1164842083216003072/Screenshot_2023-10-20_112335.png)

## Installation

1. Install a version of [Python](https://www.python.org/downloads/) 3.8 or later.

2. Navigate to the root directory. Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the necessary dependencies.

```
pip install -r requirements.txt
```

## Usage
```           
python qazo.py
```
To update sensitivity settings:
```           
python qazo.py setup
```
To collect image data for annotating and training:
```           
python qazo.py collect_data
```
