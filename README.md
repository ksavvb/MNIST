# MNIST
This project demonstrates a simple Machine Learning model trained on the MNIST dataset. We use 70.000 grayscale images of handwritten digits, then we train the model on 60.000 images and we test the result with the rest 10.000 images. To achieve this we use a Deep Neural Network with the following parameters: 
- learning rate = 0.001
- epochs = 20
-  Architecture: 5 layers — 784 → 256 → 128 → 64 → 10
-  Activation function: ReLU (for hidden layers)
-   With these parameters we succesfully achieve  99.5% accuracy.

  You can view and run this Google Collab here: https://colab.research.google.com/drive/1HbnQHISZmfYIXWmmv1pk8hP9WVrTE1JE?usp=sharing

Questions:

a.Do you consider the MNIST data to be good for training a model? Justify your answer.
- Yes, the MNIST dataset is good for training a model especially for begginers because it's clean and easy to process.

b.Do you consider all the pixels equally valuable?
-No, because the corners are usually empty (black) all the time, so they don’t add any value to the prediction.

c.In which cases is it a good idea to use a Deep Neural Networks?
-We should use them when we have a lot of data, there are comple and non linear relatioships.

d.Can Deep Learning be used in all three branches of Machine Learning?
-Yes, Deep Neural Networks are flexible and can be used everywhere.
