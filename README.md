# Rock, Paper, and Scissors Image Classification Using CNN TensorFlow
Little project for my submission of my learning in Dicoding about machine learning to classify image of rock, paper, and scissors with Convolutional Neural Network (CNN). To build the model, we will be going to use Python with TensorFlow and Keras. I'm using Google Colab notebook to run my code, so we better to use Google Colab if you want to try my code.

The dataset that I used for this project is [this dataset](https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors) from Kaggle. The dataset is large so it can not be uploaded to GitHub so I suggest you to download the dataset if you want to run it locally or download directly from Google Colab.

# Requirements
Library that I used for this project are below.
* TensorFlow
* Keras
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
  
  The next step is building the CNN model. With Sequential model from TensorFlow and Keras, we determine the layers, number of neurons, activation function, loss function, and optimisation function.
* Model Training

  After model building then we do the training. (Make sure to use GPU, if not it will take a long time)
* Model Evaluation

  We can visualize the accuracy and loss from our model training using line plot with matplotlib library.
* Model Testing

  Last, we will do testing on our trained model with any rock, paper, and scissors image(s) that you can upload to Google Colab. (This is why I suggest use Google Colab) 

You may check my notebook for the detail of every steps.

# Conclusion
That was it, the Image Classification Project of Rock, Paper, Scissors has completed. We achieved 96% accuracy, which is pretty high. Our model also successfully detect the images correctly with the image we uploaded. Although, not every time the model will correctly predict the image but it's alright as we can always improve the model by adding new data or tune our model. Thank you for visiting my page if you have any further discussion or suggestion you may contact me! (A star would be very appreciated!)
