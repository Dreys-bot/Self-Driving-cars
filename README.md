# Self-Driving-cars

Self-Driving Cars is a project with the aim of learning a car to drive autonomously on a simulated track. This ability of the model to drive a car is learned from cloning
the behaviour of a human driver. The model is trained to predict an appropriate steering angle for every frame while driving and it is hen validated on a new track to check for generalization of the 
learned features for performing steering angle prediction. The model used here is the **Nvidia Model** consists of 9 layers, including a normalizatoin layer, 5 convolutional layers and 3 fully connected layers.

![](https://github.com/Dreys-bot/Self-Driving-cars/blob/main/images/nvidia_model1.PNG)

## Getting Started
 To build the project, you just need to run the requirements file to install all the dependencies.
 ``pip -r requirements.txt``
 
 ## Running the app
 
 To run the app, just run the follow command: ``python Drive.py``
 Then launch the udacity simulator.
