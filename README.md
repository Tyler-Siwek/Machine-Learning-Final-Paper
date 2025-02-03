# Machine-Learning-Final-Paper

Attatched is the paper describing the project

Abstract— This project is looking to use image data to determine the location an image was taken. This is done through training on image data from various rooms in an indoor environment and implemented on an embedded device through a convolutional neural network.
Keywords—Embedded systems, Image detection, Tensorflow, TFlite
I.	INTRODUCTION 
The goal of my project is to connect an image with the location it was taken using a neural network. Being able to connect photos to a location has many practical applications in areas such as automatic geotagging of images posted to a website, a redundant check on navigation systems in autonomous vehicles to confirm and increase the accuracy of GPS and speeding up the logging of map data in cities. Additionally, this can be a helpful tool for certain indoor mapping problems, such as indoor navigation or a maintenance reporting system that automatically tags a reported location to help workers locate and optimize repairs. 
For this project, I worked with both indoor and outdoor data but found better results with indoor data given the embedded system application and reduced variability of environments over time. From my collected images, I train a custom ML model that uses deep convolution to predict a class (location/room) that the image was taken in. Next, I compress the model and send it to a raspberry pi where the tflite model is used to predict the location that an image was taken with the attached camera.  Model evaluation will use a set of images and finding the percentage of correct predictions. 

