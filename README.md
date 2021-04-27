# Gesture-Recognition---Deep-Learning-Models
## Problem Statement
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

## Gesture	Corresponding Action
Thumbs Up	Increase the volume.
Thumbs Down	Decrease the volume.
Left Swipe	'Jump' backwards 10 seconds.
Right Swipe	'Jump' forward 10 seconds.
Stop	Pause the movie.
Each video is a sequence of 30 frames (or images).

## Objectives:
Generator: The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

Model: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

## Dataset:
You can download the dataset from here (https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL). The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.It looks like this: dataset
![image](https://user-images.githubusercontent.com/72683459/116293060-100a6280-a7b4-11eb-8b6d-35c5883bd810.png)

## Results:

![image](https://user-images.githubusercontent.com/72683459/116293006-ff59ec80-a7b3-11eb-8df2-7ee35bf3e748.png)

I choose CNN+LSTM based model as the final choice due to fairly decent accuracy considering the type of data as well the no. of parameters as I wanted my model to be light weight in nature.
