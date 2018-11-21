# Image Recognition using Deep Convolutional Neural Network and Retraining Pretrained Models 	                                           
[comment]: # (*************************************************************************************************************************************)
##### Domain             : Computer Vision, Machine Learning
##### Sub-Domain         : Deep Learning, Image Recognition
##### Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
##### Application        : Image Recognition, Image Classification
*************************************************************************************************************************************
### Description
1. Developed image recognition tool using Deep Convolutional Neural Network built from scratch with Keras Sequential model and, pretrained model “Inception” separately for fine-tuning with new class labels.
2. Trained on multiple datasets - Flower dataset (testing accuracy - 85.68%, 5 species, 4327 images, 228 MB), 10 Monkey species (validation accuracy – 97.06%, 553MB), Dog Breed dataset (Testing accuracy - 76.41%, 120 class, 10222 images, 344MB).
*************************************************************************************************************************************
### Flower Dataset:
###### Number of Class: 5
###### Number of Images: Total: 4327, Training: 3031, Validation: 866, Testing: 430
###### Dataset Size: Total: 228 MB, Training: 158 MB, Validation: 51.8 MB, Testing: 26.6 MB
###### Base Model: InceptionV3
###### Optimizers: Adam
###### Loss Function: categorical_crossentropy
<!---
###### Number of Epochs: 8
###### Training Time (Approx.): 2 Hours
-->
###### Metrics (Accuracy): Validation: 82%, Testing: 85.68%
###### Metrics (Loss): Testing: 1.29

#### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Flowers%20Recognition/demo/sample/sample.png>
</kbd>

*************************************************************************************************************************************

### Monkey Dataset:
###### Number of Class: 10
###### Number of Image: Total: 1370, Training: 1098, Validation: 272, Testing: 0
###### Dataset Size: Total: 553 MB, Training: 434 MB, Validation: 119 MB, Testing: 0 MB
###### Base Model: InceptionV3
###### Optimizers: Adam
###### Loss Function: categorical_crossentropy
<!---
###### Number of Epochs: 43
###### Training Time (Approx.): 2 Hours
-->
###### Metrics (Accuracy): Validation: 97.06%
<!---
##### Metrics (Loss): Testing: 1.29
-->

#### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Monkey%20Recognition/demo/sample/sample.png>
</kbd>

*************************************************************************************************************************************

### Dog Dataset:
###### Number of Class: 120
###### Number of Image: Total: 10222, Training: 7221, Validation: 2043, Testing: 958
###### Dataset Size: Total: 344 MB, Training: 239 MB, Validation: 71.1 MB, Testing: 34.3 MB
###### Base Model: InceptionV3
###### Optimizers: Adam
###### Loss Function: categorical_crossentropy
###### Number of Epochs: 29
###### Training Time (Approx.): 23.63 Hours
###### Metrics (Accuracy): Validation: 76.41%
<!---
#### Metrics (Loss): 
-->
#### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Dog%20Breed%20Identification/demo/sample/sample2.png>
</kbd>

*************************************************************************************************************************************
##### Languages   : Python
##### Tools/IDE   : Anaconda
##### Libraries   : Keras, TensorFlow, Inception, ImageNet
*************************************************************************************************************************************
##### Duration   : September 18 - Current
##### Current Version  : v1.0.0.0
##### Last Update      : 11.09.2018
*************************************************************************************************************************************
