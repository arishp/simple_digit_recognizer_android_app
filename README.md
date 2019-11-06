# simple_digit_recognizer_android_app
This repository contains code snippets required to develop a simple MNIST digit recognizer android app.  The app takes an image of a digit, 0 to 9, and forms a prediction based on the model that is provided. This project is based on simple linear regression. Image is loaded in an image view which is being converted into numeric array for prediction. This model predicts two choices, first choice and second choice in a text view. This repository has two main sections.  The first is going to be the python files and the second section deals with android development code. Initially a the tensorflow based linear regression model is built using simple computational graph,  then it is trained and tested in Python.  The computational graph is frozen into the optimized version for Android input. This is the end of python code. Now the necessary file are imported and the android app is built around this model.
