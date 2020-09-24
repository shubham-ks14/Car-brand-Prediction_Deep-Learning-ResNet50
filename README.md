# Car-brand-Prediction_Deep-Learning-ResNet50
Image-based Car brand prediction using Deep learning technique and ResNet-50 architecture

## Overview
* Demonstrating a method to use deep learning technique to classify  images of car brand by training the model with around 84 images.
* The classification was done on 3 different class of images available as follows:
1. Audi
2. Lamborghini
3. Mercedes

## Methods
### Dataset 
* 84 images for train data and 30 images for test data were used to reduce the computational cost.
* Images from train data of all 3 classes is provided the folder.
* Each of train and test contains images for above mentioned 3 classes.
* The default resizing of images of 224 x 224 pixels is used.
### Approach
* For the classification Deep CNN method with Transfer learning training mechanism is applied.
* ResNet50 deep learning architecture is used.

### Platform/IDE/Tools
* Google Colaboratory IDE with TPU hosted runtime server to allow fast computaion.
* Save the dataset in google drive first, mount the drive in Colab and then give correct path to directory where data is saved.
* Training time is close to 30 minutes.
* A model in jupyter notebook is also available but dosent provide good accuracy reason being less computaional power in local machine.

### Results
* Highest accuracy of 0.9167 for training set and 0.700 for test set is obtained.
* Final predicion of one image each from different class.
* 2 out of 3 predictions were correct matching the test accuracy.

## Future Scope
* Use of other Deep CNN architecture such as VGG16, AlexNet.
* Deployment in PAAS platforms such as Heroku or IAAS like AWS for a complete cotton disease prediction web app.

