This folder contains the solution to the Kaggle project of classifying monkeys into 10 species.

I have used Transfer Learning by using mobilenet as bottom model and retraining the top model to suit our monkey classifier problem.

I have made use of ImageDataGenertor to induce small changes in the images at every epoch as the input dataset is quite small.

Checkpoints and Earlystopping have been used to reach a maximum validation accuracy of 93.75%

Dataset can be downloaded from Kaggle:
https://www.kaggle.com/slothkong/10-monkey-species
