# DeepLearning BasicCNN HumanFace Recognition
This Repo shows the basic code for building a CNN layer from scratch, including basic code for convolution operation, kernels sliding windows, padding and pooling(downsampling). I trained on a two-class human face dataset using one layer CNN, with 8 kernels, and each kernel size is 3 by 3. The tuned model gives a good performance on test dataset.

## Getting Start
In the Simple_CNN.ipybn file, it shows how to code one layer CNN.

There are four important functions for a CNN layer: padding function, convolution function, pooling function, and sliding window function.

## The Standard way for ML

### First Step: Load data
In this experiment, I used ten thounsands of (28,28) human face dataset to train a classifier for HumanFace Recognition.

### Second step: Build model
One layer CNN(kernels:8,3,3), linear combination in my case.

### Third Step : Chose Cost function
softmax, this is a two-classification problem.

### Fourth Step: Training Algorithm
#### standrad gradient descent vs mini batch gradient descent
I used two version of gradient descent and make a comparison for training processing.

### Fifth Step: Training on train dataset and cross-validation on test dataset
#### The training result and cross-validation accuracy is shown below
<img width="1526" alt="simple_cnn_cost" src="https://user-images.githubusercontent.com/36088488/39958176-0e2dd1fc-55c5-11e8-98d9-79f7c4e6bd9b.png">


<img width="1384" alt="simple_cnn_accuracy" src="https://user-images.githubusercontent.com/36088488/39958174-0e1fdcfa-55c5-11e8-9e52-b6bd005e9c54.png">

The training result is very good and the accuracy is pretty high!

### Final Step: Example predictions on Test set
<img width="1156" alt="simple_cnn" src="https://user-images.githubusercontent.com/36088488/39958177-0e3c4c8c-55c5-11e8-80e3-4e6576a4a5fc.png">

If you have any question or comments, please feel free to contact me: bowentian2017@u.northwestern.edu 

The material in this repository is not to be distributed, copied, or reused without written permission from the author.
