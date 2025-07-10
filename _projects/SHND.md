---
layout: page
title: Deep SVHN
description: Street House Number Detection System
img: assets/img/Yolo_v3.JPG
importance: 8
category: work
related_publications: false
---

Repository: <a href="https://github.com/azwad-tamir/Deep_SVHN">GitHub</a>


<p><strong style="font-size: 18px;">Description: </strong></p>

In this project, we have developed a house number detection system based on the YOLO architecture that could detect and recognize house numbers from raw street view images. It is made up of a detection block that could put bounding boxes on street numbers and a classifier block specilizing on recognizing the digits.  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Yolo_v3.JPG" title="YOLO_Image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Object Detection using YOLOv3.
</div>

A numerical digit detection system has been build based on deep convolutional neural networks. The model is trained and tested on the SVHN dataset which consists of bulk multi-digit images of house numbers. The dataset contains two types of images. The type which consists of raw uncropped house number images has been chosen. The model consists of two parts; a detector and a classifier. The raw images are fed to the detector which creates bounding boxes around each of the separate digits of an image and crops the individual images of the digits. Next, the individual digit images are fed to the classifier, which classifies the images into 10 classes starting from '0' to '9'. The detector is based on resnet50 and Yolo-v2. 

It is built from scratch using the PyTorch machine learning framework. The individual accuracy of the detector and the classifier has been evaluated. The detector reports a training accuracy of 91% and a test accuracy of 59% while the classifier reports a training accuracy of 94% and a test accuracy of 92.11%. The overall training and testing accuracy of the entire system is found to be 86% and 54.41% respectively

