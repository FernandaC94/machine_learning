# Tennis Players Classifiers :tennis:
In this project I created my own dataset of images for my favourite four tennis players and used it as my dataset to train and test different ML classifiers. 

The steps I took are the following:
1. **Image preprocessing**
    - Using Haar-cascades for eyes and face detection to crop the images which contain two eyes and save them in a folder
    - Using Wavelet Decomposition techniques for feature extraction
    - creating our dataset 
    - Performing data augmentation techniques to balance the dataset
2. **Model Selection using GridSearchCV**
    - Hyperparameter tuning for Random Forest, Logistic Regression and Support Vector Classifier with and without balancing the dataset. 
    - Comparing training and test accuracy before and after balancing the dataset
