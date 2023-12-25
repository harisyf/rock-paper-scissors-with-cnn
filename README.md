# Rock, Paper, and Scissors Image Classification Using CNN TensorFlow and Hyperparameter Tuning
A project for my submission of my learning in Dicoding about machine learning to classify image of rock, paper, and scissors with Convolutional Neural Network (CNN). To build the model, we will use Python with TensorFlow and Keras. I also applied hyperparameter tuning to help find the optimal model using Keras-Tuner. I use Google Colab notebook to run my code, so I recommend to use Google Colab if you want to try my code.

The dataset that I used for this project is [this dataset](https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors) from Kaggle. The dataset is large so it can not be uploaded to GitHub so I suggest you to download the dataset if you want to run it locally or download directly from Google Colab.

# Requirements
Library that I used for this project are below.
* TensorFlow
* Keras
* Keras-Tuner
* Matplotlib
* Numpy
* Google.Colab (To upload images for testing the model)
* Time (To calculate training time)
Note: In order to speed up your training process you will need to use the GPU since using CPU only will likely to take a long time.

# Project Structure
There are several steps in this project as stated below:
* Library Preparation
  
  In this step, we will prepare the necessary libraries and packages.
* Dataset Preparation
  
  We download and extract dataset in this step.
* Data Preprocessing
  
  After we extract the dataset, next we will do data preprocessing such as image augmentation and traing and validation data split.
* CNN Modelling
  
  The next step is building the CNN model. I use hyperparameter tuning to help find the best parameter so we can get the optimal model. Parameters that we will search are number of layers, neuron units, kernel size, and optimizer function.
* Model Re-Training

  After model building then we do the training. (Make sure to use GPU, if not it will take a long time)
* Model Evaluation

  We can visualize the accuracy and loss from our model training using line plot with matplotlib library.
* Model Testing

  Last, we will do testing on our trained model with any rock, paper, and scissors image(s) that you can upload to Google Colab. (This is why I suggest use Google Colab) 

You may check my notebook for the detail of every steps.

# Conclusion
That was it, the Image Classification Project of Rock, Paper, Scissors has been completed. We achieved 96% accuracy, which is pretty high. We also succesfully implemented hyper parameter tuning. Hyperparameter Tuning proves beneficial if we are uncertain regarding the selection of parameters and optimal number of layers for our model. While this may help to do 'semi-automation' in the search for the best configuration. However, it is important to note that hyperparameter tuning can be computationally expensive. As you can see, it takes quite a lot of resources for searching the best parameter and re-training so it might takes some consideration to use this. A high performance PC is recommended due it will take high computational resources to train with images dataset.

The model performance is quite good in detecting images with green background but it fails to detect images with different background so it may need another dataset to improve the accuracy for unseen data. Thank you for visiting my page if you have any further discussion or suggestion you may contact me! (A star would be very appreciated!)
