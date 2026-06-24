# PRODIGY_ML_04 - Hand Gesture Recognition

## Task

Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image data.

## Dataset

Leap Gesture Recognition Dataset from Kaggle.

## Technologies Used

* Python
* OpenCV
* NumPy
* Scikit-learn
* Jupyter Notebook

## Machine Learning Model

Support Vector Machine (SVM)

## Gesture Classes Used

* Palm
* Fist
* Thumb

## Steps Performed

1. Downloaded and extracted LeapGestRecog dataset
2. Selected 3 gesture classes for training
3. Loaded gesture images from dataset
4. Converted images to grayscale
5. Resized images to 64x64 pixels
6. Flattened images into feature vectors
7. Assigned labels to each gesture
8. Split dataset into training and testing sets
9. Trained SVM classifier
10. Evaluated model accuracy

## Dataset Used

* 50 Palm images
* 50 Fist images
* 50 Thumb images

Total images used: 150

## Model Accuracy

Accuracy achieved: **100%**

## Outcome

Successfully built a hand gesture recognition model using SVM to classify different hand gestures. This project improved understanding of image preprocessing, feature extraction, and machine learning-based gesture classification.
