Selection of compute-device which best matches criteria.

```c
1. Check how many compute devices are attached.
2. Select device with atleast compute capability 1.3.
```

```bash
$ nvcc -std=c++17 -Xcompiler -O3 main.cu
$ ./a.out

# Current CUDA device: 0
# CUDA device with atleast compute capability 1.3: 0
#
# Cards that have compute capability 1.3 or higher
# support double-precision floating-point math.
```

See [main.cu] for code.

[main.cu]: main.cu

<br>
<br>


## References

- [CUDA by Example :: Jason Sanders, Edward Kandrot](https://gist.github.com/wolfram77/72c51e494eaaea1c21a9c4021ad0f320)

![](https://ga-beacon.deno.dev/G-G1E8HNDZYY:v51jklKGTLmC3LAZ4rJbIQ/github.com/moocf/choose-device.cuda)
