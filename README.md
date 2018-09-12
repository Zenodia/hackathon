# hackathon
pre-worked dataset for hackathon
original data from kaggle : https://www.kaggle.com/kmader/electron-microscopy-3d-segmentation
pre-worked and simplified the dataset to binary classification instead of masking , also reduced the images data to 100 

# the challenge --
train a deep learning model that reaches at least 85% of accuracy 

note: train-test split is 80/20 
# hints :
the data is unbalanced 

you will need at least 3 conv-pool to get to the accuracy

you will need to save the best trained model in order to get to the accuracy 

use binary_crossentropy as loss and adam as optimizer , metrics is obvious accuracy 

