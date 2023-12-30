---
layout: archive
permalink: /projects/
author_profile: true
---

{% include base_path %}

Problem Solving
======
I loved to solve problems on UVa Online Judge and Light OJ when I was an undergraduate student. Nowadays, I love to solve problems in LeetCode. I solved 305 problems in UVa Online Judge, 130+ problems in LeetCode, 46 problems in Light OJ and participated in many programming
contests both in real-time and online. I also answered some questions in StackOverflow.

Solved Problems Link: [UVa Online Judge](https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=20&page=show_authorstats&userid=77454).

Projects
======

GeoTorchAI Deep Learning Framework
------
GeoTorchAI, formerly known as GeoTorch, is a spatiotemporal deep learning framework on top of PyTorch and Apache Sedona. It enable spatiotemporal machine learning practitioners to easily and efficiently implement deep learning models targeting the applications of raster imagery datasets and spatiotemporal non-imagery datasets. Besides deep learning, it also supports scalable and distributed data preprocessing for raster and spatiotemporal datasets.

Project Link: [Github Repository](https://github.com/DataSystemsLab/GeoTorchAI)

ML Aware Spatial Data Repartitioning
------
This is a framework which aims at reducing the training time and memory usage of a spatial machine learning model by reducing the number of partitions in a spatial grid dataset. Experiments on four datasets achieved significant reduction in training time and memory consumption while bounding the difference in prediction error within 5%.

Project Link: [Github Repository](https://github.com/kanchanchy/spatial-repartitioning-ml)

Forecasting Climate Change with Deep Learning
------
This project builds and trains an LSTM model in order to predict global and US temperature from historical data. It shows all steps from raw data loading and preprocessing to model evaluation in a step-by-step procedure. Operations include: data loading, exploratory data analysis, data cleaning, data visualization, preparing data for model training, model building, training and evaluation.

Project Link: [Github Repository](https://github.com/kanchanchy/climate-change-forecasting-keras)

Spatio-Temporal Data Processing on Apache Spark/Apache Sedona
------
This work performs spatial and temporal data processing steps using Apache Sedona on the raw dataset of NYC Taxi Trip records (https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page). The final goal is to convert the dataset into two tensors: i) spatio-temporal tensor and ii) spatial grid tensor.

Project Link: [Github Repository](https://github.com/kanchanchy/Spatial-Data-Processing)

Data Visualization in Python
------
It performs statistical data analysis using useful visualizations with three Python libraries: Matplotlib, Seaborn, and Plotly Express. Visualizations include but are not limited to line plot, scatter plot, pie chart, histograms, bnar plots, subplot, 3D plot, pair plot, count plot, dist plot, heatmaps, correlation plot, gantt chart, bubble chart, sunburst, box plot, density plot, and violin plot.

Project Link: [Github Repository](https://github.com/kanchanchy/Data-Visualization-in-Python)

Fake News Detection using Bidirectional LSTM
------
This project builds and trains a bidirectional LSTM in order to perform fake news classification. It shows all steps from data loading and preprocessing to model evaluation in a step-by-step procedure. Operations include: data loading and feature engineering, data cleaning, data visualization, tokenization and feature vector generation, and model building, training and evaluation.

Project Link: [Github Repository](https://github.com/kanchanchy/Fake-News-Detection-BiLSTM)

Anomaly detection using Pycaret
------
This project builds and evaluates anomaly detection models using PyCaret. Performed operations include data loading from Pycaret library, exploring data with visualizations, preparing data for model, building, evaluating, and deploying anomaly detection model.

Project Link: [Github Repository](https://github.com/kanchanchy/anomaly-detection-pycaret)

Named Entity Recognition
------
Named Entity Recognition, NER in short, is a research problem which has gained growing interests from the NLP community. Recently, deep learning methods has achieved state-of-the-art performance in the task of recognizing named entity although performance improvement has become very slow at this stage. In this work, I tune various steps of the state-of-the-art deep learning methods for named entity recognition in order to experiment the changes in performance. I evaluate the tuned NER algorithms with two popular datasets: CoNLL-2003 and OntoNotes-5.0.

Project Link: [Github Repository](https://github.com/kanchanchy/Named-Entity-Recognition)

Hotspot Analysis using New York Taxitrip Data
------
This project performs three tasks. 1) It writes two User Defined Functions: ST_Contains and ST_Within in SparkSQL and uses them to perform spatial queries such as Range Query and Distance Query. 2) Hotzone Analysis: it performs a range join operation on a rectangle dataset and a point dataset. For each rectangle, the number of points located within the rectangle is obtained. The hotter rectangle means that it include more points. 3) Hotspot Analysis: it implements a Spark program to calculate the Getis-Ord statistic of NYC Taxi Trip datasets. It is hot cell analysis. A G score is calculated for each cell, and higher G score means hotter cell. The topic of this task is from ACM SIGSPATIAL GISCUP 2016. The Problem Definition page is [here](http://sigspatial2016.sigspatial.org/giscup2016/problem).

Project Link: [Github Repository](https://github.com/kanchanchy/Hotspot-Analysis-Taxitrip-Data)

Generative Adversarial Network in PyTorch
------
This project builds a generative adversarial network in PyTorch with MNIST dataset. The network consists of two models: generator model and discriminator model. Generator model generates fake images and discriminator model classifies fake and real images.

Project Link: [Github Repository](https://github.com/kanchanchy/generative-adversarial-network-pytorch)

Denoising Image using Autoencoder in PyTorch
------
This project builds an autoencoder model in PyTorch in order to perform denoising operation on images. For that purpose, it loads MNIST image datsets and adds noises to every image. Later, an autoencoder is built and trained to reproduce actual images from noisy images. It prepares a custom dataset on PyTorch which generates a noisy version of each image. In the training dataset, noisy images and original images serve as input data and labels respectively.

Project Link: [Github Repository](https://github.com/kanchanchy/Denoise-Image-Autoencoder)

Sentiment Analysis with BERT in PyTorch
------
The purpose of this project is to classify sentiment/emotions using twitter smile emotion dataset. It performs necessary data preprocessing, tokenization, and encoding to prepare the data for model training. After that, it sets up BERT pretrained model and performs training, evaluation, saving, and loading of the model.

Project Link: [Github Repository](https://github.com/kanchanchy/sentiment-analysis-bert-pytorch)

Optimizing Hyperparameters of CNN
------
Performance of a multi-layer neural network always depends on hyper-parameters such as learning rate, mini batch size, dropout rate, starting learning rate, and learning rate etc. Optimizing hyper-parameters of a multi-layer neural network is always a challenging task. This project implements two ways of optimizing hyper-parameters of a convolutional neural network and compares their performances: 1) Grid Search and 2) Bayesian Optimization. It optimizes three particular hyper-parameters: learning rate, dropout for first fully connected layer and dropout for second fully connected layer. The implementation is based on Pytorch framework.

Project Link: [Github Repository](https://github.com/kanchanchy/Optimizing-Hyperparameters-CNN)

Multi-layer Neural Network from Scratch
------
This project shows the scratch implementation of a multi-layer neural network using numpy. It implements various functions used in a deep neural network and uses those functions to train and test a multi-layer neural network. The project shows the implementation of following functions: 1)Parameter initialization, 2)Relu activation, 3)Gradient of relu activation, 4)Linear activation, 5)Derivative of linear activation, 6)Softmax cross entropy loss, 7)One hot representation of classes, 8)Derivative of softmax cross entropy loss, 9)Forward dropout, 10)Backward dropout, 11)Single layer forward propagation, 12)Multi-layer forward propagation, 13)Single layer backward propagation, 14)Multi-layer backward propagation, 15)Classification/Prediction, 16)Calculating momentum, 17)Updating parameters with momentum, 18)Multi-layer neural network

Project Link: [Github Repository](https://github.com/kanchanchy/Multilayer-Neural-Network-from-Scratch)

Image classification with CNN using Keras
------
This project implements a convolutional neural network (CNN) model using Keras framework. After that, it performs training and testing on CNN model for classifying MNIST dataset. The CNN used here consists of two convolution layers. Each convolution layer is followed by a pooling layer. Convolution and pooling layers are followed by three fully connected layers where the last fully connected layer is the output layer.

Project Link: [Github Repository](https://github.com/kanchanchy/CNN-Keras)

GGfone: Free Voice Calls Over Wifi + Wifi Calling
------
GGfone is an Android platform based mobile application featuring high-quality international calls at super affordable costs, unlimited free voice calls with HD quality between this application users, transfering credit balance to other users, and earning free credit by doing simple tasks. This application was developed during my work at Gagagugu PTE LTD.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.gagagugu.ggfone)

GagaGugu Android Application
------
GagaGugu is an Android platform based mobile application which supports social networking and communications. Supported functionalities include but are not limited to messaging, free audio and video calls, updating posts, sharing videos, news, and other posts. This application was developed during my work at Gagagugu PTE LTD.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.gagagugu.connect)

ChefOnline - Order Takeaway App
------
ChefOnline - Order Takeaway App is an Android based mobile application for restaurants developed supporting the features such as online orders and reservations. This application was developed during my work at Le Chef Plc.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.chefonline.chefonline)

Ayurvedic Treatment
------
It's an Android application providing useful home treatment information for various diseases. Provided information helps in knowing which plants are good for which diseases. It also helps in diagnosis of diseases based on symptoms. It helps in determining the BMI status, and necessary dietary tips are provided based on BMI status. It also shows the nearest hospitals on Google map.

Project Link: [Github Repository](https://github.com/kanchanchy/Ayurvedic-Treatment)

Tic Tac Toe Childhood Game
------
It is an Android operating system based childhood game. It's mainly played between two players connecting two devices through bluetooth. If a partner player is not available, user can also play it with Android where Android acts as a player. There are two symbols: Circle and Cross. Each player use one symbol. There are a square number of boxes in a grid. Each player put his symbol in either one of the remaining boxes. The player who can first match his symbol horizontally, vertically or diagonally wins the match. If no matching is possible then the game is tied.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.applicationslab.tictactoe&hl=en) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [Github Repository](https://github.com/kanchanchy/Tic-Tac-Toe)

My other projects can be found on my [Github Repository](https://github.com/kanchanchy).
------

