# matrix-cuda
matrix multiplication in CUDA, this is a toy program for learning CUDA, some functions are reusable for other purposes


# test results
following tests were carried out on a Intel Xeon 1650v3 and NVIDIA GTX 1060.

[C\Users\1111\Desktop\MatMul]a

please type in m n and k

1024 1024 1024

Time elapsed on matrix multiplication of 1024x1024 . 1024x1024 on GPU: 13.604608 ms.

Time elapsed on matrix multiplication of 1024x1024 . 1024x1024 on CPU: 9925.121094 ms.

all results are correct!!!, speedup = 729.541138

[C\Users\1111\Desktop\MatMul]a

please type in m n and k

1024 1024 1023

Time elapsed on matrix multiplication of 1024x1024 . 1024x1023 on GPU: 51.141281 ms.

Time elapsed on matrix multiplication of 1024x1024 . 1024x1023 on CPU: 8964.353516 ms.

all results are correct!!!, speedup = 175.286057

