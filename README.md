# FashionMNISTPersonalProject
I created a Deep Learning project that predicts the class of a fashion item using computer vision trained on Fashion MNIST

Here is the workflow of what I accomplished:

1. I loaded the dataset using tensorflow's keras API
2. I created a sequential neural network model without a convolutional neural network (CNN) at first
3. I compiled the model with an adam optimizer, sparse_categorical_crossentropy loss function (it is preferred for multi-class image classification), and displayed the accuracy of the model on validation data using accuracy metrics
4. I then fitted this model on the training and validation images
5. Then, I created a second sequential model that implemented two convolutions and poolings and did the same procedure as steps 3 and 4
6. I then experimented by removing a convolution and compared the validation accuracy metric

Overall, here is a summary of the skills I implemented:

- Implementing Keras in Tensorflow project
- Creating multi-class categorical image classifier
- Implementing convolutional neural networks
- Evaluating model accuracy
- Understanding the optimal loss function and optimizer for image classification problems involving more than two categories
