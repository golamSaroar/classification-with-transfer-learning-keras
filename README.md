## Classification with Transfer Learning

The aim of this project is to create and train a Convolutional Neural Network (CNN) with an existing CNN model architecture, and its pre-trained weights. For this task, I have used the MobileNet model architecture along with its weights trained on the popular ImageNet dataset. 

By using a model with pre-trained weights, and then training just the last layers on a new dataset, we can drastically reduce the training time required to fit the model to the new data. The pre-trained model has already learned to recognize thousands of simple and complex image features, and I have used its output as the input to the last layers that I have trained.

Please have a look at the notebook [here](classification-with-transfer-learning-keras.ipynb), or open it on [Colab](https://drive.google.com/file/d/1ds3z-u5uUMmLDd9IS9LbV-2iUtDbkiLA/view?usp=sharing).
