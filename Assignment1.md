1) 
A mathematical representation of a biological neuron is the neuron. Although the dendrite of actual neurons receives electronic pulses from the axons of other neurons, these electrical signals are expressed numerically in the neuron. Electrical impulses are modulated in varying quantities at synapses between dendrites and axons. In the neuron, this is also modeled by multiplying each of the inputs.In the neuron, this is also modeled by multiplying each input value by a weight value. Only when the cumulative intensity of the input signals exceeds a certain threshold does a real neuron fire an output signal.In a neuron, we model this phenomenon by computing the weighted sum of the inputs, which represents the cumulative intensity of the input signals, and then applying a phase function to the sum to calculate the output. This performance is fed to other neurons, much as in biological neural networks. 

2)
The step size, also known as the "learning rate," is the sum by which the weights are adjusted throughout training. The learning rate is a hyperparameter that has a small positive value, usually between 0.0 and 1.0, and is used in the training of neural networks. The learning rate is a parameter that determines how quickly the model adapts to the problem.

3)
We can't set all weights to 0.0 because the optimization algorithm causes some asymmetry in the error gradient, making it impossible to search effectively.
Weight initialization has traditionally followed basic heuristics such as:
Small random values inside the range[-0.3, 0.3]
Small random numbers between 0 and 1
Small random numbers between -1 and 1
In general, these heuristics continue to function well.
Nonetheless, more customized methods have emerged, as they may result in a slightly more efficient optimization process.
The type of activation function used in the nodes that are being initialized divides these modern weight initialization techniques.The types of activation functions used in the nodes that are being initialized, such as "Sigmoid and Tanh" and "ReLU," are used to divide these modern weight initialization techniques.

4)
The objective function is the function that is used to test a solution (i.e. a set of weights) in an optimization algorithm. We might try to maximize or reduce the objective function, which means we're looking for a solution with the highest or lowest score. When it comes to neural networks, the aim is usually to reduce the amount of error.As a result, the objective function is often called a cost function or a loss function, and the value determined by the loss function is simply referred to as "loss."

5)
The derivative of f(g(x)) is f'(g(x))g', according to the chain law. To put it another way, it aids in the differentiation of *composite functions*.
Cos(8x), for example, is a composite function since it can be written as f(g(x)) with f(x)=cos(x) and g(x)=8x. Backpropagation, in simple terms, performs a backward pass through a network after each forward pass while changing the model's parameters using this chain rule.