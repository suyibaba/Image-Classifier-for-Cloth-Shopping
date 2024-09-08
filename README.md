# Image-Classifier-for-Cloth-Shopping

      
    BUSINESS CASE
    
                  This is a project to classify the images of cloths available in a boutique and to create a Neural Network that will predict the type of dressing features to be selected by a potential customer. 
                  
                        
                        The Datasets comprises of 80,000 different fashion features images comprising of 
                        "T shirt","Trouser","Pullover","Dress","Coat","Sandal","Shirt","Sneaker","Bag","Ankle boot". 
                        
                        
                   The following libraries where imployed to develop the model and make the prediction.
                   
import numpy as np
import pandas as pd
%matplotlib inline
import matplotlib as mpl
import matplotlib.pyplot as plt
import tensorflow as tf
from tensorflow import keras 


                        Model Process:
                        
                        Data Gathering
                        Data Spliting
                        Normalizing Data
                        SPLIT THE DATA INTO TRAIN/VALIDATION/TEST DATASETS - 60,000 datasets for training and 10,000 test datasets. I further split the data into train/validation. validation data is used for tuning the hyperparameters and evaluate the models, IT IS used to optimized the performance of our models
                        Created the Neural Network using KNN

![image](https://user-images.githubusercontent.com/64482231/196857346-ccaea5b1-1ea3-40be-9cbe-06ab63a28918.png)



                        COMPILE AND TRAIN MODEL
                        plot how our accuracy are changing with each epoch - 

![image](https://user-images.githubusercontent.com/64482231/196857283-28780eba-1cd6-4ea5-b8a2-90fa94c46b5d.png)



                        with each epoch, the training accuracy and the validation accuracy is increasing and the loss is decreasing
                        from evaluating the performance , the performance of my model was 0.88 which is good. 
                        
                        PREDICT PROBABLITIES AND PREDICT CLASS OF NEW UNSEEN DATA
                        
