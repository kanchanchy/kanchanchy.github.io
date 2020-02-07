---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Most of my recent projects are related to machine learning and distributed database systems. Besides, I also developed some Android aplications before starting my PhD. Few of my projects are listed here. My other projects can be found on my [Github Repository](https://github.com/kanchanchy).

I loved to solve problems on UVa Online Judge and Light OJ when I was an undergraduate student. All of my solved problems on UVa Online Judge can be found [here](https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=20&page=show_authorstats&userid=77454). 

Optimizing Hyperparameters of CNN
======
Performance of a multi-layer neural network always depends on hyper-parameters such as learning rate, mini batch size, dropout rate, starting learning rate, and learning rate etc. Optimizing hyper-parameters of a multi-layer neural network is always a challenging task. This project implements two ways of optimizing hyper-parameters of a convolutional neural network and compares their performances: 1) Grid Search and 2) Bayesian Optimization. It optimizes three particular hyper-parameters: learning rate, dropout for first fully connected layer and dropout for second fully connected layer. The implementation is based on Pytorch framework.

Project Link: [Github Repository](https://github.com/kanchanchy/Optimizing-Hyperparameters-CNN)

Hotspot Analysis using New York Taxitrip Data
======
This project performs three tasks. 1) It writes two User Defined Functions: ST_Contains and ST_Within in SparkSQL and uses them to perform spatial queries such as Range Query and Distance Query. 2) Hotzone Analysis: it performs a range join operation on a rectangle dataset and a point dataset. For each rectangle, the number of points located within the rectangle is obtained. The hotter rectangle means that it include more points. 3) Hotspot Analysis: it implements a Spark program to calculate the Getis-Ord statistic of NYC Taxi Trip datasets. It is hot cell analysis. A G score is calculated for each cell, and higher G score means hotter cell. The topic of this task is from ACM SIGSPATIAL GISCUP 2016. The Problem Definition page is [here](http://sigspatial2016.sigspatial.org/giscup2016/problem).

Project Link: [Github Repository](https://github.com/kanchanchy/Hotspot-Analysis-Taxitrip-Data)

Multi-layer Neural Network from Sketch
======
This project shows the sketch implementation of a multi-layer neural network using numpy. It implements various functions used in a deep neural network and uses those functions to train and test a multi-layer neural network. The project shows the implementation of following functions: 1)Parameter initialization, 2)Relu activation, 3)Gradient of relu activation, 4)Linear activation, 5)Derivative of linear activation, 6)Softmax cross entropy loss, 7)One hot representation of classes, 8)Derivative of softmax cross entropy loss, 9)Forward dropout, 10)Backward dropout, 11)Single layer forward propagation, 12)Multi-layer forward propagation, 13)Single layer backward propagation, 14)Multi-layer backward propagation, 15)Classification/Prediction, 16)Calculating momentum, 17)Updating parameters with momentum, 18)Multi-layer neural network

Project Link: [Github Repository](https://github.com/kanchanchy/Multilayer-Neural-Network-from-Sketch)

GGfone: Free Voice Calls Over Wifi + Wifi Calling
======
GGfone is an Android platform based mobile application featuring high-quality international calls at super affordable costs, unlimited free voice calls with HD quality between this application users, transfering credit balance to other users, and earning free credit by doing simple tasks. This application was developed during my work at Gagagugu PTE LTD.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.gagagugu.ggfone)

GagaGugu Android Application
======
GagaGugu is an Android platform based mobile application which supports social networking and communications. Supported functionalities include but are not limited to messaging, free audio and video calls, updating posts, sharing videos, news, and other posts. This application was developed during my work at Gagagugu PTE LTD.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.gagagugu.connect)

Image classification with CNN using Keras
======
This project implements a convolutional neural network (CNN) model using Keras framework. After that, it performs training and testing on CNN model for classifying MNIST dataset. The CNN used here consists of two convolution layers. Each convolution layer is followed by a pooling layer. Convolution and pooling layers are followed by three fully connected layers where the last fully connected layer is the output layer.

Project Link: [Github Repository](https://github.com/kanchanchy/CNN-Keras)

Tic Tac Toe Childhood Game
======
It is an Android operating system based childhood game. It's mainly played between two players connecting two devices through bluetooth. If a partner player is not available, user can also play it with Android where Android acts as a player. There are two symbols: Circle and Cross. Each player use one symbol. There are a square number of boxes in a grid. Each player put his symbol in either one of the remaining boxes. The player who can first match his symbol horizontally, vertically or diagonally wins the match. If no matching is possible then the game is tied.

Project Link: [Playstore](https://play.google.com/store/apps/details?id=com.applicationslab.tictactoe&hl=en) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [Github Repository](https://github.com/kanchanchy/Tic-Tac-Toe)

Ayurvedic Treatment
======
It's an Android application providing useful home treatment information for various diseases. Provided information helps in knowing which plants are good for which diseases. It also helps in diagnosis of diseases based on symptoms. It helps in determining the BMI status, and necessary dietary tips are provided based on BMI status. It also shows the nearest hospitals on Google map.

Project Link: [Github Repository](https://github.com/kanchanchy/Ayurvedic-Treatment)

