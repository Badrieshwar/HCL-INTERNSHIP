# HCL-INTERNSHIP
FLOWER RECOGNIZATION USING DEEP LEARNING

# TECHNOLOGIES 

### Numpy – pip install numpy

### Keras – pip install keras

### Tensorflow – pip install tensorflow

### openCV - pip install opencv-python

### matplotlib - pip install matplotlib

# SYSTEM ARCHITECTURE

![image](https://user-images.githubusercontent.com/107951883/200894291-9b5598bc-1801-4650-a359-49e54d838c09.png)

# Steps to Implement:

## 1. Import all the libraries

## 2. Here we are loading our datasets. We are using the flow_from_directory function of keras which loads the dataset from the folder and will also categorize it into respective categories.2. Here we are loading our datasets. We are using the flow_from_directory function of keras which loads the dataset from the folder and will also categorize it into respective categories.

## 3. Here we are doing the same thing for our test dataset.

## 4. In this, we are creating our cnn variable which is also our CNN model. This is the first step of building it and here we are defining it that we are using a sequential model of Keras.

## 5. Here we are doing the first step of our four steps discussed above. The first step is to pass our images through the convolutional layer. After that, it passes to the pooling layer. Here we are using Max_pool.

## 6. Here we are doing the same thing as above. This is done because there is a possibility that some important features might be left in the first iteration. So, we are performing it twice to get good results.

## 7. Here are dropping out some units in our network. We are using the dropout layer for that purpose. This layer is an important step for building our neural network because it prevents overfitting by dropping some of the units.

## 8. After pooling and dropping, the next step is to flatten the matrix obtained. This step is already explained above. Here we are using Flatten function in Keras for flattening.

## 9. Here we are making our hidden layer. As explained above, our flattened neuron layer has to pass through hidden layers where some computations occur which ultimately produces results.

## 10. Here we are using again the same action but with a different activation function. Here we changed the activation function because different activation function gives different results. You can try using different functions and see which one gives the best result. In our case, the ‘softmax’ function gives the best result.

## 11. Here are compiling our final results. For this, we have to pass an optimizer. There are a lot of optimizers. You can try them out.

## 12. After performing all the steps, we have finally built our Neural Network. Now we have to provide training and test datasets to train into this neural network and we are done.

## 13. Here we are providing an image to our neural network to predict the output to check if it is working correctly. So, we provide an image from the prediction folder. For testing, we provided an image of a daisy flower.

## 14. This code is to classify the image as to whether the flower daisy or rose or dandelion or sunflower or tulip. Because we are gonna get our answer in form of 1, 2, 3, 4, 5.

## 15. Here we are just printing the result.

# output

![image](https://user-images.githubusercontent.com/107951883/200896270-d4056613-69a2-4518-b801-edc337afa9a1.png)

![image](https://user-images.githubusercontent.com/107951883/200895971-e844213c-9235-4744-a82c-6bec696c389d.png)

![image](https://user-images.githubusercontent.com/107951883/200895990-56b537f4-036b-41e8-8bd7-ff50fc04ed25.png)
