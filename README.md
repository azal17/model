# RCNN Model for Airplane Dataset

This project implements a Region-based Convolutional Neural Network (RCNN) for detecting and classifying airplanes in images. The model is built using the TensorFlow library and optimized with the Adam optimizer.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)


## Introduction

Region-based Convolutional Neural Networks (RCNN) are a class of deep learning models used for object detection and classification. This project focuses on identifying airplanes from a given dataset. The model is trained using the TensorFlow library and utilizes the Adam optimizer for efficient training.

## Dataset

The dataset used for this project contains labeled images of airplanes. It includes various airplane types and different viewing angles. Each image is annotated with bounding boxes indicating the location of the airplanes.

## Model Architecture

The RCNN model architecture consists of the following components:
1. **Region Proposal Network (RPN)**: Generates candidate object regions.
2. **Convolutional Neural Network (CNN)**: Extracts features from the proposed regions.
3. **Classifier**: Classifies the objects within the regions and refines the bounding boxes.




