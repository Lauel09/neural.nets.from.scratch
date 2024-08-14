# Learning Micrograd
This is a simple implementation of a backpropagation algorithm in Python. It is based on the Andrej Karpathy's [Micrograd](https://github.com/karpathy/micrograd). This is a simpler version.


## Implementation details

1.  Creation of `Value` class that represents an universal value that can be used in computation graph.

2. `Value` has various methods like `backward` to compute gradients, `__add__`, `__mul__`, `__pow__` etc. to perform operations on the values. These methods were necessary for basic operations and calculating gradient smoothly.

3. Implemented class in this particular heirarchial order: `Neuron`