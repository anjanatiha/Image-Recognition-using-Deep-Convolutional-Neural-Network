# Image Recognition using Deep Convolutional Neural Network and Retraining Pretrained Models 	                                           
[comment]: # (*************************************************************************************************************************************)
##### Domain             : Computer Vision, Machine Learning
##### Sub-Domain         : Deep Learning, Image Recognition
##### Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
*************************************************************************************************************************************
### Description
1. Developed image recognition tool using Deep Convolutional Neural Network built from scratch with Keras Sequential model and, pretrained model “Inception” separately for fine-tuning with new class labels.
2. Trained on multiple datasets - Flower dataset (testing accuracy - 85.68%, 5 species, 4327 images, 228 MB), 10 Monkey species (validation accuracy – 97.06%, 560MB), Dog Breed dataset (validation accuracy - 74.25%, 120 class, 22000 images, 680MB).
*************************************************************************************************************************************
### Training Details for Flower Dataset:
##### Number of Class: 5
##### Number of Images: Total: 4327, Training: 3031, Validation: 866, Testing: 430

##### Dataset Size: Total: 228 MB, Training: 158 MB, Validation: 51.8 MB, Testing: 26.6 MB
<!---
###### Number of Epochs: 8
###### Training Time (Approx.): 2 Hours
-->
##### Metrics (Accuracy):
<!---
###### Training:
-->
###### Validation: 82%
###### Testing: 85.68%

##### Metrics (Loss):
<!---
###### Training:
###### Validation:
-->
###### Testing: 1.29

### Training Details for Monkey Dataset:
##### Number of Class: 10
##### Number of Image: Total: 1370, Training: 1098, Validation: 272, Testing: 0

##### Dataset Size: Total: 553 MB, Training: 434 MB, Validation: 119 MB, Testing: 0 MB
<!---
###### Number of Epochs: 8
###### Training Time (Approx.): 2 Hours
-->
##### Metrics (Accuracy):
<!---
###### Training:
###### Testing:
-->
###### Validation: 97.06%
##### Metrics (Loss):
<!---
###### Training:
###### Validation:
###### Testing: 1.29
-->

### Training Details for Dog Dataset:
##### Number of Class: 120
##### Number of Image: Total: 10222, Training: 7221, Validation: 2043, Testing: 958

##### Dataset Size: Total: 344 MB, Training: 239 MB, Validation: 71.1 MB, Testing: 34.3 MB
<!---
###### Number of Epochs: 8
###### Training Time (Approx.): 2 Hours
-->
##### Metrics (Accuracy):
<!---
###### Training:
-->
###### Validation: 74.25%
<!---
###### Testing: 
#### Metrics (Loss):
###### Training:
###### Validation:
###### Testing: 1.29
-->
*************************************************************************************************************************************
##### Languages   : Python
##### Tools/IDE   : Anaconda
##### Libraries   : Keras, TensorFlow, Inception, ImageNet

##### Duration   : September 18 - Current
*************************************************************************************************************************************
Current Version  : v1.0.0.0
Last Update      : 11.09.2018
*************************************************************************************************************************************
