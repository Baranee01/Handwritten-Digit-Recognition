# Handwritten Digit Recognition using CNN

### INSTALLATION

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Keras](https://keras.io/)
- [matplotlib](http://matplotlib.org/)
- [tensorflow](https://www.tensorflow.org/)
- [seaborn](http://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/index.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

##
### EXECUTION

In a terminal or command window, navigate to the top-level project directory `HandwrittenDigitRecognition/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook MNIST_CNN.ipynb
```
or
```bash
ipython notebook MNIST_CNN.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser. You can also use Google Colab for easy access as it already has all the packages installed.


##
### ABOUT THE DATASET
• It is an inbuilt dataset from keras.

• The training part of the datas contains 60000 datas with 28 * 28 each.

• The testing part of the datas contains 10000 datas with 28 * 28 each.

• The 28 * 28 matrix of each data represents the pixel's color values of each data.

##
### SAMPLE DATASET

![MNIST Dataset](https://user-images.githubusercontent.com/59074144/117337012-7da44600-aeba-11eb-9cf6-e2d535d579f7.png)

##
### FLOW OF THE PROJECT

Program has been separated into two divisions:
- Classifying the MNIST dataset.
- Recognising the digit.

##
### NOTE: USE ONLY GRAYSCALE IMAGE FOR RECOGNITION.
