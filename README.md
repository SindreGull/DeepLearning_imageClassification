# DeepLearning_imageClassification

This project implements a CNN classifier using with ResNet50 to classify images into 6 distinct categories. Also included is data preprocessing, augmentation, model training, evaluation, and test prediction generation.

Features of the mpodel include:

- Model learning using ResNet50 (pre-trained on ImageNet)
- Preprocessing: resizing, reshaping, normalization
- Data augmentation using ImageDataGenerator
- Handles class imbalance with calculated class weights
- Evaluation with balanced accuracy, confusion matrix, and classification report
  

## Files in this repository

─ ML4.py is the core model training and evaluation logic
- Main.py contains the basic statistics and result summary
─ Xtrain_Classification2.npy contains the flattened training images
─ ytrain_Classification2.npy are the training labels
─ Xtest_Classification2.npy contains the flattened images for the testing of teh model
─ test_predictions.npy are the saved predictions on the test set
