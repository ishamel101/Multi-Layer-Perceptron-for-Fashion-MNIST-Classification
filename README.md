# Introduction
In this practical, we implement and train a feed-forward neural network (also known as an "MLP" for "multi-layer perceptron") 
on a dataset called "Fashion MNIST", consisting of small greyscale images of items of fashion.

# Data
In this practical, we use the Fashion MNIST dataset consisting of 70,000 greyscale images and their labels. The dataset is divided
 into 60,000 training images and 10,000 test images. The idea is to train a **classifier** to identify the class value 
 (what type of fashion item it is) given the image. We train and *tune* a model on the 60,000 training images and then evaluate 
 how well it classifies the 10,000 test images that the model did not see during training. This task is an example of a **supervised learning** problem, 
 where we are given both input and labels (targets) to learn from. This is in contrast to **unsupervised learning** where we only have inputs from which 
 to learn patterns or **reinforcement learning** where an agent learns how to maximise a reward signal through interaction with its environment. 

 # Steps
 1. Preprocessing: Data loading, exploration, and visualization.
2. Model Building: Implementing a Multi-Layer Perceptron architecture.
3 .Training: Optimizing the model on the Fashion MNIST dataset.
4. Evaluation: Assessing model performance through metrics and visualizations.
(...)
