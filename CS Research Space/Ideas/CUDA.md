We can use the GPU to do computations for us. (more on this later)

```python
gpu = torch.device("cuda")

x = x.to(gpu) # Allocate `x` in GPU's memory
# Do computations in GPU
```