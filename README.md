# Sparse-Tensor
Sparse Tensor implementation using linked lists
This project introduces a Sparse Tensor implementation using linked lists and focuses on sub-tensor computations. Here's an analysis:

Key Components in the Code:
Sparse Tensor Class (STen):

Implements a sparse tensor using a linked list of Node structures to store non-zero elements.
Includes methods for:
Adding new non-zero elements (add function).
Counting sub-tensors that match a target sum (subTen function).
Node Structure:

Represents each non-zero element with coordinates (x, y, z) and a value.
Uses a linked list to manage sparse data efficiently.
Goal:

Count sub-regions (sub-tensors) in the sparse tensor whose elements sum to a specified target value.
