# Computer Vision Coursework

This Git repository contains code and documentation for a computer vision coursework project. The project is divided into three projects, each focusing on different aspects of computer vision. Below is an overview of each project:

## First Project: Feature Extraction, Matching, and Homography Estimation

In this project, we explore the fundamental techniques of feature extraction and matching, along with homography estimation using RANSAC. The key components of this project include:

- **Feature Extraction:** We implement feature extraction techniques that involve creating a dog pyramid and computing brief descriptors for keypoints. These techniques enable us to identify distinctive points in images, which are crucial for various computer vision applications.

- **Feature Matching:** We develop methods for matching features between images. This is essential for tasks such as image stitching, object recognition, and more. We use descriptors obtained from the previous step for matching.

- **Homography Estimation with RANSAC:** Robust homography estimation is critical for tasks like image registration. We utilize the RANSAC (Random Sample Consensus) algorithm to compute the homography matrix that relates two images, even when there are outliers in the correspondence data.

## Second Project: Optical Flow - Lucas-Kanade Implementation

In this project, we delve into optical flow estimation, specifically the Lucas-Kanade method. We implement different versions of the Lucas-Kanade algorithm, including the naive approach, iterative refinement, and the use of image pyramids. Additionally, we provide practical examples of optical flow in action:

- **Naive Optical Flow:** We start with a basic implementation of Lucas-Kanade optical flow estimation to understand the core concepts.

- **Iterative Optical Flow:** We refine the initial estimates through an iterative process to improve the accuracy of optical flow vectors.

- **Pyramidal Optical Flow:** Utilizing image pyramids, we enhance optical flow estimation's performance, especially in cases with large motion.

- **Example Videos:** We include example videos to showcase the application of optical flow in real-world scenarios, such as tracking a moving person and stabilizing footage captured on a bumpy road.

## Third Project: Deep Learning with PyTorch on CIFAR-10 Dataset

In the final project, we shift our focus to deep learning using the PyTorch framework. We work with the CIFAR-10 dataset, a popular dataset for image classification, and explore various aspects of deep learning:

- **CIFAR-10 Dataset:** We provide code to load and preprocess the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 different classes.

- **Convolutional Neural Networks (CNNs):** We implement deep learning models, primarily Convolutional Neural Networks, to classify images into their respective classes.

- **Training and Evaluation:** We detail how to train the model on the dataset and evaluate its performance using metrics like accuracy and loss.

- **PyTorch Implementation:** All the deep learning models are implemented using PyTorch, making it easier for you to understand and experiment with different neural network architectures.
