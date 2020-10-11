Selection of compute-device which best matches criteria.

```c
1. Check how many compute devices are attached.
2. Select device with atleast compute capability 1.3.
```

```bash
# OUTPUT
Current CUDA device: 0
CUDA device with atleast compute capability 1.3: 0

Cards that have compute capability 1.3 or higher
support double-precision floating-point math.
```

See [main.cu] for code, [main.ipynb] for notebook.

[main.cu]: main.cu
[main.ipynb]: https://colab.research.google.com/drive/1mVl4hFESWT-6BLQVrQS98Wj_CGMalY8y?usp=sharing


### references

- [CUDA by Example :: Jason Sanders, Edward Kandrot](http://www.mat.unimi.it/users/sansotte/cuda/CUDA_by_Example.pdf)
