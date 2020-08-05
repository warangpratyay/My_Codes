This is a simple program to demonstrate the use of openCV ( cv2 ).

Here I use the webcam to capture live footage using 'cv2.VideoCapture()' function.
This is sent frame by frame to a function called 'sketch'.
Here each frame is first converted to grayscale and to find the edges in the frame I make use of cv2's inbuilt 'Canny()' function.
This generates the sketching effect.

Finally all the frames are displayed in a loop using 'cv2.imshow()' function.
