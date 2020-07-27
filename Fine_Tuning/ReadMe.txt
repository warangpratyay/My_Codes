This folder contains the solution to the Kaggle project of classifying flowers into 17 categories.

I have used Transfer Learning & Fine Tuning by using VGG16 as bottom model and retraining the top model to suit our Flower classifier problem.

I have made use of ImageDataGenertor to induce small changes in the images at every epoch as the input dataset is quite small.

Checkpoints and Earlystopping have been used to reach a maximum validation accuracy of 85.79%

Later I have tried to reduce the training time by setting the input image size to 64 * 64 which reduced the training time significantly from around 1200s per epoch to about 30s per epoch.
Maximum validation accuracy dropped to 70%

Dataset can be downloaded from Kaggle:
https://www.kaggle.com/saidakbarp/17-category-flowers
