This folder contains the solution to the Simpsons Character Classification problem.

I have created a VGG type model with alternate convolution-normaliation-maxpooling-dropout layers.

I have made use of ImageDataGenertor to induce small changes in the images at every epoch as the input dataset is quite small.

Checkpoints and Earlystopping have been used to reach a maximum validation accuracy of 91.17%

A beautiful confusion matrix and classification report is generated at the end.

I have also used OpenCV to visualize the predicted outputs with true targets.


Dataset can be downloaded from Kaggle: 
https://www.kaggle.com/alexattia/the-simpsons-characters-dataset
