# About app

The application allow you to confirm matrix maltiplication on your GPU and to compare the result with multiplication completed on CPU

# How to execute
Before start the app please follow this [guide](https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html)

---

Note: you need to have compatible GPU, [list](https://developer.nvidia.com/cuda-gpus) of allowed GPUs

---

After completeing of all prerequests you can complile it with the following command:

`/usr/local/cuda/bin/nvcc -I/usr/local/cuda/include -L/usr/local/cuda/lib -lcurand  matrixMul.cu -o test`

It will generate executable file with the name "test".
Execute it by the following command: `./test`. Note that yout terminal should be in the app's directory.  

# Results

The results were tested on GeForce gt730.

| Matrix size   | CPU, ms       | GPU, ms|
| ------------- |:-------------:| -----: |
| 320x320       | 225           | 81.284 |
| 640x640       | 2259          | 92.381 |
| 1600x1600     | 45380         | 243.549|
