# CNN-HandwrittenDigits
Recognize HandWritten Digits using Convolution Neural Network on TensorFlow

# DATASET USED  : MNIST (as .csv file available on Kaggle)

# What is CNN ?
 
  In machine learning, a convolutional neural network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural network that have successfully been applied to analyzing visual imagery.

CNNs use a variation of multilayer perceptrons designed to require minimal preprocessing.[1] They are also known as shift invariant or space invariant artificial neural networks (SIANN), based on their shared-weights architecture and translation invariance characteristics.

Convolutional networks were inspired by biological processes in which the connectivity pattern between neurons is inspired by the organization of the animal visual cortex.

# Convolution And Pooling :
   One of the best Articles : https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner%27s-Guide-To-Understanding-Convolutional-Neural-Networks/


# Sigmoid Function :
  A sigmoid function is a mathematical function having a characteristic "S"-shaped curve or sigmoid curve. Often, sigmoid function refers to the special case of the logistic function. 

# One-Hot Encoding :
   To One-Hot Encode 5 we create an array of 10 (Representing the digits from 0-9):
   0 0
   1 0
   2 0
   3 0
   4 0
   5 1
   6 0
   7 0
   8 0
   9 0


# SoftMax Function :
  Softmax regression (or multinomial logistic regression) is a generalization of logistic regression to the case where we want to handle multiple classes.
  Basically, it returns the probaility of matching to the output.
  # Note : It only calculates the probability of similarity not the error calculation.

# Cross Entropy : 
    Best Video for Understanding the same :   https://www.youtube.com/watch?v=tRsSi_sqXjI


# TENSORFLOW : 

###  Officialy : 

  TensorFlow™ is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent         mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The  flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. TensorFlow was originally developed by researchers and engineers working on the Google Brain Team within Google's Machine Intelligence research organization for the purposes of conducting machine learning and deep neural networks research, but the system is general enough to be applicable in a wide variety of other domains as well. 


###   What actually is Tensorflow and why is it so HYPED?:

  TensorFlow separates the definition of computations from their execution even further by having them happen in separate places: a graph defines the operations, but the operations only happen within a session. Graphs and sessions are created independently. A graph is like a blueprint, and a session is like a construction site.

### Further Info : https://www.oreilly.com/learning/hello-tensorflow

