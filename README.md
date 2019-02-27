Deep Learning
======
This includes my notes for studying deep learning course from deeplearning.ai and other sources. Notes and codes will be uploaded bit by bit as I learn through the course. 

lesson 1: Neural Network and Deep Learning
------

The general methodology to build a Neural Network is to:

1. Define the neural network structure:
	- how many input/output units
 	- whether shallow or deep NN (i.e. # of hidden units)
 	- which activation functions, learning rates etc. to use
2. Initialize the model's parameters
3. Loop:
    - Implement forward propagation
    - Compute loss
    - Implement backward propagation to get the gradients
    - Update parameters using gradient descent
    
The following lessons notes will cover how I learn these steps:     
- 1.1 [Introduction to deep learning](https://github.com/Phoebe0222/deep-learning/blob/master/lesson1/Lesson1-1-Intro-to-Neural-Network.pdf)
- 1.2 [Neural networks basics](https://github.com/Phoebe0222/deep-learning/blob/master/lesson1/Lesson1-2-neural-network-basics.pdf) 
	
	([notes on Vectorization](https://colab.research.google.com/github/Phoebe0222/deep-learning/blob/master/lesson1/vectorization_and_Broadcasting.ipynb))
- 1.3 [Shallow neural networks](https://github.com/Phoebe0222/deep-learning/blob/master/lesson1/Lesson1-3-shallow-neural-network.pdf)
- 1.4 [Deep neural networks](https://github.com/Phoebe0222/deep-learning/blob/master/lesson1/Lesson1-4-deep-neural-network.pdf) 
	
lesson 2: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization
------
We have covered the theoractical part of NN, but there are more practical concerns and ways to improve it when implementing it. The following lessons include methods of how to improve NNs:  
-  2.1 [Practical aspects of Deep Learning](https://github.com/Phoebe0222/deep-learning/blob/master/lesson2/Lesson2-1-practical-aspects-of-deep-learning.pdf)
-  2.2 [Optimization Algorithms](https://github.com/Phoebe0222/deep-learning/blob/master/lesson2/Lesson2-2-optimisation-algorithms.pdf)
-  2.3 [Hyperparameter tuning, Batch Normalization and Programming Frameworks](https://github.com/Phoebe0222/deep-learning/blob/master/lesson2/Lesson2-3-hyperparameters-tuning-batch-normalisation-and-programming-frameworks.pdf) 

	([notes on Tensorflow](https://github.com/Phoebe0222/deep-learning/blob/master/lesson2/Tensorflow.ipynb))


lesson 3: Structuring Machine Learning Projects
------
Here are some strategies that we could apply to out machine learning projects to improve performance and fasten the process. 

- 3 [machine learning strategies](https://github.com/Phoebe0222/deep-learning/blob/master/lesson3/Lesson3-structuring-machine-learning-projects.pdf)

lesson 4: Convolutional Neural Networks
------
In the earlier lesson of neural network for image recognition, we have used images with 64 by 64 pixel, which are actually very small images, but sometimes we want to process hige resolution pictures like 1000 by 1000 pixel. One of the challenges it presents is that the input could be very large. For example, for a 1000 by 1000 pixel image, if we flatten it, it would be a 3 million dimensional matrix. And this means that there are many parameters, which would be difficult to get enough data to prevent a neural network from overfitting. Therefore, we need convolutional neural network to do that.   
- 4.1 Foundations of Convolutional Neural Networks 
- 4.2 Deep Convolutional Models: case studies
- 4.3 Object Detection 
- 4.4 Special Applications: Face Recognition & Neural Style Transfer

lesson 5: Natural Language Processing: Building Sequence Models 
------ 


Note that these notes exclude all materials from assignments. 
 
