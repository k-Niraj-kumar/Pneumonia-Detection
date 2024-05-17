# Pneumonia Detection using Chest X-Rays

## Project Overview
This project aims to develop an accurate and efficient system for detecting pneumonia from chest X-ray images using deep learning techniques. 
The goal is to enable timely diagnosis and improve patient outcomes while minimizing misdiagnosis and unnecessary interventions.

## Motivation
Pneumonia is a serious respiratory illness that can be life-threatening if not diagnosed and treated promptly. 
Existing pre-trained models like InceptionV3 and VGG16, while achieving high accuracy on training data, often see a significant drop in performance when applied to test data. Additionally, these models involve a large number of parameters (around 20 million), making them computationally expensive and less efficient.

## Proposed Solution
In this project, we propose a custom convolutional neural network (CNN) model built using TensorFlow and Keras libraries. Our model is designed to be lighter, with around 10 million parameters, while maintaining high accuracy. By optimizing the architecture, we aim to achieve better performance on test data compared to existing approaches.

## Results
Our proposed model achieved an impressive 94% accuracy on the test data, outperforming pre-trained models like InceptionV3 and VGG16, which typically see a drop from 95-97% accuracy on training data to around 91% on test data. The lighter architecture made our model more efficient while still delivering high accuracy, enabling fast and accurate pneumonia detection for timely treatment decisions.
