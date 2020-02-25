# Introduction
This poject, which is based on python, compiling on PyCharm, is to recognize the user's handwritten digit. Combining with regressional and convolutional function, the user just need to open the main function and the project will run. Linking to HTML file, there is a canvas which user can use mouse to draw.

User can draw the digit whatever they like in the canvas. Before it user can run the regressional and convolutional functions to test the accuracy. After drawing the digit, the browser will response automatically and give you the probability with regression and convolution.User can also press `clear` button to clear their drawing if they are not satisified with it. The feedback is instant and couldn't be saved

# Required parts
## Pyhton
Python is a cross platform computer programming language. It is an object-oriented dynamic type language, which was originally designed to write automation scripts (shells). With the continuous update of versions and the addition of new language functions, it is more and more used in the development of independent and large-scale projects. Pyhton's version had better 3.5, fitting to anaconda.

## Anaconda
Anaconda refers to an open-source Python distribution, which contains more than 180 science packages such as Conda and Python and their dependencies. Because of containing a large number of science packages, Anaconda has a large download file. If you only need some packages, or need to save bandwidth or storage space, you can also use miniconda, a smaller distribution(only including Conda and python)

## Tensorflow
TensorFlow is a symbolic mathematics system based on data flow programming, which is widely used in the programming of various machine learning algorithms. Its predecessor is Distbelief, a neural network algorithm library of Google.

# Precess
## 1.Build environment
If you have installed Python3.5. This part can be ignored. If not, if your python's version is 3.8, run the command `conda create -n myenv python=3.6`. You can replace `myenv` with the environment name by yourself.

## 2.Download ZIP from github
Download and decompress the file. Open it by a python IDE such as Jupyter or Pycharm.

## 3.Choose python interpreter
Select the python with anaconda, which has plenty of modules.

## 4.Test the accuracy
Run `regression` and `convolutional`. Both of them will give you the accuracy a little while.

## 5.Start to run
Run `main` function and wait for the port appearing. Then click the port and open it in the browser.

## 6.Draw the digit
Use your mouse to draw a digit in the canvas.

# Demo
![Demo](https://github.com/a912851371/HANDWRITING-RECOGNITION-PROJECT/blob/master/Demo.gif)
