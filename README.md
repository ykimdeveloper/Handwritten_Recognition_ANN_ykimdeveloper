# Hand Written Recognition ANN
## Hand writing recognition using Artificial Neural Networks (ANN)
#### dataset “Digit” includes 1797 small images (8x8 pixels), each one includes a hand-written digit (0-9)
#### ANN Accuracy: 0.916666666667
#### Grid Best Accuracy Score: 0.961046188091
#### Grid Best Parameters: {'hidden_layer_sizes': (126,)}


<b>Backpropagation</b> In the following Neural Network, we have initialized the weights randomly. Use a training sample (X,y) = ((1,1), 0) to update the weights (perform one round of backpropagation using one training sample). Use learning rate parameter α = 0.1. 
<!-- ![Screenshot](blob/Capture.png)
![Screenshot](blob/Backpropagation.png) -->


![Screenshot](https://github.com/cowboyuniverse/handwrittenRecognitionANN/blob/master/blob/Capture.PNG)

![Screenshot](https://github.com/cowboyuniverse/handwrittenRecognitionANN/blob/master/blob/backpropagation.PNG)



- Build the feature matrix and label vector: Each image is considered as a data sample with pixels as features. Thus, to build the feature table you have to convert each 8x8 image into a row of the feature matrix with 64 feature columns for 64 pixels

<!-- ![Screenshot](blob/Capture2.png) -->

![Screenshot](https://github.com/cowboyuniverse/handwrittenRecognitionANN/blob/master/blob/Capture2.PNG)

-  Design and Train an ANN with one hidden layer with 80 neurons to recognize the digits based on the training dataset that you built in part (c). Use random_state=1, learning_rate_init = 0.002. Then, Test your ANN on testing set (from part(c)), and calculate and report the accuracy. Also, calculate and report the Confusion Matrix.

<!-- ![Screenshot](blob/Capture3.png) -->

![Screenshot](https://github.com/cowboyuniverse/handwrittenRecognitionANN/blob/master/blob/Capture3.PNG)

<!-- ![Screenshot](blob/Capture4.png) -->

![Screenshot](https://github.com/cowboyuniverse/handwrittenRecognitionANN/blob/master/blob/Capture4.PNG)


author: yosep kim

github.com/cowboyuniverse


<!-- ![Screenshot](https://github.com/cowboyuniverse/cancerPrediction/blob/master/blob/Capture.PNG) -->

<!-- ![Screenshot](Capture.png) -->
<!-- ![Alt TEXT](blob/Capture.png?raw=true "Title")
![Image description](blob/Capture.png)
![myimage-alt-tag](blob/Capture.png)
![Alt TEXT](Capture.png?raw=true "Title")
![Image description](Capture.png)
![myimage-alt-tag](Capture.png) -->