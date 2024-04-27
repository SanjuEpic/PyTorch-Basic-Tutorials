# Tensors in PyTorch

Tensors are the fundamental unit of data in PyTorch and are used for all computational operations. A tensor is a generalization of vectors and matrices to potentially higher dimensions. In PyTorch, we use tensors to encode the inputs and outputs of a model, as well as the model’s parameters.

Tensors are similar to NumPy’s ndarrays, except that they can run on GPUs to accelerate computing.

## Creating Tensors

You can create tensors in PyTorch using the  function:



## Operations on Tensors

PyTorch provides a wide range of operations on tensors which are both fast and flexible:



In the next tutorial, we will explore the autograd system in PyTorch, which allows for automatic differentiation of tensor operations, making it easy to compute gradients.
