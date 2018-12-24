### Robotic club ElHamma training
### December 2018

Big lines:
- Computer vision 
- Deep learning

Steps
  - Get basics of python, jupyter and math matrix 
  - Create and apply filters to image
  - work with opencv and numpy [OpenCv](https://opencv.org/) and [Numpy](http://www.numpy.org/)
  - Street line detection using opencv
  - Random forest segmentation 
  - Deep learning smile detection 

### Installation

The training requires conda installed [conda](https://conda.io/docs/)  to run.
installation:
- for [windows](https://conda.io/docs/user-guide/install/windows.html) 
- for [mac](https://conda.io/docs/user-guide/install/macos.html)
Then install the dependencies to new environment called "elhamma1" using [conda_env1.txt](conda_env1.txt) 

```sh
$ conda create --name elhamma1 --file conda_env1.txt 
```
Activate environment:

```sh
$ conda activate elhamma1 
```

Run jupyter notebook:

```sh
$ jupyter notebook
```

install tensorflow
```sh
$ https://github.com/antoniosehk/keras-tensorflow-windows-installation
```

Step 1:- conda search python

Step 2:- conda install python=3.5.2

Step 3:- pip install tensorflow

Step 4:- import tensorflow as tf