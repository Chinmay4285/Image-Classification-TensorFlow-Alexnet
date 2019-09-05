# TensorFlow-Image-Classification-using-Alexnet-s
This is a multiclass image classification project using Convolutional Neural Networks and TensorFlow API (no Keras) on Python.
I got this file as part of keras project and used some open source code from some github user(mubuyuk51). I trained model with 10 epochs and you can see the results below. I used Intel AI cloud to train my model and to achieve above mentioned results. Please check it if you are interested.


It is a ready-to-run code.

# Dependencies

```pip3 install -r requirements.txt```

# Training

Training on CPU:

```python3 multiclass_classification.py ```

# Notebook

```jupyter lab  Multiclass_classification.ipynb``` or ```jupyter notebook Multiclass_classification.ipynb ```

# Data
No MNIST or CIFAR-10. 

This is a repository containing datasets of 5200 training images of 4 classes and 1267 testing images.No problematic image.

Just extract files from multiclass_datasets.rar.

train_data_bi.npy is containing 5200 training photos with labels.

test_data_bi.npy is containing 1267 testing photos with labels.

Classes are chair & kitchen & knife & saucepan. Classes are equal(1300 glass - 1300 kitchen - 1300 knife- 1300 saucepan) on training data. 

Download pure data from [here](https://www.kaggle.com/mbkinaci/chair-kitchen-knife-saucepan). Warning 962 MB.

# Architecture

AlexNet is used as architecture. 5 convolution layers and 3 Fully Connected Layers with 0.5 Dropout Ratio. 60 million Parameters.
![alt text](https://github.com/MuhammedBuyukkinaci/TensorFlow-Image-Classification-Convolutional-Neural-Networks/blob/master/alexnet_architecture.png) 

# Results
Accuracy score reached 87% on CV after just 5 epochs.
![alt text](https://github.com/MuhammedBuyukkinaci/TensorFlow-Multiclass-Image-Classification-using-CNN-s/blob/master/mc_results.png)

# Predictions
Predictions for first 64 testing images are below. Titles are  the predictions of our Model.

![alt text](https://github.com/MuhammedBuyukkinaci/TensorFlow-Multiclass-Image-Classification-using-CNN-s/blob/master/mc_preds.png)
