# Facial-Emotion-Recogniton
A Facial Emotion Recognition System developed using the Haar Cascade machine learning algorithms.
Trained the system with 35,887 facial images and enhanced results using a 4-layer CNN architecture and advanced pre-processing on the FER-2013 dataset attaining 63.4% accuracy.

This project aims to classify the emotion on a person's face into one of seven categories, using deep convolutional neural networks. The data set consists of 48x48 pixel images of faces.

The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories .
     0=Angry;  
     1=Disgust; 
     2=Fear; 
     3=Happy; 
     4=Sad; 
     5=Surprise; 
     6=Neutral.

**STEPS:**
1. Install the dependencies.
2. Convert the csv file images to PNG images.
3. Train the model .
4. Run the program to detect faces.

**ALGORITHM**
1. HAAR cascade is used to detect object in the video or image. 
2. The object or face to be detected is limited to 48*48 and is fed as an 
    input to CNN.             	
3. The output is a list of scores of seven different emotions. 
4. The emotion label with the maximum score is displayed on the screen


- Accuracy of the model: 63.4%
- Number of epochs: 50
- Size of training dataset: 28,000 images
- Size of testing dataset: 7,000 images



