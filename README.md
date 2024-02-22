# Image Classification using ANN
In this project, we explore the task of image classification using Artificial Neural Networks (ANNs). ANNs are a type of neural network where neurons in one layer are connected to all neurons in the next layer.

 ## Introduction
The task involves classifying images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images divided into 10 classes. Each class contains 6,000 images, with 5,000 for training and 1,000 for testing. This dataset offers a diverse range of objects and animals, making it an excellent benchmark for image classification tasks.

## Dataset Overview
The CIFAR-10 dataset is pre-loaded within TensorFlow, facilitating seamless integration into our project. Upon loading the dataset, it is divided into training and testing sets, with input images and corresponding labels. Additionally, preprocessing steps are performed to normalize pixel values and convert labels into one-hot encoded vectors.

## Model Architecture
Our Artificial Neural Network model consists of three layers: one input layer, two hidden layers, and one output layer. The input layer flattens the image tensors, while the hidden layers use ReLU activation functions for feature extraction. The output layer employs a sigmoid activation function to produce class probabilities for each image.

## Conclusion
Through this project, we demonstrate the effectiveness of Artificial Neural Networks in image classification tasks. By leveraging TensorFlow and carefully crafted model architecture, we achieve impressive accuracy in classifying CIFAR-10 images. This project showcases the power of deep learning techniques in computer vision applications.






