In this folder I have provided solution to the Fruits 360 problem provided by Kaggle.

Here I wanted to see the difference between 'datagen.flow' & 'datagen.flow_from_directory' functions provided in Keras and Tensorflow 2.0 'preprocessing.image' modules.

When the input images are given in seperate folders (as in this problem) it is a lot more convinient to use 'datagen.flow_from_directory' as it automatically takes images from all subfolders and labels them accordingly.

I tried to get the same output using 'datagen.flow' and it took more complex coding and lot more extraction time.


You can download the dataset as part of the fruits and vegetable dataset in Kaggle:
https://www.kaggle.com/moltean/fruits
