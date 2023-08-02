# Plant Disease Detection with Deep Convolutional Neural Network

  <img src="https://qyuo.dev/AI4ALL_PDD.svg" alt="Plant Disease Detection" width="600">


This repository contains the implementation of a deep convolutional neural network (CNN) for optimizing plant disease detection, developed as part of the AI4ALL Program at Carnegie Mellon University. The model utilizes transfer learning with a ResNet 50 architecture and incorporates advanced data augmentation techniques to improve model performance and generalization.

## Background 

Plant disease detection is a critical task in agriculture as it helps identify and address potential threats to crop health. Deep learning techniques, especially convolutional neural networks, have shown great promise in accurately detecting diseases in plants. This project aims to build an efficient and accurate CNN-based model for plant disease classification.

## Data

The dataset used for training and evaluation consists of images of healthy plants and plants affected by various diseases. The dataset contains a diverse collection of plant species and disease classes to ensure robustness and real-world applicability of the model.

## Model Architecture

The deep CNN is built using the ResNet 50 architecture as the base model. Transfer learning is employed to leverage the knowledge learned from large-scale datasets and adapt it to our plant disease detection task. The pre-trained ResNet 50 model is fine-tuned on our custom dataset to achieve high accuracy and efficiency.

## Dependencies

- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV

## Acknowledgments

This project was developed as part of the AI4ALL Program at Carnegie Mellon University, and it builds upon the knowledge and expertise shared by the program mentors.
