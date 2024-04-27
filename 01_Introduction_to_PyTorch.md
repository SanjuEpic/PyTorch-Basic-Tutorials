# Introduction to PyTorch

PyTorch is an open-source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing, primarily developed by Facebook's AI Research lab (FAIR). It is free and open-source software released under the Modified BSD license. PyTorch provides two high-level features:

- Tensor computing (like NumPy) with strong acceleration via graphics processing units (GPU)
- Deep neural networks built on a tape-based autograd system

You can define your neural networks in PyTorch using the  package, which relies on autograd to define models and differentiate them. An  contains layers, and a method  that returns the .

## Why PyTorch?

- It's more pythonic and designed to be intuitive and linear in thought, which makes it easier to learn and use.
- PyTorch has dynamic computation graphs that allow you to change how the network behaves on the fly, unlike static graphs in TensorFlow or other libraries.
- PyTorch is known for having a strong community, with support from many contributors.

In the next tutorial, we will dive deeper into tensors, the fundamental building blocks of PyTorch.
