# NLP
This project focuses on the solutioning for different use cases for NLP leveraging GPT3. This is a good starting point for NLP beginners. 

Neural network neuron is a mathematical function that takes different inputs with their corresponding weights, calculates an output value that passed through an activation function. Neurons in a neural network are anologous to neurons in the brain. 

Neural networks are made of layers of neuron. Screenshot below is a simple neural network with one input layer, one hidden layer and an output layer. 

![image](https://user-images.githubusercontent.com/70435753/133885343-ad0f5306-ad25-4abe-b70b-03dd49aa71ea.png)

Key inputs for the neural network are the learning rate and activation function. Learning rate determines the quantum of feedback that gets propagated back in the neural network. Learning rates are key in neural network. High learning rate can result in unstable learning process that does not converge and low learning rate will take a lot of time/iterations to get to the optimal weights. 

The weigths in the neural network are initialized randonmly. The backpropogation process adjusts weights based on the the learning rate and variation in the output from the expected value for the sample(quantum of error).

Loss is the prediction error in the neural network.  Method used to calulate the loss is called the loss function. This loss is fed back into the neural network as part of the back propogation network. 

In the backpropogation mechanism, we need to calculate the partial derivative of the error with respect to the weights in each layer. To calculate this value, we use the chain rule. Chain rule is a methematical concept used in calculus to calculate partial derivatives. 

              ∂c/∂a = ∂c/∂b . ∂b/∂a

Rate of change of C w.r.t a is equal to rate of change of C w.r.t b multipled by rate of change of b w.r.t a.





