# ASL_Detection

This repository contains the implementation of a Convolutional Neural Network (CNN) for recognizing American Sign Language gestures. Our goal is to bridge the communication gap between the Deaf and Hard of Hearing community and the hearing world through the power of artificial intelligence.

# Dataset 


For this we are going to use a dataset available on Kaggle : " Sign Language MNIST "
The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion).


# Conclusion 

we experimented with a straightforward approach to implement a CNN model. Our process involved data preprocessing, generation, and preparation for the model. To enhance the training process and prevent overfitting, we constructed the CNN using a sequence of Conv2D and Maxpooling layers, with BatchNormalization and dropout layers in between. Additionally, we included two Dense layers at the end, with the final one reducing the output to 24 features. In future notebooks, we plan to incorporate various techniques during training and model building to assess their impact on performance.
