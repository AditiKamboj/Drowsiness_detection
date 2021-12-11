In this Python project, we will be using OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach is as follows :
1. Take image as input from a camera.
2. Detect the face in the image and create a Region of Interest (ROI).
3. Detect the eyes from ROI and feed it to the classifier.
4. Classifier will categorize whether eyes are open or closed.
5. Calculate score to check whether the person is drowsy.
