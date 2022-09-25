
# 10-Food-Class-Vision

The goal of creating this model was to beat "DeepFood", a 2016 paper which used a Convolutional Neural Network trained for 2-3 days to achieve 77.4% top-1 accuracy, using only 10% of the data, the preprocessed data was gotten from kaggle containing only #2,500 test images and #7,500 train images as compared to the original dataset which contains #75,000 train data and #25,000 test data.


https://www.researchgate.net/publication/304163308_DeepFood_Deep_Learning-Based_Food_Image_Recognition_for_Computer-Aided_Dietary_Assessment

Transfer learning was utilised to train this model and EfficientNetB7 model architecture was utilised.

The model was trained with 10 epochs, and the accuracy of the model when tested on the test data stood at 88%, which beats the DeepFood paper at 77% accuracy.

Below is the image that shows the loss and accuracy chart


![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/1.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/2.jpg?raw=true)

When we visualise the model on the test data, the images below shows the accuracy the model predict images visually


![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/3.jpg?raw=true)

The model labelled some images wrongly, below are some of the sample images the model predicted wrongly...


![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/4.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/5.jpg?raw=true)


custom images were downloaded from the internet to further test the model on data, it has not being exposed to before, and to see how the model will perform in real world scenarios, and the images below was how the model predicted the images given to it



![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/6.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/7.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/8.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/9.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/10.jpg?raw=true)

![](https://github.com/Josehope/10-Food-Class-Vision/blob/master/screenshot/11.jpg?raw=true)



For further development on how to improve the model, my suggestions will be tweaking the learning rate, change the last 5 layers of the transfer learning model to fine tune the model to improve its accuracy, and training the model with enough images... this model utilise just 10% of the original data, and got 88% accuracy, if more images were used in training this model, the accuracy will be greatly improved.
