# Deep Learning 

## Project: Generate TV Scripts using RNN

### By Vedavyas Kamath

### Goal/Aim
To design & build a RNN that will generate a new script for TV Series [Seinfield](https://en.wikipedia.org/wiki/Seinfeld) using scripts for the previous seasons.

### Dataset:
We are using the [Seinfeld Dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) which has scripts for episodes of the first 9 seasons which we will be using to train our RNN to generate a new ,"fake" TV script, based on patterns it recognizes in this training data. The data has been extracted and is present in the `data` folder. 

### Project Overview
This project has been completed under a single Jupyter notebook, the details for which are below:

**Notebook : dlnd_tv_script_generation.ipynb**
* Load in & explore the data.
* Prepare/pre-process the data for analysis (create lookup table & tokenize punctuation) and also perform unit tests to verify for correctness.
* Batch the data and create dataloader and finally build the network by defining inital weights, feed-forward and back-propagation behaviour.
* Define training and test functions to be finally called to train/evaluate the model accordingly and finally get the generated TV script as output


### Software Requirements
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pytorch](https://pytorch.org/)
- [Unittest](https://docs.python.org/2/library/unittest.html)
- [collections.Counter](https://docs.python.org/2/library/collections.html#collections.Counter)