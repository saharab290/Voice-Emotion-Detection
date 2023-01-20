# Voice-Emotion-Detection
Voice Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

Why we need it?

1. Emotion recognition is the part of speech recognition which is gaining more popularity and need for it increases enormously. Although there are methods to recognize emotion using machine learning techniques, this project attempts to use deep learning to recognize the emotions from data.

2. SER(Speech Emotion Recognition) is used in call center for classifying calls according to emotions and can be used as the performance parameter for conversational analysis thus identifying the unsatisfied customer, customer satisfaction and so on.. for helping companies improving their services

3. It can also be used in-car board system based on information of the mental state of the driver can be provided to the system to initiate his/her safety preventing accidents to happen


# Summary 
Inspired by LSTM Networks for Sentiment Analysis. Here is an implementation repo for training a LSTM neurtal networks with Sequential Model for recogonizing audio data's speaker gender and emotion. The audio data used is from Vox Forge. Data Science is supposed to handle all kinds of problems without having domain knowledge. We assume no knowledge exist for data scientist in Audio signal processing. 'FFT' is an alternative optioin instead of letting the neural nets learn the audio signal logic from raw wave data them self.

Datasets used in this project 
dataset link : https://paperswithcode.com/dataset/ravdess 
1.Crowd-sourced Emotional Mutimodal Actors Dataset (Crema-D) 
2.Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess) 
3.Surrey Audio-Visual Expressed Emotion (Savee) 
4.Toronto emotional speech set (Tess) 

# Fist of all the Load dataset
![data_s](https://user-images.githubusercontent.com/123153920/213757979-2421a7a5-1da8-425f-925b-4b9a66a1a7ad.png)

# Visualizetion
![Data_visualization_s](https://user-images.githubusercontent.com/123153920/213759835-3f4a2422-fecb-4afc-b95a-106a8808f9aa.png)

Visualized every types of emotion data from the dataset by using a waveplot
![waveplot_s](https://user-images.githubusercontent.com/123153920/213759115-314b5492-f725-49d6-a549-cee06b3f11ca.png)

# Methodology
Here is the total methodology of my project.
![methodology](https://user-images.githubusercontent.com/123153920/213760223-eaad714f-b587-4b72-b0cb-f3dbb50c5df0.jpeg)

After applying Sequential Process model i find a train and test accuracy and loss curve.
![Accuracy_plot_s](https://user-images.githubusercontent.com/123153920/213760693-ca114eca-2567-4ce8-a5dd-9c0d7e7c01b4.png)

# Confuision Matrix 
![CM_s](https://user-images.githubusercontent.com/123153920/213761474-7045da19-340f-4736-a7ee-98e9053541a0.png)

# Result
At the last we got an accuracy 61% with diffrent emotion samples. I use 4 types of dataset thats why my accuracy is low. 
![accuracy_s](https://user-images.githubusercontent.com/123153920/213762125-dc7ec569-9fe3-4134-9828-4d8b8eba4705.png)

# Requirments
tensorflow, numpy, scipy 


