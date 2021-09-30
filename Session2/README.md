Session 2: Neural network with backpropagation simulated in excel. 

The below screenshot depicts a four layer neutral network with one input layer, two hidden layer and one output layer. The network is represented in the picture below:

													
													
													
													
													
													
													
													
													
													
													
													
													
													
![image](https://user-images.githubusercontent.com/70435753/135507939-47a494d1-2318-486d-bfec-a1bfc565bc86.png)

The values for the nodes in hidden layer1 are calculated based on weights w1,w2, w3 and w4 and input values relevant based on the connecting lines. Activation function that is used in hidden layer1 is sigmoid function. 

			
![image](https://user-images.githubusercontent.com/70435753/135509163-b368ce6e-12cf-467c-8adf-8815858427aa.png)


The values for the nodes in hidden layer2 are calculated based on weights w5,w6, w7 and w8 and the output values from activation function in hidden layer1.Activation function that is used in hidden layer2 is sigmoid function. 

		
![image](https://user-images.githubusercontent.com/70435753/135509261-9e11c0e5-aa01-4408-ae87-7eb17f1b13e0.png)
		

Loss is the prediction error in the neural network.  Method used to calulate the loss is called the loss function. This loss is fed back into the neural network as part of the back propagation network. Error for each node in output layer is calculated as below:

![image](https://user-images.githubusercontent.com/70435753/135509478-0a2e796e-4458-4154-ab67-43ef9764e870.png)
													
													
Weights in the neural network are adjusted based on the attribution to the loss on account of the weights (∂E/∂w). Learning rate determines the rate at which the network learns from the loss. Chain rule in mathematics is used to arrive at the ∂E/∂w value for each of the weights. Chain rule is described below.

Chain rule is a methematical concept used in calculus to calculate partial derivatives. 

              ∂c/∂a = ∂c/∂b . ∂b/∂a

Rate of change of C w.r.t a is equal to rate of change of C w.r.t b multipled by rate of change of b w.r.t a.


The below screenshot captures the equations derived for the partial derivatives of the error for each of the weights using the chain rule. 

![image](https://user-images.githubusercontent.com/70435753/135511238-9ad81e7f-65c0-4143-82d3-8bae41f2e6b1.png)

													
													
The below screenshot captures a simulated neural network in excel based on formula's shared in the earlier part of this readme file. 

![image](https://user-images.githubusercontent.com/70435753/135511743-c2e6949b-854c-433f-b2e7-010e57050665.png)


Learning rate determines that rate in which the loss value is fed back into model to adjust the weights. Learning rate needs to be optimized. While higher learning rates can help the model learn faster, there are scenarios where the model does not converge faster on account of higher learning rates; sometimes they do not even converge to the minimum loss point. 

Below are the screenshots of the visualization highlighting the rate at which error reduces for different learning rates. We can see that for the neural network in this exercise, the model learns faster when the learning rate increases. 
																														
![image](https://user-images.githubusercontent.com/70435753/135512518-35440041-6c99-4d3d-94af-542d749501a1.png)
												

![image](https://user-images.githubusercontent.com/70435753/135512614-b46906b2-85ca-4452-8761-f58092520ddd.png)
													
									
![image](https://user-images.githubusercontent.com/70435753/135513537-30cf38c0-9e79-4bce-aa68-9cf17caea403.png)
												
													
													







