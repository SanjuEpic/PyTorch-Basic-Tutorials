# Basic Operations with Tensors

In PyTorch, you can perform a variety of operations on tensors. These operations are fast and efficient, taking advantage of GPU acceleration when available. Here are some of the basic operations you can perform on tensors:

## Arithmetic Operations

- Addition: `torch.add(x, y)` or `x + y`
- Subtraction: `torch.sub(x, y)` or `x - y`
- Multiplication: `torch.mul(x, y)` or `x * y`
- Division: `torch.div(x, y)` or `x / y`

## In-place Operations

In-place operations are operations that directly change the content of a given Tensor without making a copy. For example:

- In-place addition: `x.add_(y)`

## Reshaping Tensors

Reshaping tensors is a common operation in PyTorch. It allows you to change the shape of a tensor without changing its data. Here's how you can reshape a tensor:

- `x.view(a, b)`: Returns a new tensor with the same data as `x` but of a different shape.
- `x.reshape(a, b)`: Returns a new tensor with the same data as `x` and the specified shape.
- `x.resize_(a, b)`: Changes the shape of tensor `x` in-place.

Note: The `view` method returns a new tensor that shares the same data but looks different, while `reshape` can return a copy if the shapes are not compatible.

## Broadcasting

Broadcasting enables you to perform operations on tensors of different shapes. When operating on two tensors, PyTorch automatically expands one to match the shape of the other.

## Tensor to NumPy and Vice Versa

Tensors can be converted to NumPy arrays and vice versa using the `.numpy()` method and `torch.from_numpy()` function respectively.

In the next tutorial, we will delve into the autograd system and how it facilitates the computation of gradients.
