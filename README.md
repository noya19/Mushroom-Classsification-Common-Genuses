# Mushroom-Classsification-Common-Genuses

The Project is aimed at building a Mushroom-Classifier from Scratch with the help of Transfer Learning.        
The Project Uses the [Mushrooms classification - Common genus's images](https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images/data) dataset to train the model.  
This dataset has a total of 6714 images distributed over 9 Categories.

## Project Aim
- To reach an accuracy over 90% over both the training set and validation set
- Visualize the Feature Maps of the Convolutional Layers

## Insights Learned
- Preprocessing data is a very important step, specially, emphasis should be given on the preparation of the validation set. It determines how the model will perform in training as well as validating. This also helps to prevent the model from overfitting in the training data.
- While adding your own layers at the top of the exsisting Model, adding batchnormalization is important, as it helps to identify important features from the data.
- After the Custom layers have trained on the New data, the model will be able to get a good prediction accuracy over a lot of test images, but the fine-Training process of transfer learning will ensure that the learned features are more specific to the current dataset.

## References:
- [Transfer Learning - Tensorflow tutorial](https://www.tensorflow.org/tutorials/images/transfer_learning)
- [Deep Shrooms - by Teemu Koivisto, Tuomo Nieminen, Jonas Harjunpää](https://tuomonieminen.github.io/deep-shrooms/)
- [Data Augmentation using keras and tensorflow](https://towardsdatascience.com/exploring-image-data-augmentation-with-keras-and-tensorflow-a8162d89b844)
