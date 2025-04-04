# Emotion-detection-CNN

# Problem Statement
According to statistics by WHO, more than 15% of adults have mental issues due to workplace pressure. Detecting and analyzing emotions to improve psychological well-being is necessary.

# Dataset Description 

* The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image.
* The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).
* The training set consists of 28,709 examples and the public test set consists of 3,589 examples.
* https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset

# Model Description

## CNN
I have used Convolutional Neural Network for our Project. I have trained CNN to predict human emotions using TensorFlow, OpenCV, and Keras.

## Layers of CNN
Here I used 4 convolutional layers and 2 fully connected layers where we have performed max pooling and batch normalization.

## Fitting Model
For fitting the model with training and validation data we have used the Keras library and using that only we have predicted the accuracy of the model.

# Flowchart - Building the Model
![image](https://github.com/Khizar-Baig/Emotion-detection-CNN/assets/59732957/96ed5250-50eb-4a4a-b179-f6a04e9044d4)

# Flowchart - Main.py
![image](https://github.com/Khizar-Baig/Emotion-detection-CNN/assets/59732957/8681ba25-27bb-48c1-9307-01a84110e974)

# Result and Output
![image](https://github.com/Khizar-Baig/Emotion-detection-CNN/assets/59732957/0dbba277-6bd4-408d-994b-28786512ed6b)

# Accuracy & Loss Analysis
![image](https://github.com/Khizar-Baig/Emotion-detection-CNN/assets/59732957/a602540b-3f49-4740-b0cc-c4f25b7dbab4)






