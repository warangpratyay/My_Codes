In this project I combine a trained model for facial expression detector with openCV to build a Live Emotion Detector.

The steps used are as follows:

1) First I train a model to identify 7 types of expressions: 'Angry', 'Disgust', 'Fear', 'Happy', 'Neutral', 'Sad', 'Surprise'

2) I save this model in order to later use it to get predictions from our live feed. ( emotion_detector.h5 )

3) I use openCV's cv2.VideoCapture() function to get the live feed from webcam.

4) I take each frame from this feed and use a 'Haarcascades Face Classifier' to detect faces in each frame.

5) These detected faces are cropped and preprocessed in order to feed to our trained model.

6) The preprocessed & cropped faces are fed to the emotion_detector.h5 model to get the required output.

7) This output is mapped to the expression type and displayed on the frame with cv2's 'putText()' function.

8) All these frames are displayed on screen with use of cv2's imshow() function.

9) This whole process is run within a loop to get the Live Emotion Detector.
