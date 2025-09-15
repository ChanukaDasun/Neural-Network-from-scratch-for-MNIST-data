# Neural-Network-from-scratch-for-MNIST-data
A neural network built from scratch with NumPy to classify MNIST handwritten digits. Implements forward propagation (ReLU, Softmax), cross-entropy loss, backpropagation, and gradient descent, with dataset splitting, one-hot encoding, and accuracy evaluation for end-to-end training.

## MNIST dataset explanation
<img width="354" height="327" alt="image" src="https://github.com/user-attachments/assets/c05752b4-3921-46fa-9e46-e4be3d37f9db" />

here all the handwritten digit images are divide into 28x28 pixel grid (each pixel has its own pixel value between 0-255) and each pixel consider as a feature of the image itself which feed into the neural network.

## Structure of the Neural network 
we are going to build a neural network for handwritten digit recognition problem. This is a multiclassification problem since there has 10 classes which numbers from 0 to 9. As it mentioned earlier each image has 28x28=784 input features so the input layer has 784 units/neurons. Since this problem has 10 classes the output layer has 10 units. below it shows how the structure of the neural network for this problem is going to be.  
<img width="908" height="584" alt="image" src="https://github.com/user-attachments/assets/3349ea33-4f14-4b2c-b5a8-529dadc9e545" />

