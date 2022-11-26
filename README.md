# Parkinsons-Disease-prediction-by-Aman-Jain
Predictive Analytics project
Predictive Analytics  

Using Neural Network
Parkinsons Disease
November 26, 2022,
________________________________________


Made by 
Aman Jain 209301581
Data Analytics -B(CSE)
“You can have Data without information but you cannot have information without Data”
- Daniel Keys Moran
Introduction
Parkinson's disease is a progressive disorder that affects the nervous system and the parts of the body controlled by the nerves. Symptoms start slowly. The first symptom may be a barely noticeable tremor in just one hand. Tremors are common, but the disorder may also cause stiffness or slowing of movement.

Problem Statement
To build a neural network model to predict efficiently whether a person is suffering from Parkinson’s Disease based on the attributes given in the dataset collected from Kaggle.
Approach to Solution
To build a Machine learning model using Google Colaboratory which is an online platform for Machine Learning Development. The language used to build the model is Python3. We would be using technologies like TensorFlow, NumPy, seaborn, Keras, and matplotlib. We would be using Dataset imported from Kaggle which is a free, open-source platform containing a large variety of datasets to choose from.
About the technologies used
1.	TensorFlow: The TensorFlow platform helps you implement best practices for data automation, model tracking, performance monitoring, and model retraining. Using production-level tools to automate and track model training over the lifetime of a product, service, or business process is critical to success.
2.	Keras: Keras allows users to productize deep models on smartphones (iOS and Android), on the web, or on the Java Virtual Machine. It also allows the use of distributed training of deep-learning models on clusters of Graphics processing units (GPU) and tensor processing units (TPU). 
3.	Seaborn: Seaborn is an amazing visualization library for statistical graphics plotting in Python. It provides beautiful default styles and color palettes to make statistical plots more attractive. It is built on the top of the Matplotlib library and is also closely integrated into the data structures from pandas.
4.	NumPy & Pandas: NumPy stands for Numerical Python and it is a core scientific computing library in Python. It provides efficient multi-dimensional array objects and various operations to work with these array objects.						Pandas is an open-source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another package named Numpy, which provides support for multi-dimensional arrays	

Formal Definition:
	Initial State: Un-preprocessed and un-trained dataset.
	Final State: Trained and classified data set.
	Transition model: Neural Network using activation function like sigmoid(exponential) and ReLu (linear).
	Path Cost: weight required to trained the model.

PEAS:
1.)	Performance: training = 78.9% and  testing = 79.49%.
2.)	Environment: Online Python kernel and data set.
3.)	Actuator: Convulational Neural Network 
4.)	Sensor: Inputs taken from the data set.


Code Snippets
 
 

 
 

 

 




Output
Training and Testing Accuracy
 
Dataset
 
Data Pre-Process:
 
Confusion Matrix
 
ROC Curve
 
Conclusion
The model Neural Network model created using Python3, TensorFlow and Keras predict if the person is suffering from Parkinsons Disease or is at a potential risk of having progressive disorder that affects the nervous system and the parts of the body controlled by the nerves with an accuracy of 79.49%.
Thus, the model created in this project can be implemented for real-world applications and can be extended further by training a larger dataset and improving the accuracy of prediction using advanced methods of Deep Learning and Convolutional Neural Networks.
