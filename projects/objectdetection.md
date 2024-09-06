---
layout: project
type: project
image: img/objectdetection.jpg
title: "Attacks on YOLOv3 Object Detection Model for Detecting Stop Signs"
date: 2022-11-23
published: true
labels:
  - YOLOv3
  - Object Detection
  - Adversarial Patch Attacks
  - Deep-Learning Neural Networks
summary: "My Electrical Engineering Master's Project"
---

<img class="img-fluid" width = "200px" src="../img/icloudpr/icloudPRlogo.png">

Object detection is a computer vision method to classify and locate objects in an image. Object detection methods can be divided into machine learning methods and deep learning methods. 
Object detection models are based on Deep-learning neural networks (DNNs) which are excellent for identifying the differences by using shapes and color, but DNNs are vulnerable to adversarial attacks such as
adversarial patch attacks (APAs) and small alterations on an image. It is important to improve the security of AI systems and to explore effective solutions against adversarial attacks. 
Understanding how attacks and defenses work on object detection models will help develop better object detection for future applications. To evaluate the vulnerability of YOLO v3 and YOLO v3-Tiny against adversarial patch attacks, we created diverse variations of stop signs with black,
red and white rectangular patches covering different parts of the sign and ran the images through the YOLOv3 and YOLOv3-Tiny model. As a result, it was found that covering up the letters with stripes was the best type of attack in our test cases. The models were able to detect the stop sign even with the letter completely
blocked.
