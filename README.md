# PRGFlow: Benchmarking SWAP-Aware Unified Deep Visual Inertial Odometry

**PRGFlow** by <a href="http://prg.cs.umd.edu"><i>Perception & Robotics Group</i></a> at the Department of Computer Science, <a href="https://umd.edu/">University of Maryland- College Park</a>.

### What will be released? 
We plan to release the Tensorflow Training and Testing for the architectures presented in the paper along with the pre-trained models. Also, we will release the hardware setup instructions for NanoPi, Google Coral USB Accelerator and Google Coral Dev Board.
(Follow this repository for more updates.)

[PRGFlow: Benchmarking SWAP-Aware Unified Deep Visual Inertial Odometry](http://prg.cs.umd.edu/research/PRGFlow_files/DiffQuadrotors.png)]

### Abstract

Odometry on aerial robots has to be of low latency and high robustness whilst also respecting the Size, Weight, Area and Power (SWAP) constraints as demanded by the size of the robot. A combination of visual sensors coupled with Inertial Measurement Units (IMUs) has proven to be the best combination to obtain robust and low latency odometry on resource-constrained aerial robots. Recently, deep learning approaches for Visual Inertial fusion have gained momentum due to their high accuracy and robustness. However, the remarkable advantages of these techniques are their inherent scalability (adaptation to different sized aerial robots) and unification (same method works on different sized aerial robots) by utilizing compression methods and hardware acceleration, which have been lacking from previous approaches. 
To this end, we present a deep learning approach for visual translation estimation and loosely fuse it with an Inertial sensor for full 6 DoF odometry estimation. We also present a detailed benchmark comparing different architectures, loss functions and compression methods to enable scalability. We evaluate our network on the MSCOCO dataset and evaluate the VI fusion on multiple real-flight trajectories.

- [Project Page](https://prg.cs.umd.edu/PRGFlow)
- [Paper](https://prg.cs.umd.edu/research/PRGFlow_files/PRGFlow.pdf)
- [arXiv Preprint](https://arxiv.org/pdf/2006.06753)


## License:
Copyright (c) 2020 Perception and Robotics Group (PRG)
