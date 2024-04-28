**Iris Flower Classification with TensorFlow**
This code demonstrates how to train a neural network model to classify iris flowers into three different species using TensorFlow. The model is trained on the Iris dataset.

**Requirements**
Python 3.x
TensorFlow
Pandas
**Installation**
To install the required dependencies, run:


pip install tensorflow pandas
Usage

git clone https://github.com/your_username/iris-classification.git
cd iris-classification

Run the Python script:

python iris_classification.py

**Description**
Dataset
The Iris dataset consists of 150 samples of iris flowers, each with four features (sepal length, sepal width, petal length, and petal width) and a label specifying the species of iris.

**Script**
Import necessary libraries and set up logging.
Load the Iris dataset using TensorFlow's tf.keras.utils.get_file function and Pandas.
Define input function to convert inputs to a dataset.
Define feature columns for the DNNClassifier.
Build a DNNClassifier model with two hidden layers.
Train the classifier on the training data.
Evaluate the model on the testing data.
Define input function for prediction.
Prompt user for numeric input values for prediction features.
Make predictions using the trained classifier.
**Results:**
The script outputs the accuracy of the model on the test set and predicts the species of iris based on user input.
