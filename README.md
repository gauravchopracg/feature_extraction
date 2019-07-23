# feature_extraction
the improvements gained by using features that are computed from the raw pixels than as opposed to using raw pixel values.


Overview
============

For each image we will compute a Histogram of Oriented Gradients (HOG) as well as a color histogram using the hue channel in HSV color space. We form our final feature vector for each image by concatenating the HOG and color histogram feature vectors; then, we will train a neural network on image features. This approach should outperform all previous approaches: you should easily be able to achieve over 55% classification accuracy on the test set; our best model achieves about 60% classification accuracy

Dependencies
============

* Numpy 
* matplotlib
* scipy 
### Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies


Usage
===========

To check the implementation of code, just open features.ipynb and run the all the cells


Credits
===========

This is a part of Assignment #1 of [CS231n](http://cs231n.github.io/)
