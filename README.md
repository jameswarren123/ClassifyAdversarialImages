# ClassifyAdversarialImages
A Python application which takes the MNIST dataset and generates a series of adversarial examples against Convolutional Neural Network identifier with 4 different algorithms, Random Noise, Fast Gradient Sign Method, Carlini and Wagner Method, and Deepfool, with both targeted and untargeted methods. Then taking unused images from the MNIST dataset and our adversarial images we create two datasets. A binary dataset which only tags whether an image is perturbed or not, and a multiclass one which record whether an image is unperturbed or altered through one of the 8 methods. We then analyze the efficacy of the different algorithms and identification methods by training 4 different model types, linear regression, kmeans, random forest, and CNN, and compare their accuracy and confusion matrices to make our analyses.
## Features
- Project start up with new or previously generated images to save time.
- Intuative model imaging through MatPlotLib.
- Image output to show the difference in image generation accross the algorithms.
- View of each model to improve understanding.
## Technologies Used
- Python
- Numpy
- Pandas
- MatPlotLib
- TensorFlor
- PyTorch
## Setup
Download the ipynb file hear and upload it to google colab.
