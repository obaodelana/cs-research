![[Tensors.png]]
## Examples of Tensors
1. 1D Tensor: A scalar
2. 2D Tensor: A vector *of arbitrary size*
3. 3D Tensor: A matrix *of arbitrary size*
4. 4D Tensor: A **list** of *matrices*, e.g.,
	- An image may be represented as a 4D Tensor of size 3, where each matrix (of dimension $\text{width}\times\text{height}$) represents the RGB values of the image, respectively.
	
		![[Image as 4D Tensor.png]]

## Creating tensors
```python
vector = torch.empty(5) # 2D Tensor of size 5
# `randn` fills the entries with normally-distributed numbers
matrix = torch.randn(4, 6) # 3D Tensor of dimension 4x6
# 4D Tensor of dimension 3x10x10 (e.g., 10x10 RGB image)
list_of_matrices = torch.empty(3, 10, 10)
```

