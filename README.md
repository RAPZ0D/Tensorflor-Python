# Neural Networks

- [What is a Neural Network](#what-is-a-neural-network)
- [Artificial Neural Network](#artificial-neural-network)
- [Convolution Neural Network](#convolution-neural-network)


## What is a Neural Network
What is Neural Networks?
Neural Networks are computational systems inspired by the human brain's structure and function. They consist of interconnected nodes, or neurons, organized into layers that process information.

Neurons and Layers:
1. Neurons: These are the basic units that receive inputs, apply weights to them, and pass the result through an activation function.
2. Layers: Neurons are organized into layers—input, hidden, and output layers. Input layer receives initial data, hidden layers process information, and output layer produces the final result.

Some of its applications are: 
1. Image and Speech Recognition: CNNs excel in recognizing patterns and features within images and audio.
2. Natural Language Processing (NLP): RNNs are effective in processing sequences of words for tasks like language translation, sentiment analysis, and text generation.
3. Predictive Analysis and Forecasting: Neural networks are used extensively in financial forecasting, trend analysis, and predictive modeling.

Types of Neural Netowrks: 
1. Artificial Neural Netowrks (ANN)
2. Convolution Neural Netowkr (CNN)
3. Recurrent Neural Networks (RNN)


Here is a very informative video about Neural Networks. It is a video by 3Blue1Brown [What is Neural Network](https://www.youtube.com/watch?v=aircAruvnKk)
The Image Below is a representation of what a Neural Network is in simple terms
So Neural Network is inspired by the biological neuron in a simplified manner. A biological neuron is a cell that processes and transmits information in the brain. It consists of a cell body, dendrites, and an axon. Dendrites receive signals, the cell body processes these signals, and the axon transmits signals to other neurons.

![neural](https://github.com/RAPZ0D/Neural-Network-Python/assets/100001521/24f148d8-f2e9-4fac-b236-1eeb4e5c6dd6)


The MATH behind Neural Networks

Neural Networks in Machine Learning is a combination of Biology and Mathematics. Math is the key language behind neural networks, helping them understand and process information efficiently. It's crucial because it enables these networks to describe how neurons work together, perform calculations quickly, and learn from examples. Math also guides the fine-tuning of these networks, ensuring they make accurate predictions and generalize well to new, unseen data. It's like the foundation that allows neural networks to do their job—making sense of data, learning from it, and making useful decisions or predictions. Without math, it would be really tough for these networks to work effectively and learn from the world around them.
Here's an overview along with some key mathematical elements:

    1. Linear Transformation:
        Formula: z=w⋅x+bz=w⋅x+b
        Explanation: This represents the core operation within a neuron where xx is the input, ww is the weight, bb is the bias, and zz is the weighted sum.
        Matrix Form: For multiple inputs and weights, this operation can be represented as matrix multiplication: Z=W⋅X+BZ=W⋅X+B, where ZZ and XX are matrices of weighted sums.

    2. Activation Functions:
        Formula (e.g., Sigmoid): σ(z)=11+e−zσ(z)=1+e−z1​
        Explanation: Activation functions introduce non-linearity, enabling neural networks to model complex relationships in data.
        Other Functions: ReLU (Rectified Linear Unit), Tanh, Leaky ReLU, etc., each with its own mathematical formulation.

    3. Loss Functions:
        Formula (e.g., Mean Squared Error): L(y,y^)=1n∑i=1n(yi−y^i)2L(y,y^​)=n1​∑i=1n​(yi​−y^​i​)2
        Explanation: These functions measure the difference between predicted (y^y^​) and actual (yy) values, guiding the learning process by quantifying the model's performance.

    4. Gradient Descent:
        Formula (Gradient Descent Update Rule): wi+1=wi−α⋅∂L∂wwi+1​=wi​−α⋅∂w∂L​
        Explanation: Used in training, this formula updates weights (ww) based on the gradient of the loss function (LL) with respect to the weights, multiplied by a learning rate (αα).

    5. Backpropagation:
        Explanation: Involves the application of the chain rule of calculus to compute gradients throughout the network. It calculates how changing each weight in the network contributes to the overall error.

    6. Matrix Calculus:
        Explanation: Crucial for efficiently computing gradients in neural networks. Involves operations like matrix differentiations (e.g., calculating gradients with respect to weight matrices in various layers).

 ![math_neural](https://github.com/RAPZ0D/Neural-Network-Python/assets/100001521/9442ab8c-066a-495c-89b6-ca2dee9d4830)

 The Activation Functions 
 
![graphs](https://github.com/RAPZ0D/Neural-Network-Python/assets/100001521/25cd6677-b553-46b7-b269-42d86c606176)
