# ECE-4715_Final-Project
This is the final project submission for ECE 4715 - Machine Learning class. Done by Ye Yint and Htet Enedray Tun
## 🚀 Traffic Sign Detection System 🎯

  This repository contains implementation of a traffic sign recognition system using YOLOv5 and improved YOLO. The goal of this project is to accurately detect traffic signs and assign them to their appropriate classes. We will address the problem of challenges in small object detection especially when detecting traffic signs. The dataset that we used is called Traffic sign dataset from kaggle which extracted 4 classes out of 40 from German Traffic Sign Recognition Benchmark. 

This is the link to access the dataset: https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-dataset-in-yolo-format.

This is the link to GTSRB: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

To run this project, you will need to run the .ipynb on kaggle environment or modify it to run on other platforms. 
We have also provided the dataset and the dataset.yaml containing the 4 classes. 

This is where you can find the code to run the original YOLOv5 : [YOLOv5 Official Repo](https://github.com/ultralytics/yolov5)
This is the youtube video that was super helpful when figuring out how to run the code on google colab : https://www.youtube.com/watch?v=80Q3HIBy7Qg
The environment she uses is juypter notebook but you can easily modify it to run on colab. 


Below are some comparisons between the models 
| Metric                        | Value   |
|-------------------------------|---------|
| mAP@0.5  Yolov5               | 79%     |
| mAP@0.5:0.95 Yolov5           | 50.6%   |
| mAP@0.5   Improved Yolo       | 83.3%   |
| mAP@0.5:0.95   Improved Yolo  | 51.7%   |
