# Image_Classifier

This project aims at classifying images from MNIST and Cifar10 datasets.

 The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. Here, I tried to use Multi Layer Perceptron to perform the classification,
 Initially after processing data, I tried to define a Single Layer Neural Network to classify the dataset. Further, three hidden layers were added to the model.
 Then, I tried improving accuracy by changing the activation functions in the layers, optimizers and their parameters.
 Finally, I tried to apply dropout regularizations on the Dense Layers in the neural net.
 The model was then, saved.
 
 An overall accuracy of around 96% was obtained. The code can be found in the Jupyter Notebook - "MNIST Classifier.ipynb". The saved models(.json and .h5) are also updated with the code.

 The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes. The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. I tried to classify these images using deep learning mechanisms, like MLP and Convolutional Neural Networks(CNN).
 Only a small accuracy of 50% was obtained through the MLP model, even after performing various combinations of optimizations.
 Then, a convolutional neural network nodel was built, which gave upto 70% accuracy.
 Dropout layers were frequently added to reduce overfitting of the model.

 The final models for MLP and CNN were saved, loaded and compared. It was concluded that CNN results in a much better learning of the rgb images compared to MLPs.
