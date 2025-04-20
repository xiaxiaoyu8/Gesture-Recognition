# Gestures-Recognition
基于openCV和官方模型文件实现的改良版手势识别

实现功能： 0-9的数字手势，OK👌的手势的识别，效果哇塞，可拓展性强

import numpy as np 
import cv2 as cv 
import math 

实现原理： 
使用openCV第三方库和模型文件： 
palm_detection_mediapipe_2023feb.onnx 
handpose_estimation_mediapipe_2022may.onnx 
检测五指的弯曲程度，以及相邻两指指尖的相对距离，从而准确判断此时做的是哪个手势

配置环境： 
Python-3.12.9 
openCV库版本：4.10.0.84
numpy库版本：2.24

Gesture recognition based on two onnx files of openCV and mediapipe

Functions: 0-9 digital gestures, OK👌 gesture recognition, the effect is wow, and the scalability is strong

import numpy as np import cv2 as cv import math How it works:

Using openCV third-party libraries and model files: 
palm_detection_mediapipe_2023feb.onnx 
handpose_estimation_mediapipe_2022may.onnx 

Detect the degree of curvature of the five fingers, as well as the relative distance between the fingertips of the two adjacent fingers, so that you can accurately determine which gesture to make at this time

Configure the environment: Python-3.12.9 openCV version: 4.10.0.84 Numpy version: 2.24
