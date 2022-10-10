# Image-classification-with-CNN-Tensorflow
Training a CNN to classify dog and cat images using Tensorflow and Keras
Done as part of guided project on Coursera. View my verified certifict here


1. ImageDataGenerator(rescale = 1./255,shear_range = 0.2,zoom_range = 0.2, horizontal_flip = True)
Used to create variations of images in training by adding zoom, roation along axis, shear and rescaling. This is done in order to ensure that model does not overfit the training data (reduce variance).

2. cnn.compile(optimizer =adam' , loss = 'binary_crossentropy', metrics = ['accuracy'])

Loss is binary cross entropy as it is a binary classification problem
For more details on binary cross entropy and compatible loss functions, visit https://peltarion.com/knowledge-center/modeling-view/build-an-ai-model/loss-functions/binary-crossentropy


Adam optimiser- chooses a per parameter learning rate to ensure that rate of gradient descent is in such a way that ensures that it bypasses local minimas in lesser steps while reducing osciallations while it reaches global minima. 
https://www.geeksforgeeks.org/intuition-of-adam-optimizer/
