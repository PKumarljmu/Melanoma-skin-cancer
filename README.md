Project Name: Melanoma Skin Cancer Detection

Problem Statement:

In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. The aims to shorten the current gap to just a couple of days by providing the predictive model. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.


Model Architecture:
Epoch 1/20
169/169 [==============================] - ETA: 0s - loss: 2.0475 - accuracy: 0.2159
Epoch 1: val_accuracy improved from -inf to 0.39151, saving model to model.h5
169/169 [==============================] - 290s 2s/step - loss: 2.0475 - accuracy: 0.2159 - val_loss: 1.5685 - val_accuracy: 0.3915
Epoch 2/20
169/169 [==============================] - ETA: 0s - loss: 1.5765 - accuracy: 0.4006
Epoch 2: val_accuracy improved from 0.39151 to 0.47144, saving model to model.h5
169/169 [==============================] - 287s 2s/step - loss: 1.5765 - accuracy: 0.4006 - val_loss: 1.3460 - val_accuracy: 0.4714
Epoch 3/20
169/169 [==============================] - ETA: 0s - loss: 1.4101 - accuracy: 0.4685
Epoch 3: val_accuracy improved from 0.47144 to 0.51706, saving model to model.h5
169/169 [==============================] - 289s 2s/step - loss: 1.4101 - accuracy: 0.4685 - val_loss: 1.2776 - val_accuracy: 0.5171
Epoch 4/20
169/169 [==============================] - ETA: 0s - loss: 1.2936 - accuracy: 0.5128
Epoch 4: val_accuracy improved from 0.51706 to 0.58995, saving model to model.h5
169/169 [==============================] - 295s 2s/step - loss: 1.2936 - accuracy: 0.5128 - val_loss: 1.1292 - val_accuracy: 0.5899
Epoch 5/20
169/169 [==============================] - ETA: 0s - loss: 1.1527 - accuracy: 0.5720
Epoch 5: val_accuracy improved from 0.58995 to 0.67470, saving model to model.h5
169/169 [==============================] - 295s 2s/step - loss: 1.1527 - accuracy: 0.5720 - val_loss: 0.8709 - val_accuracy: 0.6747
Epoch 6/20
169/169 [==============================] - ETA: 0s - loss: 1.0610 - accuracy: 0.6118
Epoch 6: val_accuracy improved from 0.67470 to 0.69418, saving model to model.h5
169/169 [==============================] - 294s 2s/step - loss: 1.0610 - accuracy: 0.6118 - val_loss: 0.8542 - val_accuracy: 0.6942
Epoch 7/20
169/169 [==============================] - ETA: 0s - loss: 0.9179 - accuracy: 0.6588
Epoch 7: val_accuracy improved from 0.69418 to 0.74221, saving model to model.h5
169/169 [==============================] - 296s 2s/step - loss: 0.9179 - accuracy: 0.6588 - val_loss: 0.7500 - val_accuracy: 0.7422
Epoch 8/20
169/169 [==============================] - ETA: 0s - loss: 0.8352 - accuracy: 0.6908
Epoch 8: val_accuracy improved from 0.74221 to 0.77615, saving model to model.h5
169/169 [==============================] - 297s 2s/step - loss: 0.8352 - accuracy: 0.6908 - val_loss: 0.6422 - val_accuracy: 0.7761
Epoch 9/20
169/169 [==============================] - ETA: 0s - loss: 0.7486 - accuracy: 0.7239
Epoch 9: val_accuracy improved from 0.77615 to 0.79043, saving model to model.h5
169/169 [==============================] - 298s 2s/step - loss: 0.7486 - accuracy: 0.7239 - val_loss: 0.6247 - val_accuracy: 0.7904
Epoch 10/20
169/169 [==============================] - ETA: 0s - loss: 0.6708 - accuracy: 0.7485
Epoch 10: val_accuracy improved from 0.79043 to 0.83012, saving model to model.h5
169/169 [==============================] - 298s 2s/step - loss: 0.6708 - accuracy: 0.7485 - val_loss: 0.5679 - val_accuracy: 0.8301
Epoch 11/20
169/169 [==============================] - ETA: 0s - loss: 0.6118 - accuracy: 0.7787
Epoch 11: val_accuracy improved from 0.83012 to 0.84180, saving model to model.h5
169/169 [==============================] - 300s 2s/step - loss: 0.6118 - accuracy: 0.7787 - val_loss: 0.4689 - val_accuracy: 0.8418
Epoch 12/20
169/169 [==============================] - ETA: 0s - loss: 0.5578 - accuracy: 0.7912
Epoch 12: val_accuracy improved from 0.84180 to 0.87908, saving model to model.h5
169/169 [==============================] - 299s 2s/step - loss: 0.5578 - accuracy: 0.7912 - val_loss: 0.3658 - val_accuracy: 0.8791
Epoch 13/20
169/169 [==============================] - ETA: 0s - loss: 0.5134 - accuracy: 0.8084
Epoch 13: val_accuracy did not improve from 0.87908
169/169 [==============================] - 299s 2s/step - loss: 0.5134 - accuracy: 0.8084 - val_loss: 0.5299 - val_accuracy: 0.8162
Epoch 14/20
169/169 [==============================] - ETA: 0s - loss: 0.4575 - accuracy: 0.8322
Epoch 14: val_accuracy did not improve from 0.87908
169/169 [==============================] - 298s 2s/step - loss: 0.4575 - accuracy: 0.8322 - val_loss: 0.3762 - val_accuracy: 0.8639
Epoch 15/20
169/169 [==============================] - ETA: 0s - loss: 0.4737 - accuracy: 0.8240
Epoch 15: val_accuracy did not improve from 0.87908
169/169 [==============================] - 299s 2s/step - loss: 0.4737 - accuracy: 0.8240 - val_loss: 0.3623 - val_accuracy: 0.8720
Epoch 16/20
169/169 [==============================] - ETA: 0s - loss: 0.4095 - accuracy: 0.8461
Epoch 16: val_accuracy did not improve from 0.87908
169/169 [==============================] - 299s 2s/step - loss: 0.4095 - accuracy: 0.8461 - val_loss: 0.3914 - val_accuracy: 0.8670
Epoch 17/20
169/169 [==============================] - ETA: 0s - loss: 0.4328 - accuracy: 0.8368
Epoch 17: val_accuracy improved from 0.87908 to 0.89373, saving model to model.h5
169/169 [==============================] - 299s 2s/step - loss: 0.4328 - accuracy: 0.8368 - val_loss: 0.3252 - val_accuracy: 0.8937
Epoch 18/20
169/169 [==============================] - ETA: 0s - loss: 0.4070 - accuracy: 0.8531
Epoch 18: val_accuracy improved from 0.89373 to 0.90560, saving model to model.h5
169/169 [==============================] - 300s 2s/step - loss: 0.4070 - accuracy: 0.8531 - val_loss: 0.2854 - val_accuracy: 0.9056
Epoch 19/20
169/169 [==============================] - ETA: 0s - loss: 0.3627 - accuracy: 0.8665
Epoch 19: val_accuracy improved from 0.90560 to 0.93231, saving model to model.h5
169/169 [==============================] - 304s 2s/step - loss: 0.3627 - accuracy: 0.8665 - val_loss: 0.1796 - val_accuracy: 0.9323
Epoch 20/20
169/169 [==============================] - ETA: 0s - loss: 0.3361 - accuracy: 0.8748
Epoch 20: val_accuracy did not improve from 0.93231
169/169 [==============================] - 300s 2s/step - loss: 0.3361 - accuracy: 0.8748 - val_loss: 0.2383 - val_accuracy: 0.9147

Conclusion:
1) There was some overfitting the data after adding 1000 sample data to solve the class imbalance but after reducing the sample data for 500, overfitting gone. 2) I have recieved the accuracy: 0.8748 - val_loss: 0.2383 - val_accuracy: 0.9147 finally that looks good to make 3) Augmentor helped alot to add the sample images to manage the class imbalance
