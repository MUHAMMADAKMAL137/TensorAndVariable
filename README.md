# TensorAndVariable
During my practice with the code from the book "Deep Learning with Python" by François Chollet, I encountered the concepts of tensors and variables. These concepts are fundamental in building and training deep learning models.

In the code, tensors are used to represent numerical data. Tensors are multidimensional arrays that hold values and are utilized for input data, model weights, and intermediate computations. For example, when loading the MNIST dataset, the images and labels were converted into tensors. Throughout the code, tensors were involved in operations such as matrix multiplication, activation functions, and loss calculations during training and evaluation.

Variables, on the other hand, are a specific type of tensor used to hold values that can be updated during model training. They are particularly important for representing the learnable parameters, such as weights and biases, of a neural network. In the code, variables were created when defining the model architecture using Keras. These variables were initialized with random values and updated through the process of backpropagation during training. By utilizing functions like `tf.Variable` or `keras.layers.Layer.add_weight`, I was able to create and manage these variables.

Variables play a crucial role in gradient computation, as they enable the optimization process of the model. By storing the learned information and capturing the knowledge acquired during training, variables allow for the adjustment and fine-tuning of the model's parameters.

My practice with tensors and variables provided me with a deeper understanding of their significance in deep learning. By working with these concepts, I was able to develop a solid foundation in model computation and optimization, which further enhanced my understanding of the intricacies of deep learning models.
