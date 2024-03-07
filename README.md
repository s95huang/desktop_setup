## 40 series machine
```
Ubuntu 22
CUDA 12.2
CUDNN 8.8/8.9
TensorRT 8.6

```



## 30 Machine
11.4
```
CUDA 11.4
CUDNN 8.2.4
TensorRT 8.4 GA Update 2
```
11.6
```
CUDA 11.6
CUDNN 8.4.1
TensorRT 8.4.3
```

## jetson AGX and desktop

```
CUDA 10.2
CUDNN 8.0 
TensorRT 7.1.3
```

## CUDA related errors
1. CUDA_curand_LIBRARY (ADVANCED) is needed during cmake

Solution:
Replace 11-6 with your CUDA versions
```
sudo apt-get install libcurand-dev-11-6
sudo apt-get install libcusolver-dev-11-6
```

