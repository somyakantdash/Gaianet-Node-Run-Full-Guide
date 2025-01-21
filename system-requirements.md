# System requirements

You can install the GaiaNet on a wide variety of devices and operating systems with or without GPUs. The node installing and operating instructions work on devices ranging from Raspberry Pi, MacBooks, Linux servers, Windows Desktop, to cloud-based Nvidia H100 clusters. For institutional operators, we recommend EITHER of the following for a GaiaNet node. 

| System                                     | Minimum Requirements        |
| ------------------------------------------ | --------------------------- |
| OSX with Apple Silicon (M1-M4 chip)	       | 16GB RAM (32GB recommended) |
| Ubuntu Linux 20.04 with Nvidia CUDA 12 SDK | 8GB VRAM on GPU             |
| Azure/AWS                                  | Nvidia T4 GPU Instance      |

> Check out our [tutorial](tasks/cuda) on how to install the NVIDIA driver and the CUDA toolkit on a Ubuntu 22.04 machine.

If you are hosting the node in your home or office, it needs access to the public Internet to join the GaiaNet network.

## Supported on

GaiaNet node software is designed to be cross-platform, allowing it to run on various CPU and GPU architectures. The GaiaNet installer automatically detects the presence of NVIDIA CUDA drivers and leverages the power of GPU accelerators on the device. More hardware support is on the way.

### GPU

The GaiaNet node can run on all types of NVIDIA GPU products from H100 to NVIDIA Jetson series of hardware.
It also runs on all Apple Silicon M-series GPUs.

### CPU

* Arm-64 based on CPU chips
* X86 based on CPU chips
* Apple M1 chips
* Apple M1 Pro chips
* Apple M1 Max chips
* Apple M1 Ultra chips
* Apple M2 chips
* Apple M2 Pro chips
* Apple M2 Max chips
* Apple M2 Ultra chips
* Apple M3 chips
* Apple M3 Pro chips
* Apple M3 Max chips
* Apple M3 Ultra chips

### Oses

* macOS
* Linux-like OS

