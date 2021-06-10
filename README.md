# AI at the edge

A curated list of hardware, software, frameworks and other resources for Artificial Intelligence at the edge. Inspired by [awesome-dataviz](https://github.com/fasouto/awesome-dataviz).


## Contents
- [Hardware](#hardware)
- [Software](#software)
- [Frameworks](#frameworks)
- [Contributing](#other-interesting-resources)
- [License](#license)

# Hardware
- [OpenMV](http://docs.openmv.io) - A camera that runs with MicroPython on ARM Cortex M6/M7 and great support for computer vision algorithms. Now with [support for Tensorflow Lite too](https://openmv.io/blogs/news/tensorflow-lite-and-person-detection).
- [JeVois](http://jevois.org/) - A TensorFlow-enabled camera module.
- [Edge TPU](https://cloud.google.com/edge-tpu/) - Google’s purpose-built ASIC designed to run inference at the edge.
- [Movidius](https://www.movidius.com) - Intel's family of SoCs designed specifically for low power on-device computer vision and neural network applications.
    - [UP AI Edge](https://up-shop.org/25-up-ai-edge) - Line of products based on Intel Movidius VPUs (including Myriad 2 and Myriad X) and Intel Cyclone FPGAs.
    - [DepthAI](https://www.crowdsupply.com/luxonis/depthai) - An embedded platform for combining Depth and AI, built around Myriad X
- [NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/) - High-performance embedded system-on-module to unlock deep learning, computer vision, GPU computing, and graphics in network-constrained environments.
    - Jetson TX1
    - Jetson TX2
    - Jetson Nano
- [Artificial Intelligence Radio - Transceiver (AIR-T)](https://www.crowdsupply.com/deepwave-digital/air-t) - High-performance SDR seamlessly integrated with state-of-the-art deep learning hardware.
- [Kendryte K210](https://kendryte.com/) - Dual-core, RISC-V chip with convolutional neural network acceleration using 64 KLUs (Kendryte Arithmetic Logic Unit).
    - [Sipeed M1](http://en.dan.sipeed.com/) - Based on the Kendryte K210, the module adds WiFi connectivity and an external flash memory.
    - [M5StickV](https://docs.m5stack.com/#/en/core/m5stickv) - AIoT(AI+IoT) Camera powered by Kendryte K210
    - [UNIT-V](https://docs.m5stack.com/#/en/unit/unitv) - AI Camera powered by Kendryte K210 (lower-end M5StickV)
- [GreenWaves GAP8](https://greenwaves-technologies.com/en/gap8-product/) - RISC-V-based chip with hardware acceleration for convolutional operations.
- [Ultra96](https://www.96boards.ai/products/ultra96/) - Embedded development platform featuring a Xilinx UltraScale+ MPSoC FPGA.
- [Apollo3 Blue](https://www.sparkfun.com/products/15170) - SparkFun Edge Development Board powered by a Cortex M4 from Ambiq Micro.
- [Google Coral](https://coral.ai/) - Platform of hardware components and software tools for local AI products based on Google Edge TPU coprocessor.
    - Dev boards
    - USB Accelerators
    - PCIe / M.2 modules
- [Gyrfalcon Technology Lighspeeur](https://www.gyrfalcontech.ai/solutions/) - Family of chips optimized for edge computing.
- [ARM microNPU](https://www.arm.com/products/silicon-ip-cpu/machine-learning/ethos-u55) - Processors designed to accelerate ML inference (being the first one the Ethos-U55).
- [Espressif ESP32-S3](https://www.espressif.com/en/products/socs/esp32-s3) - SoC similar to the well-known ESP32 with support for AI acceleration (among many other interesting differences).
- [Maxim MAX78000](https://www.maximintegrated.com/en/products/microcontrollers/MAX78000.html) - SoC based on a Cortex-M4 that includes a CNN accelerator.
- [Beagleboard BeagleV](https://beagleboard.org/beaglev) - Open Source RISC-V-based Linux board that includes a Neural Network Engine.

# Software
- [TensorFlow Lite](https://www.tensorflow.org/lite/) - Lightweight solution for mobile and embedded devices which enables on-device machine learning inference with low latency and a small binary size.
- [TensorFlow Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers) - Port of TF Lite for microcontrollers and other devices with only kilobytes of memory. Born from a [merge with uTensor](https://os.mbed.com/blog/entry/uTensor-and-Tensor-Flow-Announcement/).
- [Embedded Learning Library (ELL)](https://github.com/Microsoft/ELL) - Microsoft's library to deploy intelligent machine-learned models onto resource constrained platforms and small single-board computers.
- [uTensor](https://github.com/uTensor/uTensor) - AI inference library based on mbed (an RTOS for ARM chipsets) and TensorFlow.
- [CMSIS NN](https://arm-software.github.io/CMSIS_5/NN/html/index.html) - A collection of efficient neural network kernels developed to maximize the performance and minimize the memory footprint of neural networks on Cortex-M processor cores.
- [ARM Compute Library](https://developer.arm.com/technologies/compute-library) - Set of optimized functions for image processing, computer vision, and machine learning.
- [Qualcomm Neural Processing SDK for AI](https://developer.qualcomm.com/software/qualcomm-neural-processing-sdk) - Libraries to developers run NN models on Snapdragon mobile platforms taking advantage of the CPU, GPU and/or DSP.
- [X-CUBE-AI](https://blog.st.com/stm32cubeai-neural-networks/) - Toolkit for generating NN optimiezed for STM32 MCUs.
- [Neural Network on Microcontroller (NNoM)](https://github.com/majianjia/nnom) - Higher-level layer-based Neural Network library specifically for microcontrollers. Support for CMSIS-NN.
- [nncase](https://github.com/kendryte/nncase) - Open deep learning compiler stack for Kendryte K210 AI accelerator.
- [deepC](https://github.com/ai-techsystems/dnnCompiler) - Deep learning compiler and inference framework targeted to embedded platform.
- [uTVM](https://tvm.apache.org/2020/06/04/tinyml-how-tvm-is-taming-tiny) - *MicroTVM* is an open source tool to optimize tensor programs.
- [Edge Impulse](https://edgeimpulse.com/) - Interactive platform to generate models that can run in microcontrollers. They are also quite active on social netwoks talking about recent news on EdgeAI/TinyML.
- [Qeexo AutoML](https://qeexo.com/ml-platform/) - Interactive platform to generate AI models targetted to microcontrollers.

# Other interesting resources
- [Benchmarking Edge Computing (May 2019)](https://medium.com/@aallan/benchmarking-edge-computing-ce3f13942245)
- [Hardware benchmark for edge AI on cubesats - Open Source Cubesat Workshop 2018](https://github.com/crespum/oscw18-edge-ai)
- [Why Machine Learning on The Edge?](https://towardsdatascience.com/why-machine-learning-on-the-edge-92fac32105e6)
- [Tutorial: Low Power Deep Learning on the OpenMV Cam](https://community.arm.com/innovation/b/blog/posts/low-power-deep-learning-on-openmv-cam)
- [TinyML: Machine Learning with TensorFlow on Arduino and Ultra-Low Power Micro-Controllers](http://shop.oreilly.com/product/0636920254508.do) - O'Reilly book written by Pete Warden, Daniel Situnayake.
- [tinyML Summit](https://www.tinymlsummit.org/) - Annual conference and monthly meetup celebrated in California, USA. Talks and slides are usually [available from the website](https://www.tinymlsummit.org/#meetups).

# Contributing
- Please check for duplicates first.
- Keep descriptions short, simple and unbiased.
- Please make an individual commit for each suggestion.
- Add a new category if needed.

Thanks for your suggestions!

# License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Xabi Crespo](https://crespum.eu/) has waived all copyright and related or neighboring rights to this work.
