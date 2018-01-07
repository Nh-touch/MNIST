MNIST Net Work Practice(TensorFlow)
===========

  I'm a Beginner of Machine Learning, this is my second project aimed to practice the Machine Leaning skills.

## Environment: Python3.6(64-bit) 
  Pls run the following command to install the requirements.  
  `pip3 install -r requirements.txt`
  
## Data:
  The MNIST Images Data Download From The Net.
  ```
  from tensorflow.examples.tutorials.mnist import input_data
  mnist = input_data.read_data_sets("/tmp/data", one_hot = True)
  ```
  
## Purpose:
  The purpose of this project is try to let the machine recognize the numbers written by hand.
  
## How to run:
   After **installed the requirements**, pls use the following command to run:  
   `py -3 mnist_train.py`  
   Which will start the training program, and save the models in the same dir. 
   
## Results:
   The accuracy of train_data and test_data is up to 99.4%, which means it is a very nice tool to recognize the human-written numbers.
   And as a program to understand and practice basic tensorflow deep learning skills. This
   project will be more than enough.  
   
## Contacts:
   If you are interested in this project, pls feel free to contact me, improve this project together. 

