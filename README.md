# yolov7

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
YOLO is a one-stage model for detection and classification. In this experiment, I will use YOLOv7 to detect car license plates.

## Training with yolov7
In this experiment, we aim to use YOLO to detect car license plates. A total of 477 images were used, with 259 images for the training set and 174 images for validation.

training set resource: 
[training set](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection)
[testing set](https://www.kaggle.com/datasets/fareselmenshawii/license-plate-dataset)

## Testing with yolov7

![00ceeec7002bace0](https://hackmd.io/_uploads/By7HLFHmJg.jpg)
![00d763761e47f723](https://hackmd.io/_uploads/Sygv8tHXkl.jpg)
![00e8e5e79255536f](https://hackmd.io/_uploads/ryAPIKHXJl.jpg)



## Problem Solving in the Training Process

#### 1. subprocess.CalledProcessError: Command 'git tag' returned non-zero exit status 128.
This issue pertains to incorrect weight paths. Below is the context for reference:
1. The weights path is missing or undefined.
2. There are capital letters in your path.

Image showing the problem:
![problem1](https://hackmd.io/_uploads/rk53zFrmJg.png)

Solving:
1. Providing the weights path
2. If you have already provided the path but the problem still occurs, try navigating to the directory first. Use cd to change to the folder containing the path, and then try again.

## Reference
1.[【圖文教學】YOLOV7 教學 手把手帶你做 訓練自己的物件偵測模型 訓練自己的資料集](https://medium.com/@huchi00057/yolov7-%E6%95%99%E5%AD%B8-%E6%89%8B%E6%8A%8A%E6%89%8B%E5%B8%B6%E4%BD%A0%E5%81%9A-%E7%94%A8gpu%E8%A8%93%E7%B7%B4%E8%87%AA%E5%B7%B1%E7%9A%84%E7%89%A9%E4%BB%B6%E5%81%B5%E6%B8%AC%E6%A8%A1%E5%9E%8B-%E8%A8%93%E7%B7%B4%E8%87%AA%E5%B7%B1%E7%9A%84%E8%B3%87%E6%96%99%E9%9B%86-pytorch-%E6%9E%B6%E6%A7%8B-coco%E6%A0%BC%E5%BC%8F%E8%B3%87%E6%96%99%E9%9B%86-d56370ab2035)
2.[How to Train own Dataset YOLOv7 in Google Colab](https://medium.com/@gary.tsai.advantest/yolov7-%E8%87%AA%E8%A8%82%E7%BE%A9%E8%A8%93%E7%B7%B4%E9%9B%86-4d9002e9d5bd)
