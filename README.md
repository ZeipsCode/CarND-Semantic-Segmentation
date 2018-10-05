# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### GPU
`main.py` will check to make sure you are using GPU - if you don't have a GPU on your system, you can use AWS or another cloud computing platform.
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

##### Hyperparameters
- Adam optimizer is used with default parameters (learning_rate=0.001,
    beta1=0.9,
    beta2=0.999,
    epsilon=1e-08)

- Number of Epochs = 50
- Batch Size = 16



##### Inference result example

![alt text](https://github.com/dzeip87/CarND-Semantic-Segmentation/blob/master/inference_results/um_000006.png "Reasonably good example inference result")

![alt text](https://github.com/dzeip87/CarND-Semantic-Segmentation/blob/master/inference_results/um_000007.png "Reasonably good example inference result")

![alt text](https://github.com/dzeip87/CarND-Semantic-Segmentation/blob/master/inference_results/um_000070.png "Bad example inference result")
