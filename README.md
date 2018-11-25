# Image Recognition using Deep Convolutional Neural Network and Retraining Pretrained Models 	                                           
[comment]: # (*************************************************************************************************************************************)
##### Domain             : Computer Vision, Machine Learning
##### Sub-Domain         : Deep Learning, Image Recognition
##### Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
##### Application        : Image Recognition, Image Classification
*************************************************************************************************************************************
### Description
1. Developed image recognition tool using Deep Convolutional Neural Network built from scratch with Keras Sequential model and, pretrained model “Inception” separately for fine-tuning with new class labels.
2. Trained on multiple datasets - Flower dataset (testing accuracy - 90.38%, 5 species, 4327 images, 228 MB), 10 Monkey species (validation accuracy – 97.06%, 553MB), Dog Breed dataset (Testing accuracy - 76.41%, 120 class, 10222 images, 344MB).
*************************************************************************************************************************************
### Flower Dataset:

<pre>
<b>Dataset Details</b>
Dataset Name            : Flower Dataset
Number of Class         : 5
Number/Size of Images   : Total      : 4327 (228 Megabyte (MB))
                          Training   : 3031 (158 Megabyte (MB))
                          Validation : 866  (51.8 Megabyte (MB))
                          Testing    : 430  (26.6 Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 50
Training Time           : 40 min

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Validation</b>
Accuracy                : 82%

<b>Testing</b>
Accuracy                : 90.38%
Loss                    : 0.48
<!--Precision               : 
Recall                  : 94% (highest)
Specificity             : -->
</pre>

<!--
Best Model Path (Accuracy): data\output\models\\42-val_acc-0.86-val_loss-0.82.hdf5
Best Test Accuracy: 89.91%
Best Test Loss: 0.49
Best Model Path (Loss): data\output\models\\12-val_acc-0.84-val_loss-0.65.hdf5
Best Test Accuracy: 89.44%
Best Test Loss: 0.48
-->

##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Flowers%20Recognition/demo/sample/sample.png>
</kbd>

*************************************************************************************************************************************

### Monkey Dataset:
<pre>
Dataset Name     : 10 Monkey Species
Dataset Link     : <a href=https://www.kaggle.com/slothkong/10-monkey-species>10 Monkey Speciesy</a>
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Monkey Dataset
Number of Class         : 10
Number/Size of Images   : Total      : 1370 (553 Megabyte (MB))
                          Training   : 1098 (434 Megabyte (MB))
                          Validation : 272  (119 Megabyte (MB))
                          Testing    : 0    (0   Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 50
Training Time           : 40 min

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Validation</b>
Accuracy                : 97.0%
Loss                    : 0.11

<!--
<b>Testing</b>
Accuracy                : 
Loss                    : 
Precision               : 
Recall                  : 
Specificity             : -->
</pre>

<!--
Best Model Path (Accuracy): 27-val_acc-0.97-val_loss-0.11.hdf5
Best Test Accuracy: 97.0%
Best Test Loss: 0.11
-->
##### Sample Output: 
<kbd>
<img src=https://github.com/anjanatiha/Image-Recognition-using-Deep-Convolutional-Neural-Network/blob/master/Monkey%20Recognition/demo/sample/sample.png>
</kbd>
<!---
-->
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
##### Sample Output: 
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
##### Last Update      : 11.20.2018
*************************************************************************************************************************************
