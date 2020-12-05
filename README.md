# keras-yolo4

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

# Reference Model:

# [https://github.com/miemie2013/Keras-YOLOv4](https://github.com/miemie2013/Keras-YOLOv4)

## Introduction

A Keras implementation of YOLOv4 (Tensorflow backend) inspired by [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet).

Frame code from [https://github.com/qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3).

![](yolo4.png)

---

## Quick Start

1. Download YOLOv4 weights from [yolov4.weights](https://drive.google.com/open?id=1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT).
2. Convert the Darknet YOLOv4 model to a Keras model.
```
python convert.py
```
3. Run YOLOv4 detection.

```
python test.py
```
---

### Todo

Update to Keras 2.4 and TF 2