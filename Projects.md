---
layout: page
permalink: /Projects/
title: Projects
tags: [Projects]
modified: 3-10-2014
comments: false
---




### Master Thesis: Image-based count and Size Determination of Fly Larvae
#### ETH Zurich, Switzerland (Jun. 2018 - Dec. 2018)
- This thesis aims to develop complete solution of automation of most laborious part of Bio-waste conversion by counting and estimating size of insect larvae. Collected and Prepared pixel-wise annotated image dataset of fly larvae in MS-COCO style dataset format
- Implemented Mask RCNN algorithm for given objective and compared the population estimation result with CountCeption (Yoshua Bengio et al.) fully convolutional Network using redundant count map labels
- Developed novel approach for simultaneously predicting object count and size distribution histogram using CountCeption and ResNet network. 
- Reduced Mean absolute count error by half as compared to Mask RCNN, Observed a significant reduction in the KL divergence loss and the mean absolute L1 error for histogram prediction.
- Further reduced error by training model in Deep supervised fashion by predicting 2, 4 bin size distribution histogram as intermediate results. 
- Validated robustness of the developed method by preparing synthetic data of various sized thin ellipses following different probability distribution. Built GUI for user friendly usage of algorith.

### Detection and Tracking of Surgical Equipments
#### PRAKTIKUM : Machine Learning For Medical Imaging (Oct. 2017 - Feb. 2018)
- Prepared and preprocessed dataset using Robotic Laparoscopy surgical equipment videos from Endovis Challenge Dataset and created labels as gaussian probability maps of their joint locations
- Implemented UNet architecture to classify and localize joint locations of equipment; Trained Network using various training schedules for multiple objective learning; achieved state of the art accuracy for pose estimation of some equipments
- Modeled FCN using VGG and ResNet architecture, Compared the results of FCN and UNet based approaches

### Autoencoding beyond Pixels using Learned Similarity metric
#### SEMINAR : Deep Generative Models
- Submitted a comprehensive report by Analysing , implementing and constructively criticizing
the proposed methodology in the paper
- Presented the paper explaining the proposed technique and fundamentals of Autoencoder,
VAE, GAN and compared the results

### Object Pose Estimation Model Based Tracking
- The aim of the project was to track a texture-rich 3D object in a series of images using camera pose estimation and projection of the 3D object on the images in every input image. 
- A feature-rich 3d box was generated by backprojecting the sift features found in the initialization images to the 3d box. Using SIFT descriptors matching and RANSAC (Random Sample Consensus) an approximate camera pose was detected for new images. 
- Finally, after applying non-linear optimization using the Levenberg Marquardt algorithm an optimum pose was found. P3P, RANSAC, Lavenberg Marquardt, SIFT algorithms were used in the project. Performed tracking of the camera in respect to given 3D model for given sequence of images

### Random Forest: Object Classification \& Detection
- The aim of the project was to do object detection and classification simultaneously using Random forest classifier. Extracted HOG descriptors of images using OpenCV library for training Binary Decision tree and Random Forest to classify images belonging to 6 different classes in C++
- Generated bounding boxes and used sliding window to classify contents within each bounding box, filtered out bounding boxes with low confidence using non maximal suppression
- Evaluated detection result by using metric used in pascal visual object challenge metric and plotted PR curve

### CNN: Object Classification \& Pose Estimation
- This project implementation closely followed the approach of Wohlhart et al. (https://arxiv.org/abs/1502.05908). The aim of the project was to do pose estimation and object instance recognition of already-detected objects simultaneously by learning an appropriate discriminative feature space using CNN.
- The lower dimensional descriptors obtained using descriptor CNN preserved two important properties: 1) euclidean distance between descriptors of dissimilar objects should be large and 2) euclidean distance between descriptors of objects from same class should be relative to their poses. 
- The loss function was designed in a way to help maintain above-mentioned two properties. Loss function contained triplet loss (using three images at a time) and pairwise loss (using two images at a time).
- Implemented a batch generator forming triplet batches consisting of real images and synthetic rendered sample, using the quaternion similarity. Constructed CNN closely following the LeNet architecture and trained network using Adam optimizer using Tensorflow
- Evaluated the network on test images by implemented K- nearest neighbour search in descriptor space of training images to find object class and pose for the object present in test images.Visualized feature descriptors in 3D space and plotted confusion matrix
 
### Mining Massive Yelp Dataset
####Restaurant Recommendation
- The aim of this task was to recommend restaurants to users based on the rating data in the massive Yelp dataset and predict the rating a user will give to a restaurant they have not been to yet based on a latent factor model.
- Preprocessed data by detecting duplicate reviews using Locality Sensitive Hashing with Cosine Similarity and removed them 
- Performed latent factor matrix factorisation using A = P\*Q matrix factorization as the latent factor model where A is the matrix containing all users and reviews while P and Q are unknownusing Alternating Optimisation and Gradient Descent for the recommendation of restaurant and compared their results.
- Used two approaches for finding the factorization, Alternating optimization of P and Q, and Stochastic/Minibatch gradient descent optimization.
#### Restaurant Review Classification
- The aim of this project was to rank a subset of reviews given by users to restaurants in Las Vegas using Hidden Markov Model (HMM) as a probabilistic generative model for text data
- The dataset contained 1-star and 5-star reviews and two HMMs were used to learn the sequence structures of two datasets using  Baum-welch algorithm.
- After training, classfied test sequences as 1-star or 5-star based on which model gives a higher likelihood for the given sequence.
#### Restaurant Ranking 
- The aim of this project was to rank restaurants with the help of the PageRank algorithm using a directed weighted graph where each node represents one restaurant and  edges in this graph were based on users reviews.
-  Further extension was done to implement a topic-specific PageRank algorithm to find the top-ranked restaurants in a pre-defined topic/category by calculating standard page rank scores, like Mexican or Chinese, while a restaurant can have multiple topics/categories assigned to it.
#### Clustering Users
- The aim of this project was to cluster users using spectral clustraing on an undirected weighted graph of users based on reviews
- Qualitatively evaluated results using ratio cut and normalized cut

### Image based Plant Disease Detection using Deep Learning
- The aim of the project was to correctly classify the plant type and the disease it is having (if any) given an image of a plant leaf. 
- Plant village dataset was used which contains 54,306 images of 14 crop species having 26 different diseases. In total, there were 38 plant-disease pairs.
- Modified Network architecture and used transfer learning to train ResNet-18, DenseNet, AlexNet, VGG-Net, Achieved state of the art accuracies for DenseNet in test results

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
- Performed semantic segmentation by doing transfer learning using Resnet18 pretrained ConvNet on PASCAL semantic part dataset
- Trained the model by fine tuning last layers while keeping early layers fixed, Used CUDA libraries in PyTorch to decrease the training time

### Binary Segmentation -Gaussian Mixture Model Estimation
- The aim of the project was to do binary image segmentation of grayscale images using Gaussian mixture model (GMM) and Expectation maximization (EM) algorithm.
- A mixture of 5 Gaussians was trained on the foreground (input rectangular region of the given image) and a mixture of 5 Gaussians was trained on the background (whole image except foreground box) using pixel wise labeling into foreground and background. 
- After learning the foreground and background pixel intensity distribution a pixel-wise classification was done to perform final segmentation of the whole image into foreground and background.

### Generating 2D Velocity Fields using GAN
- Generated velocity fields of simple 2D plume fluid simulation using mantaflow (http://mantaflow.com/) software
- Modeled a simple Generative Adversarial Network (GAN) and generated 2d velocity fields, Modified the generator architecture to address the checkerboard problem, compared the results with including divergence-free condition

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
