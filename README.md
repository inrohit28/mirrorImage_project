# mirrorImage - Mirror image with NPP

## Project Description

A NPP CUDA Sample that demonstrates how to use NPP mirrorIMage function to mirror an Image on horizontal axis

## Key Concepts

Performance Strategies, Image Processing, NPP Library

## src dir

main program: mirrorImage/mirrorImage.cpp
helper functions: Common/*


## Build and Run

## Linux
The Linux samples are built using makefiles. To use the makefiles, change the current directory to the sample directory you wish to build, and run make:
```
./run.sh

### Program Output

./mirrorImage
./mirrorImage Starting...

GPU Device 0: "Ampere" with compute capability 8.6

NPP Library Version 11.3.3
  CUDA Driver  Version: 12.0
  CUDA Runtime Version: 11.3
  Device 0: <          Ampere >, Compute SM 8.6 detected
mirrorImage opened: <./Lena.pgm> successfully!
Saved image: ./Lena_mirrorImage.pgm



## Supported SM Architectures

[SM 3.5 ](https://developer.nvidia.com/cuda-gpus)  [SM 3.7 ](https://developer.nvidia.com/cuda-gpus)  [SM 5.0 ](https://developer.nvidia.com/cuda-gpus)  [SM 5.2 ](https://developer.nvidia.com/cuda-gpus)  [SM 6.0 ](https://developer.nvidia.com/cuda-gpus)  [SM 6.1 ](https://developer.nvidia.com/cuda-gpus)  [SM 7.0 ](https://developer.nvidia.com/cuda-gpus)  [SM 7.2 ](https://developer.nvidia.com/cuda-gpus)  [SM 7.5 ](https://developer.nvidia.com/cuda-gpus)  [SM 8.0 ](https://developer.nvidia.com/cuda-gpus)  [SM 8.6 ](https://developer.nvidia.com/cuda-gpus)

## Supported OSes

Linux, Windows

## Supported CPU Architecture

x86_64, ppc64le, armv7l

## CUDA APIs involved

## Dependencies needed to build/run
[FreeImage](../../README.md#freeimage), [NPP](../../README.md#npp)

## Prerequisites

Download and install the [CUDA Toolkit 11.4](https://developer.nvidia.com/cuda-downloads) for your corresponding platform.
Make sure the dependencies mentioned in [Dependencies]() section above are installed.



## References (for more details)




