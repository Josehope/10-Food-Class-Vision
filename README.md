
# 10-Food-Class-Vision

The goal of creating this model was to beat "DeepFood", a 2016 paper which used a Convolutional Neural Network trained for 2-3 days to achieve 77.4% top-1 accuracy, using only 10% of the data, the preprocessed data was gotten from kaggle containing only #2,500 test images and #7,500 train images as compared to the original dataset which contains #75,000 train data and #25,000 test data.


https://www.researchgate.net/publication/304163308_DeepFood_Deep_Learning-Based_Food_Image_Recognition_for_Computer-Aided_Dietary_Assessment

Transfer learning was utilised to train this model and EfficientNetB7 model architecture was utilised.

The model was trained with 10 epochs, and the accuracy of the model when tested on the test data stood at 88%, which beats the DeepFood paper at 77% accuracy.


