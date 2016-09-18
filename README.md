# Cat-Dog Image Classifier

## **(Documentation in progress)

Check out the project on my [Github.io](https://mgallow.github.io/CatDog/)

## Introduction

**Disclaimer**: This tutorial is highly based off of Francois Chollet's blog post: <https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html>

In this tutorial we create a cat vs. dog image classifier using the python deep learning library Keras. Keras is a wrapper that works on top of Tensorflow or Theano. I have constructed the following using the Tensorflow backend - though the steps should be similar (if not, identical) should you choose to use the Theano backend.

![](https://github.com/MGallow/CatDog/raw/master/example.jpg)

### Why do we care?

Image classification (in a much broader sense than just cats vs. dogs) has wide implications in medical imaging (think fracture vs. non-fracture), facial recognition, image search (think Google search with photos), etc. Working through a toy example like this helps us to conceptualize the problem as well as familiarize one's self with the latest research.

## Requirements

This tutorial assumes basic knowledge of neural networks, specifically convolutional neural networks. Check out this excellent [blog post](http://cs231n.github.io/convolutional-networks/) on CNN's by [Andrej Karpathy](http://cs.stanford.edu/people/karpathy/) if needed. I would also recommend taking a look at this [tutorial](http://neuralnetworksanddeeplearning.com) by [Michael Nielsen](http://michaelnielsen.org) for a general overview of neural networks.

**Software**:

- Python 2.7, 3.5
- Keras - available via pip or [Github](https://github.com/fchollet/keras)

### Files:

- [train_classifier.py](https://github.com/MGallow/CatDog/blob/master/train_classifier.py)
- [pre-train_classifier.py](https://github.com/MGallow/CatDog/blob/master/pre-train_classifier.py)
- [fine-tune_classifier.py](https://github.com/MGallow/CatDog/blob/master/fine-tune_classifier.py)
- [MoveFiles.py](https://github.com/MGallow/CatDog/blob/master/MoveFiles.py)
- [evaluate_classifier.ipynb](https://github.com/MGallow/CatDog/blob/master/evaluate_classifier.ipynb)
- [fine-tune_classifier.ipynb](https://github.com/MGallow/CatDog/blob/master/fine-tune_classifier.ipynb)
- [pre-train_classifier.ipynb](https://github.com/MGallow/CatDog/blob/master/pre-train_classifier.ipynb)
- [train_classifier.ipynb](https://github.com/MGallow/CatDog/blob/master/train_classifier.ipynb)

This project utilizes a **"Locations.py"** script (not included) that specifies the locations of various files/repositories on the local machine. Thus, you may need to make slight adjustments to the files in order for them to run. Specifically, the following locations are defined (among others potentially):

- **train_data_dir** = _file path to training data_
- **validation_data_dir** = _file path to validation data_
- **test_data_dir** = _file path to test data_
- **preview_dir** = _where to save the previewed images? (optional)_
- **runs_dir** = _file path to saved model weights_
- **arch_dir** = _file path to saved model architectures_
- **train_bottleneck** = _file path to generated training bottleneck features_
- **validation_bottleneck** = _file path to generated validation bottleneck features_
- **plot_dir** = _file path to saved plots_

## Bottleneck Features

## Fine-Tuning

## Acknowledgements

- Keras documentation: <https://keras.io>
- This tutorial is highly based off Francois Chollet's blog post: <https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html>
