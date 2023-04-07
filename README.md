# CA05: Movie Recommendation
This Colab notebook, available at https://colab.research.google.com/drive/1V3Lj2JwY_y5bckvrApU0Z5-k4p3oYHZL#scrollTo=BXimBkwiWY9y, contains code for training a deep learning model on the Fashion-MNIST dataset.

# Dataset
The dataset was obtained using the following gitub link https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv

# Contents
The notebook contains the following sections:

Importing Required Libraries: In this section, we import the necessary Python libraries such as TensorFlow and NumPy.

Loading and Preprocessing Data: In this section, we load the Fashion-MNIST dataset and preprocess it by normalizing the pixel values and one-hot encoding the labels.

Defining the Model Architecture: In this section, we define the architecture of our deep learning model. The model consists of a stack of convolutional and pooling layers, followed by a dense layer and a softmax output layer.

Compiling and Training the Model: In this section, we compile our model by specifying the loss function, optimizer, and evaluation metrics. We then train our model on the training set, and evaluate its performance on the test set.

Visualizing Model Predictions: In this section, we use the trained model to make predictions on a few test images and visualize the results.
