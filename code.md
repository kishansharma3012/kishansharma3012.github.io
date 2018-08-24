---
layout: page
permalink: /code/
title: Project
tags: [code]
modified: 3-10-2014
comments: false
---




### Master Thesis: Image-based count and Size Determination of Fly Larvae for bio-waste conversion with Deep Learning
## ETH Zurich, Switzerland (Jun. 2018 - PRESENT)
-Thesis aims to develop complete solution of automation of most laborious part of Bio-waste conversion by counting and estimating size of insect larvae.Prepared pixel-wise annotated labeled image dataset of fly larvae in MS-COCO style dataset format
-counting and size estimation by Detection : Implemented and compared state of the art Object detection algorithms, Faster RCNN, Mask RCNN, YOLO and SSD
-counting and size estimation by Histogram Prediction : Implemented fixed bin length and width ResNet-50  based regression model which predicts Histogram between larvae size and count (ResNet-50); developed learnable histogram layer based model (linear basis function); Novel learnable histogram layer model based on hierarchical basis function

### Detection and Tracking of Surgical Equipments
## PRAKTIKUM : Machine Learning For Medical Imaging (Oct. 2017 - Feb. 2018)
-Implemented U-Net and FCN architecture in Tensorflow for simultaneously detecting and estimating Laparoscopy surgical equipment pose using probability maps (joint locations) 
for EndoVis challenge dataset
-Achieved state of the art results for U-Net multiple tool pose estimation

### Autoencoding beyond Pixels using Learned Similarity metric
## SEMINAR : Deep Generative Models
- Submitted a comprehensive report by Analysing , implementing and constructively criticizing
the proposed methodology in the paper
- Presented the paper explaining the proposed technique and fundamentals of Autoencoder,
VAE, GAN and compared the results

### Object Pose Estimation Model Based Tracking
- Model Preparation: Associated the texture information with the 3D model using SIFT features in MATLAB
- Estimated pose using PnP and implemented RANSAC and refined the pose using Levenberg Mardquardt algorithm
- Performed tracking of the camera in respect to given 3D model for given sequence of images

### Random Forest: Object Classification \& Detection
- Extracted HOG descriptors of images using OpenCV library for training Binary Decision tree and Random Forest to classify images in C++
- Generated bounding boxes and used sliding window to classified contents within each bounding box, filtered out bounding boxes with low confidence using non maximal suppression
- Evaluated detection result by using metric used in pascal visual object challenge metric and plotted PR curve

### CNN: Object Classification \& Pose Estimation
- Implemented a batch generator forming triplet batches consisting of real images and synthetic rendered sample, using the quaternion similarity
- Constructed CNN closely following the LeNet architecture, implemented loss function as addition of triplet and pairs loss and trained network using Adam optimizer using Tensorflow
- Implemented KNN search to evaluate the network, visualized feature descriptors in 3D space and plotted confusion matrix

### Generation of Restraunt Review Sentences using Hidden Markov's Model
- Preprocessing of Large Yelp Dataset: Detected the duplicate reviews using Locality Sensitive Hashing with Cosine Similarity and removed them; cleaned the data in the sparse matrix structure
- Performed latent factor matrix factorisation using Alternating Optimisation and Gradient Descent(full-sweep and mini batch) for the recommendation of restaurant and compared their results

### Restaurant Recommendation for Massive Yelp Dataset
- Preprocessing of Large Yelp Dataset: Detected the duplicate reviews using Locality Sensitive Hashing with Cosine Similarity and removed them; cleaned the data in the sparse matrix structure
- Performed latent factor matrix factorisation using Alternating Optimisation and Gradient Descent(full-sweep and mini batch) for the recommendation of restaurant and compared their results

### Image based Plant Disease Detection using Deep Learning
- Performed classification task on the Plant Village Dataset to identify 26 diseases
- Modified Network architecture and used transfer learning to train ResNet-18, DenseNet, AlexNet, VGG-Net
- Achieved state of the art accuracies for DenseNet in test results

### Case Study-Bundesliga League Game Outcome Prediction
- Extracted expressive features such as Total goal score, current trend, goal scored and conceded etc. using
past 5 Bundesliga season data
- Approach I -Implemented Logistic multinomial regression using R library GlMNET to predict the outcome and final team ranking for 5th season using the past 4 season data
- Approach II - Modeled input features by using Poisson regression to predict goal scored by home and away teams and thus inferring the outcome and 5th season team standings

### Image Classification-CIFAR-10
- Performed linear classification with Softmax loss and optimized the loss function with SGD, Improved classification performance by training linear classifiers on features computed from the raw pixels
- Applied fully connected neural network of arbitrary depth for image classification on CIFAR-10 dataset \& Trained the network by using Adam update rule for optimization and introduced dropout and Batch Normalization
- Implemented and trained 3 layer convolutional network with drop out and batch normalization using Pytorch

### Semantic Segmentation using Transfer learning
- Performed semantic segmentation by doing transfer learning using Resnet18 pretrained ConvNet, modified last layers to perform segmentation and fine tuned some layers while keeping early layers fixed
- Trained the model by fine tuning last layers while keeping early layers fixed, Used CUDA libraries in PyTorch to decrease the training time

### Binary Segmentation -Gaussian Mixture Model Estimation
- Modeled densities of fore and background pixels based on their intensity by estimating 2 mixture of gaussians
- Applied estimated models to input image and segmented foreground and background regions in C++ using OpenCV

### Parallel Programming-Course Work
- Performed parallelism with C and modern C++ using tasks, Pthreads (static/dynamic) and hence computed histogram of the occurrences of ten famous actors in the book “War and Peace”
- Applied various features of OpenMP such as sections, tasks etc. to parallelize C code

### Scientific Computing Lab 
- Used Explicit and implicit time stepping methods upto 4th order for ordinary differential equations
- Solved stationary and instationary partial differential heat equations using Numerical methods
- Developed Solvers for large, sparse systems of linear equations, and build Adaptivity and adaptively refined discretisation grids

### Spam Classification
- Designed spam classification by using SVMs, improved the performance of spam classifier by prepossessing emails by lowercasing,removing non-words in addition with normalizing email address, url, numbers etc.
- Extracted features using a vocabulary list of frequently occurring words
