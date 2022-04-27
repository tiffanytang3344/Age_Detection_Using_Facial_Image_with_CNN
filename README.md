# Age_Detection_Using_Facial_Image_with_CNN

In this age classification project, I performed exploratory data analysis on 33486 facial images which contain images from 1 to 116 years old. 
I utilized **Tensorflow** library to perform feature extraction and build a deep learning model with **Convolutional Neural Network**. I used **Google Colab** on my personal machine while utilizing the free GPU to train my deep learning model. While training my CNN model, I used *tf.keras.callbacks.earlystopping* as a callback to monitor the validation loss so as to avoid over-fitting. After fitting the model for 20 epochs, I obtained 45.01% train accuracy and 40.00% validation accuracy. 





DATASETS
The datasets used in this project are publicly available. 
1. Facial-age dataset: https://www.kaggle.com/datasets/frabbisw/facial-age
2. UTKFace dataset: https://susanqq.github.io/UTKFace/
