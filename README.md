# Multiclass Classification

## Objective 
- Project to implement the Tensorflow and Keras libraries to (supervise) train and test a single layer neural network for multiclass classification
- Dataset was produced using the Sklearn library 

## Method
- Similar method applied to that used in the [Simple Perceptron Model](https://github.com/sebdisiena/Simple-Perceptron-Model?tab=readme-ov-file) and [Simple Keras Perceptron Model](https://github.com/sebdisiena/Simple-Perceptron-Model-Keras) repositories
- Utilised Keras' Adam stochastic gradient descent model  
- Method utilises one input layer of 2 nodes, and an output layer of x nodes to classify the dataset to x number of classes
- Multiclass cross entropy is applied which differs from the binary cross entropy equation
- Hot encoding of labels for dataset was required to eliminate unecessary dependencies within data labels. Output from this method is show below for 3 classes 
  <hr>
  <img src="Figures/hot_encode.png" alt="Hot Encode" width="300" style="display:block; margin:10px 0;">

## Results
- Accuracy and loss of 0.9910 and 0.0269 respectively after 100 epochs (for 3 classes) 
  <hr>
  <img src="Figures/accuracy_plot.png" alt="Accuracy Plot" width="300" style="display:block; margin:10px 0;"> 
  <img src="Figures/loss_plot.png" alt="Loss Plot" width="300" style="display:block; margin:10px 0;">
- Effectively plotted 3 regions for classification through contour plot and successful in classifying a random inputted data point into the correct class (0)
  <hr>
  <img src="Figures/contour_plot.png" alt="Contour Plot" width="300" style="display:block; margin:10px 0;">
  <img src="Figures/new_point_contour_plot.png" alt="Model Prediction" width="300" style="display:block; margin:10px 0;">

- Accuracy and loss of 0.9431 and 0.1616 respectively after 100 epochs (for 5 classes) 
  <hr>
  <img src="Figures/5_class_accuracy_plot.png" alt="Accuracy Plot" width="300" style="display:block; margin:10px 0;"> 
  <img src="Figures/5_class_loss_plot.png" alt="Loss Plot" width="300" style="display:block; margin:10px 0;">
- Effectively plotted 3 regions for classification through contour plot
  <hr>
  <img src="Figures/5_class_contour_plot.png" alt="Contour Plot" width="300" style="display:block; margin:10px 0;">