# Image-classification-with-CNN-Tensorflow
Training a CNN to classify dog and cat images using Tensorflow and Keras
Done as part of guided project on Coursera. View my verified certifict here


##ImageDataGenerator(rescale = 1./255,shear_range = 0.2,zoom_range = 0.2, horizontal_flip = True)
Used to create variations of images in training by adding zoom, roation along axis, shear and rescaling. This is done in order to ensure that model does not overfit the training data (reduce variance).

