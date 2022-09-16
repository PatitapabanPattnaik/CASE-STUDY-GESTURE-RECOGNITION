# CASE-STUDY-GESTURE-RECOGNITION

Neural Network Project - Gesture Recognition

Problem Statement:

Develop an algorithm for a smart TV that can recognise five different gestures performed by the user which will help control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command.

Understanding the Dataset

The training data is categorized into one five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames (images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.

Objective

For analysing videos using neural networks, two types of architectures are used commonly. One is the standard CNN + RNN architecture in which the images of a video are passed through a CNN which extracts a feature vector for each image, and then pass the sequence of these feature vectors through an RNN. The objective of this assignment is to train different models on the 'train' folder to predict the action performed in each sequence or video and which performs well on the 'val' folder as well. The final test folder for evaluation is withheld - final model's performance will be tested on the 'test' set.
