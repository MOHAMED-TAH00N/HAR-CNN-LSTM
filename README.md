# HAR-CNN-LSTM

Human Activity Recognition using CNN and LSTM networks.

## Overview

This project implements a deep learning pipeline for Human Activity Recognition (HAR) using a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. 
The system is capable of analyzing videos and predicting human actions such as walking, running, boxing, hand clapping, and hand waving. 

## Features

- Preprocessing of video data into frames
- CNN feature extraction from individual frames
- LSTM sequence modeling to capture temporal dependencies
- Output annotated videos showing predicted actions
- Modular and scalable architecture suitable for extension to larger datasets

## Dataset

This project uses the [KTH Action Dataset](http://www.nada.kth.se/cvap/actions/) which contains videos of 6 human actions:
- Walking
- Running
- Boxing
- Hand Clapping
- Hand Waving
- Jogging

## Requirements

```bash
pip install tensorflow keras opencv-python moviepy numpy
