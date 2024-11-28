# YOLOv7

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)

## Table of Contents

- [Introduction](#introduction)
- [Training](#Training)
- [Testing](#Testing)
- [Reference](#Reference)

## Introduction
YOLO (You Only Look Once) is a popular object detection algorithm that treats detection as a single regression problem, enabling fast and accurate object localization and classification in one pass. It works by dividing an image into a grid, with each grid cell predicting the bounding boxes and class labels for objects within it. YOLO's main advantages include high speed and strong accuracy. It is an end-to-end model, simplifying the training process, and excels at multi-object detection. In this experiment, we use YOLOv7 for implementation.

## Training
In this experiment, we aim to use YOLO to detect car license plates. A total of 477 images were used, with 259 images for the training set and 174 images for validation.

resource: <br>
[training set](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection)<br>
[testing set](https://www.kaggle.com/datasets/fareselmenshawii/license-plate-dataset)

## Testing
We have three contexts for testing. Below are the contexts for reference:<br>
1. Normal license plate<br>
2. Inclined license plate<br>
3. Incomplete license plate<br>
<br>
1. Normal license plate<br>
<img src="https://github.com/user-attachments/assets/4cc4a55e-19fd-4a89-83de-ab353bbdda5b" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/a061ebfb-506e-49c4-b4a7-46ae7afadd3e" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/43a94433-26a6-444b-8eec-c886d2d34f5c" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/61609bcf-9da1-4a30-96e8-89445f68b843" width = "24%" height = width>
<br>
2. Inclined license plate<br>
<img src="https://github.com/user-attachments/assets/2e2f7bdd-c3cc-45c2-87da-c11baa8a1be1" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/05c8a1ea-04d7-4325-a46a-64ded25c4ea2" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/1089920e-e3e6-4093-a9bd-0b54edb87ec8" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/904c6c47-ca06-4778-a773-1e57a6dab9f5" width = "24%" height = width>
<br>
3. Incomplete license plate<br>
<img src="https://github.com/user-attachments/assets/21a62ab0-089a-4b76-8321-5bd33b059bd6" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/2f21747b-dd83-428a-8170-a9b95433eafe" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/4f6d652d-9cbc-422d-a1d3-6bcba8421d2a" width = "24%" height = width>
<img src="https://github.com/user-attachments/assets/28c70be9-15ba-449b-b38d-798de5bfb777" width = "24%" height = width>
<br>

## Reference<br>

1.[【圖文教學】YOLOV7 教學 手把手帶你做 訓練自己的物件偵測模型 訓練自己的資料集](https://medium.com/@huchi00057/yolov7-%E6%95%99%E5%AD%B8-%E6%89%8B%E6%8A%8A%E6%89%8B%E5%B8%B6%E4%BD%A0%E5%81%9A-%E7%94%A8gpu%E8%A8%93%E7%B7%B4%E8%87%AA%E5%B7%B1%E7%9A%84%E7%89%A9%E4%BB%B6%E5%81%B5%E6%B8%AC%E6%A8%A1%E5%9E%8B-%E8%A8%93%E7%B7%B4%E8%87%AA%E5%B7%B1%E7%9A%84%E8%B3%87%E6%96%99%E9%9B%86-pytorch-%E6%9E%B6%E6%A7%8B-coco%E6%A0%BC%E5%BC%8F%E8%B3%87%E6%96%99%E9%9B%86-d56370ab2035)

2.[How to Train own Dataset YOLOv7 in Google Colab](https://medium.com/@gary.tsai.advantest/yolov7-%E8%87%AA%E8%A8%82%E7%BE%A9%E8%A8%93%E7%B7%B4%E9%9B%86-4d9002e9d5bd)
