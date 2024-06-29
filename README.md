# Object-Recognition-in-Intelligent-Surveillance-Systems

## Overview

This project focuses on the comparative evaluation of different object recognition algorithms within the context of intelligent surveillance systems. Object recognition is a critical component of computer vision, enabling systems to identify and classify various objects within images accurately. This project examines several state-of-the-art algorithms, including RCNN, YOLOv3, YOLOv5, and YOLOv7, and provides an analysis of their performance.

Object reconition is a computer vision method of identifying the different classes or types of objects in an image and locating them using bounding boxes. This Repository contains programs of four Object Recognition Algorithms - RCNN (Region based Convolutional Neural Network), YOLO (You Only Look Once) - V3, V5 and V7 to run on COCO datasets.  

Explanation of the algorithms and comparative analysis is given in the paper: [Comparative Evaluation of Different Object Recognition Algorithms](https://drive.google.com/file/d/1OFUoL51_X4K_tcIJEsGSwNCqGvGfJasF/view?usp=share_link)

When you are training the model on custom dataset, you also need to upload dataset images and annotations file to colab storage. For YOLO v3, yolov3.cfg file needs to be updated according to the customization needed. In YOLO v5 and v7, .yaml files need to be updated, which contains names of the classes along with class ids and path to the train, test and validation datasets.   

To run the algorithms, copy the code on google colab notebook. Add the input image in the colab file and you are ready to detect the objects present in the input image. Do not forget to change the image name in the code according to the input image. 

## Table of Contents

- [Introduction](#introduction)
- [Algorithms Evaluated](#algorithms-evaluated)
  - [RCNN](#rcnn)
  - [YOLO](#yolo)
- [Implementation](#implementation)
- [Results and Discussion](#results-and-discussion)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

Object recognition involves identifying and classifying objects within images using computer vision techniques. It has numerous applications, including surveillance, autonomous driving, and medical imaging. This project evaluates various object recognition algorithms to determine their effectiveness and efficiency in real-world applications.

## Algorithms Evaluated

### RCNN

RCNN (Regions with Convolutional Neural Networks) is one of the early methods combining deep learning with region proposals. It uses selective search to generate region proposals and then classifies each proposal using a CNN.

### YOLO

YOLO (You Only Look Once) is a single-stage object detection algorithm that performs detection and classification in one step. It is designed for real-time applications and offers several versions with improvements over time, such as YOLOv3, YOLOv5, and YOLOv7.

## Implementation

The implementation section details the process of setting up and running the different algorithms. It includes steps such as setting up the environment, preparing the dataset, training the models, and evaluating their performance.

## Results and Discussion

This section presents the results of the comparative evaluation, including metrics such as accuracy, precision, recall, and processing time for each algorithm. It discusses the strengths and weaknesses of each approach and provides insights into their practical applications in surveillance systems.

## Conclusion

The conclusion summarizes the findings of the project, highlighting the most effective algorithms for object recognition in intelligent surveillance systems. It also suggests potential areas for future research and development.

## References

A list of references to the academic papers and resources used in the project.


## Usage

To run the code in this project, clone and run the python files after installing dependencies.


## Contributing

Contributions to the project are welcome. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

   
