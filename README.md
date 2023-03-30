# Drowsiness Detection Of Drivers Using Machine Learning Algorithms
### CSE3013- Artificial Intelligence Project 

---
#### Implementation: 
We have used OpenCV for gathering the images from the webcam and feeding them into a Deep Learning model that will classify whether the driver’s eyes are ‘Open’ or ‘Closed’. The approach we have used for the project is as follows:
 1. Take the image as input from a camera.
 2. Detect the face in the image and create a Region of Interest (ROI).
 3. Detect the eyes from ROI and feed them to the classifier.
 4. The classifier will categorize whether eyes are open or closed.
 5. Calculate the score to check whether the driver is drowsy.
 The model architecture file is used to classify if a person’s eye is open or closed. Download it from the link below and then save it under the "models/" folder before executing the file.
https://drive.google.com/file/d/15SM7Z0qbzk8Hmhhc3K5Y0C2gEL2ud1cK/view?usp=sharing
