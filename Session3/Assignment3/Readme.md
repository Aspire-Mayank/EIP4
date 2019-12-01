## Final Validation accuracy for Base Network
> Accuracy on test data is: 82.35

## Your model definition (model.add... ) with output channel size and receptive field

/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:7: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(48, (3, 3), input_shape=(32, 32, 3..., padding="same")`
  import sys
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:12: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(48, (3, 3), padding="same")`
  if sys.path[0] == '':
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:17: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(48, (3, 3), padding="same")`
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:24: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(96, (3, 3), padding="same")`
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:29: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(96, (3, 3))`
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:36: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(96, (3, 3), padding="same")`
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:41: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(96, (3, 3), padding="same")`
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:46: UserWarning: Update your `SeparableConv2D` call to the Keras 2 API: `SeparableConv2D(96, (3, 3))`
Model: "sequential_18"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
separable_conv2d_136 (Separa (None, 32, 32, 48)        219       
_________________________________________________________________
activation_145 (Activation)  (None, 32, 32, 48)        0         
_________________________________________________________________
batch_normalization_121 (Bat (None, 32, 32, 48)        192       
_________________________________________________________________
dropout_93 (Dropout)         (None, 32, 32, 48)        0         
_________________________________________________________________
separable_conv2d_137 (Separa (None, 32, 32, 48)        2784      
_________________________________________________________________
activation_146 (Activation)  (None, 32, 32, 48)        0         
_________________________________________________________________
batch_normalization_122 (Bat (None, 32, 32, 48)        192       
_________________________________________________________________
dropout_94 (Dropout)         (None, 32, 32, 48)        0         
_________________________________________________________________
separable_conv2d_138 (Separa (None, 32, 32, 48)        2784      
_________________________________________________________________
activation_147 (Activation)  (None, 32, 32, 48)        0         
_________________________________________________________________
batch_normalization_123 (Bat (None, 32, 32, 48)        192       
_________________________________________________________________
max_pooling2d_35 (MaxPooling (None, 16, 16, 48)        0         
_________________________________________________________________
separable_conv2d_139 (Separa (None, 16, 16, 96)        5136      
_________________________________________________________________
activation_148 (Activation)  (None, 16, 16, 96)        0         
_________________________________________________________________
batch_normalization_124 (Bat (None, 16, 16, 96)        384       
_________________________________________________________________
dropout_95 (Dropout)         (None, 16, 16, 96)        0         
_________________________________________________________________
separable_conv2d_140 (Separa (None, 14, 14, 96)        10176     
_________________________________________________________________
activation_149 (Activation)  (None, 14, 14, 96)        0         
_________________________________________________________________
batch_normalization_125 (Bat (None, 14, 14, 96)        384       
_________________________________________________________________
dropout_96 (Dropout)         (None, 14, 14, 96)        0         
_________________________________________________________________
max_pooling2d_36 (MaxPooling (None, 7, 7, 96)          0         
_________________________________________________________________
separable_conv2d_141 (Separa (None, 7, 7, 96)          10176     
_________________________________________________________________
activation_150 (Activation)  (None, 7, 7, 96)          0         
_________________________________________________________________
batch_normalization_126 (Bat (None, 7, 7, 96)          384       
_________________________________________________________________
dropout_97 (Dropout)         (None, 7, 7, 96)          0         
_________________________________________________________________
separable_conv2d_142 (Separa (None, 7, 7, 96)          10176     
_________________________________________________________________
activation_151 (Activation)  (None, 7, 7, 96)          0         
_________________________________________________________________
batch_normalization_127 (Bat (None, 7, 7, 96)          384       
_________________________________________________________________
dropout_98 (Dropout)         (None, 7, 7, 96)          0         
_________________________________________________________________
separable_conv2d_143 (Separa (None, 5, 5, 96)          10176     
_________________________________________________________________
activation_152 (Activation)  (None, 5, 5, 96)          0         
_________________________________________________________________
batch_normalization_128 (Bat (None, 5, 5, 96)          384       
_________________________________________________________________
separable_conv2d_144 (Separa (None, 3, 3, 96)          10176     
_________________________________________________________________
activation_153 (Activation)  (None, 3, 3, 96)          0         
_________________________________________________________________
batch_normalization_129 (Bat (None, 3, 3, 96)          384       
_________________________________________________________________
separable_conv2d_145 (Separa (None, 1, 1, 10)          1834      
_________________________________________________________________
flatten_11 (Flatten)         (None, 10)                0         
_________________________________________________________________
activation_154 (Activation)  (None, 10)                0         
=================================================================
Total params: 66,517
Trainable params: 65,077
Non-trainable params: 1,440
_________________________________________________________________
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:51: UserWarning: Update your 'SeparableConv2D' call to the Keras 2 API: 'SeparableConv2D(96, (3, 3))'

## Your 50 epoch logs 

/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:11: UserWarning: The semantics of the Keras 2 argument `steps_per_epoch` is not the same as the Keras 1 argument `samples_per_epoch`. `steps_per_epoch` is the number of batches to draw from the generator at each epoch. Basically steps_per_epoch = samples_per_epoch/batch_size. Similarly `nb_val_samples`->`validation_steps` and `val_samples`->`steps` arguments have changed. Update your method calls accordingly.
  This is added back by InteractiveShellApp.init_path()
/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:11: UserWarning: Update your `fit_generator` call to the Keras 2 API: `fit_generator(<keras_pre..., validation_data=(array([[[..., verbose=1, steps_per_epoch=390, epochs=50)`
  This is added back by InteractiveShellApp.init_path()
Epoch 1/50
390/390 [==============================] - 40s 102ms/step - loss: 1.5199 - acc: 0.4425 - val_loss: 1.5195 - val_acc: 0.4910
Epoch 2/50
390/390 [==============================] - 32s 83ms/step - loss: 1.0869 - acc: 0.6084 - val_loss: 1.0831 - val_acc: 0.6301
Epoch 3/50
390/390 [==============================] - 32s 83ms/step - loss: 0.9342 - acc: 0.6683 - val_loss: 0.8800 - val_acc: 0.6950
Epoch 4/50
390/390 [==============================] - 32s 83ms/step - loss: 0.8352 - acc: 0.7026 - val_loss: 1.0302 - val_acc: 0.6483
Epoch 5/50
390/390 [==============================] - 32s 82ms/step - loss: 0.7623 - acc: 0.7305 - val_loss: 0.9213 - val_acc: 0.6864
Epoch 6/50
390/390 [==============================] - 32s 82ms/step - loss: 0.7090 - acc: 0.7506 - val_loss: 0.8032 - val_acc: 0.7289
Epoch 7/50
390/390 [==============================] - 32s 82ms/step - loss: 0.6660 - acc: 0.7656 - val_loss: 0.7367 - val_acc: 0.7460
Epoch 8/50
390/390 [==============================] - 32s 82ms/step - loss: 0.6324 - acc: 0.7764 - val_loss: 0.7149 - val_acc: 0.7624
Epoch 9/50
390/390 [==============================] - 32s 83ms/step - loss: 0.5999 - acc: 0.7890 - val_loss: 0.8244 - val_acc: 0.7264
Epoch 10/50
390/390 [==============================] - 32s 82ms/step - loss: 0.5764 - acc: 0.7980 - val_loss: 0.6944 - val_acc: 0.7674
Epoch 11/50
390/390 [==============================] - 32s 83ms/step - loss: 0.5527 - acc: 0.8058 - val_loss: 0.6913 - val_acc: 0.7675
Epoch 12/50
390/390 [==============================] - 32s 82ms/step - loss: 0.5315 - acc: 0.8122 - val_loss: 0.8153 - val_acc: 0.7383
Epoch 13/50
390/390 [==============================] - 32s 82ms/step - loss: 0.5158 - acc: 0.8175 - val_loss: 0.6582 - val_acc: 0.7808
Epoch 14/50
390/390 [==============================] - 32s 82ms/step - loss: 0.5011 - acc: 0.8243 - val_loss: 0.6683 - val_acc: 0.7789
Epoch 15/50
390/390 [==============================] - 32s 83ms/step - loss: 0.4852 - acc: 0.8301 - val_loss: 0.6260 - val_acc: 0.7925
Epoch 16/50
390/390 [==============================] - 32s 82ms/step - loss: 0.4680 - acc: 0.8356 - val_loss: 0.6374 - val_acc: 0.7819
Epoch 17/50
390/390 [==============================] - 32s 83ms/step - loss: 0.4574 - acc: 0.8386 - val_loss: 0.5714 - val_acc: 0.8104
Epoch 18/50
390/390 [==============================] - 32s 82ms/step - loss: 0.4513 - acc: 0.8389 - val_loss: 0.6039 - val_acc: 0.7963
Epoch 19/50
390/390 [==============================] - 32s 83ms/step - loss: 0.4371 - acc: 0.8471 - val_loss: 0.6399 - val_acc: 0.7889
Epoch 20/50
390/390 [==============================] - 32s 82ms/step - loss: 0.4244 - acc: 0.8520 - val_loss: 0.5999 - val_acc: 0.8005
Epoch 21/50
390/390 [==============================] - 32s 83ms/step - loss: 0.4147 - acc: 0.8531 - val_loss: 0.5673 - val_acc: 0.8135
Epoch 22/50
390/390 [==============================] - 32s 83ms/step - loss: 0.4058 - acc: 0.8555 - val_loss: 0.5930 - val_acc: 0.8035
Epoch 23/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3978 - acc: 0.8586 - val_loss: 0.5922 - val_acc: 0.8023
Epoch 24/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3921 - acc: 0.8618 - val_loss: 0.5967 - val_acc: 0.8079
Epoch 25/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3812 - acc: 0.8641 - val_loss: 0.5823 - val_acc: 0.8118
Epoch 26/50
390/390 [==============================] - 32s 82ms/step - loss: 0.3766 - acc: 0.8661 - val_loss: 0.5741 - val_acc: 0.8172
Epoch 27/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3743 - acc: 0.8677 - val_loss: 0.6625 - val_acc: 0.7912
Epoch 28/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3609 - acc: 0.8716 - val_loss: 0.5933 - val_acc: 0.8112
Epoch 29/50
390/390 [==============================] - 32s 82ms/step - loss: 0.3611 - acc: 0.8723 - val_loss: 0.6137 - val_acc: 0.8075
Epoch 30/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3541 - acc: 0.8740 - val_loss: 0.5661 - val_acc: 0.8158
Epoch 31/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3514 - acc: 0.8759 - val_loss: 0.5884 - val_acc: 0.8116
Epoch 32/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3425 - acc: 0.8780 - val_loss: 0.6377 - val_acc: 0.7981
Epoch 33/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3366 - acc: 0.8784 - val_loss: 0.5658 - val_acc: 0.8227
Epoch 34/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3356 - acc: 0.8801 - val_loss: 0.5946 - val_acc: 0.8124
Epoch 35/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3262 - acc: 0.8832 - val_loss: 0.5686 - val_acc: 0.8200
Epoch 36/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3223 - acc: 0.8850 - val_loss: 0.5773 - val_acc: 0.8183
Epoch 37/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3174 - acc: 0.8870 - val_loss: 0.6391 - val_acc: 0.8028
Epoch 38/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3155 - acc: 0.8869 - val_loss: 0.5788 - val_acc: 0.8191
Epoch 39/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3109 - acc: 0.8903 - val_loss: 0.6011 - val_acc: 0.8147
Epoch 40/50
390/390 [==============================] - 32s 82ms/step - loss: 0.3039 - acc: 0.8906 - val_loss: 0.6007 - val_acc: 0.8171
Epoch 41/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3088 - acc: 0.8902 - val_loss: 0.5939 - val_acc: 0.8177
Epoch 42/50
390/390 [==============================] - 32s 82ms/step - loss: 0.2991 - acc: 0.8928 - val_loss: 0.5647 - val_acc: 0.8273
Epoch 43/50
390/390 [==============================] - 32s 83ms/step - loss: 0.3005 - acc: 0.8933 - val_loss: 0.5636 - val_acc: 0.8256
Epoch 44/50
390/390 [==============================] - 32s 83ms/step - loss: 0.2930 - acc: 0.8949 - val_loss: 0.5941 - val_acc: 0.8202
Epoch 45/50
390/390 [==============================] - 32s 82ms/step - loss: 0.2878 - acc: 0.8969 - val_loss: 0.5801 - val_acc: 0.8240
Epoch 46/50
390/390 [==============================] - 32s 83ms/step - loss: 0.2896 - acc: 0.8957 - val_loss: 0.6479 - val_acc: 0.8062
Epoch 47/50
390/390 [==============================] - 32s 82ms/step - loss: 0.2855 - acc: 0.8964 - val_loss: 0.6055 - val_acc: 0.8114
Epoch 48/50
390/390 [==============================] - 32s 83ms/step - loss: 0.2798 - acc: 0.8988 - val_loss: 0.6013 - val_acc: 0.8224
Epoch 49/50
390/390 [==============================] - 32s 83ms/step - loss: 0.2802 - acc: 0.8995 - val_loss: 0.5761 - val_acc: 0.8252
Epoch 50/50
390/390 [==============================] - 32s 83ms/step - loss: 0.2773 - acc: 0.9007 - val_loss: 0.6036 - val_acc: 0.8235
Model took 1620.04 seconds to train

Accuracy on test data is 82.35
