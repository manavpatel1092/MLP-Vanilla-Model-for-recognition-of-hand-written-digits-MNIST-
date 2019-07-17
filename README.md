# MLP for recognition of hand written digits (MNIST)

Overview of Dataset:

MNIST dataset consists of handwritten digits used for training image processing systems.It has a training set of 60,000 examples, and a test set of 10,000 examples. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

The MNIST dataset can be downloaded using the following URL http://yann.lecun.com/exdb/mnist/ 
. The MNIST dataset is also available in Keras module in Python and can be accessed by running the following code directly into the notebook:
```
import keras
from keras.datasets import mnist
```
Task:

- Two “vanilla” models (Multilayer Perceptron) were built using Keras sequential interface with and without drop-out regularization, to compare the differences. 
- GridSearchCV was used to tune the parameters of the models. 
- Both models have the same accuracy measures but the loss was significantly lower for the model with no dropout regularization.
