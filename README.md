# CNN_glasses_no_glasses

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

The purpose of this project is to create a `Machine Learning model` which will be able to `classify` different kind of images in two groups, `glasss` and `no glasses`. In this model it would be applied a pretrained model `MobileNet V2`, developed by google, and it will be applied `fine-tuning` with the weight of the pretrained model.

The model is based on `Tensorflow/Learn/Tutorials/Images/Transfer learning and fine-tuning` - https://www.tensorflow.org/tutorials¶

[![Kaggle](https://seeklogo.com/images/K/kaggle-logo-83322F52DE-seeklogo.com.png)](https://www.kaggle.com/jorgebuenoperez/computer-vision-application-of-cnn)

## Technical details about thje project:

 :round_pushpin: **Programming language:** `Python`

 :round_pushpin: **Library:** `Tensorflow`

 :round_pushpin: **Applied algorithm:** `Convolutional Neural Network`
 
## Data sources: 

- Main source: https://www.kaggle.com/jeffheaton/glasses-or-no-glasses
- Secondary source: 1 Million Fake Faces - 1 - https://www.kaggle.com/tunguz/1-million-fake-faces, from which I took 311 adittional photos belonging to the class no_glasses

## Some figures:

- Some images from the train sample:

![alt text](https://github.com/lajobu/CNN_glasses_no_glasses/blob/main/Figures/5.train_images.png)

- Example of data augmentation:

![alt text](https://github.com/lajobu/CNN_glasses_no_glasses/blob/main/Figures/6.augmen_images.png)

## Results:

- Application of fine tuning (after the green line):

![alt text](https://github.com/lajobu/CNN_glasses_no_glasses/blob/main/Figures/res_model_fine.jpg)
