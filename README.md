Project Name: Melanoma Skin Cancer Detection

Problem Statement:

In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.


Model Architecture:

Model: "sequential_3"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 rescaling_3 (Rescaling)     (None, 180, 180, 3)       0         
                                                                 
 conv2d_9 (Conv2D)           (None, 178, 178, 32)      896       
                                                                 
 max_pooling2d_9 (MaxPooling  (None, 89, 89, 32)       0         
 2D)                                                             
                                                                 
 conv2d_10 (Conv2D)          (None, 87, 87, 64)        18496     
                                                                 
 max_pooling2d_10 (MaxPoolin  (None, 43, 43, 64)       0         
 g2D)                                                            
                                                                 
 conv2d_11 (Conv2D)          (None, 41, 41, 128)       73856     
                                                                 
 max_pooling2d_11 (MaxPoolin  (None, 20, 20, 128)      0         
 g2D)                                                            
                                                                 
 dropout_6 (Dropout)         (None, 20, 20, 128)       0         
                                                                 
 flatten_3 (Flatten)         (None, 51200)             0         
                                                                 
 dense_3 (Dense)             (None, 128)               6553728   
                                                                 
 dropout_7 (Dropout)         (None, 128)               0         
                                                                 
 dense_4 (Dense)             (None, 9)                 1161      
                                                                 
=================================================================
Total params: 6,648,137
Trainable params: 6,648,137
Non-trainable params: 0
_________________________________________________________________

Conclusion:
1) There was some overfitting the data after adding 1000 sample data to solve the class imbalance but after reducing the sample data for 500, overfitting gone. 2) I have recieved the accuracy: 0.8748 - val_loss: 0.2383 - val_accuracy: 0.9147 finally that looks good to make 3) Augmentor helped alot to add the sample images to manage the class imbalance
