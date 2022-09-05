# Awesome-Rust-Embedded-Robotics
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🔥🔥🔥 This repository lists some awesome public Rust projects for embedded and robotics.

## Contents
- [Awesome-Rust-Embedded-Robotics](#awesome-rust-embedded-robotics)
  - [Summary](#summary)
    - [Awesome List](#awesome-list)
    - [Code Overview](#code-overview)
  - [Embedded Programming](#embedded-programming)
  - [General Operating System](#general-operating-system)
  - [Robot Operating System](#robot-operating-system)
  - [FFI Bindings](#ffi-bindings)
  - [GPU Integration](#gpu-integration)  
  - [Linear Algebra](#linear-algebra)
  - [Optimization Algorithm](#optimization-algorithm)
  - [Signal Processing](#signal-processing)
  - [Sensor API](#sensor-api)
  - [Image Processing](#image-processing)
  - [Localization and Mapping](#localization-and-mapping)
  - [Path Planning](#path-planning)
  - [Motion Control](#motion-control)
  - [Machine-Learning](#machine-learning)
  


- ## Summary

  - ### Awesome List

    - [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) <img src="https://img.shields.io/github/stars/rust-embedded/awesome-embedded-rust?style=social"/> : Curated list of resources for Embedded and Low-level development in the Rust programming language.

    - [robotics-rs/robotics.rs](https://github.com/robotics-rs/robotics.rs) <img src="https://img.shields.io/github/stars/robotics-rs/robotics.rs?style=social"/> : List of (awesome) Rust libraries for Robotics. 


  - ### Code Overview

    - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR. 




- ## Embedded Programming

  - [stm32-rs](https://github.com/stm32-rs) : Community Rust support projects for STM32 microcontrollers.

  - [rust-embedded](https://github.com/rust-embedded) : Enabling usage of Rust on Embedded Platforms (Embedded Linux / RTOS / Bare Metal).



- ## General Operating System

  - [BlogOS](https://github.com/phil-opp/blog_os) <img src="https://img.shields.io/github/stars/phil-opp/blog_os?style=social"/> : This repository contains the source code for the Writing an OS in Rust series at [os.phil-opp.com](https://os.phil-opp.com/).

  - [rust-raspberrypi-OS-tutorials](https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials) <img src="https://img.shields.io/github/stars/rust-embedded/rust-raspberrypi-OS-tutorials?style=social"/> :  📚 Learn to write an embedded OS in Rust 🦀 
  
  - [rCore-Tutorial-v3](https://github.com/chyyuu/os_kernel_lab) <img src="https://img.shields.io/github/stars/chyyuu/os_kernel_lab?style=social"/> : OS kernel labs based on Rust/C Lang & RISC-V 64/X86-32.

  - [rCore](https://github.com/rcore-os/rCore) <img src="https://img.shields.io/github/stars/rcore-os/rCore?style=social"/> : Rust version of THU uCore OS. Linux compatible. 

  - [zCore](https://github.com/rcore-os/zCore) <img src="https://img.shields.io/github/stars/rcore-os/zCore?style=social"/> : Reimplement Zircon microkernel in Rust. 

  - [RustSBI](https://github.com/rustsbi/rustsbi) <img src="https://img.shields.io/github/stars/rustsbi/rustsbi?style=social"/> : RISC-V Supervisor Binary Interface (RISC-V SBI) implementation library in Rust; runs on M or HS mode; good support for embedded Rust ecosystem. 

  - [writing-an-os-in-rust](https://github.com/rustcc/writing-an-os-in-rust) <img src="https://img.shields.io/github/stars/rustcc/writing-an-os-in-rust?style=social"/> : 《使用Rust编写操作系统》

  - [Theseus](https://github.com/theseus-os/Theseus) <img src="https://img.shields.io/github/stars/theseus-os/Theseus?style=social"/> : Theseus is a modern OS written from scratch in Rust that explores 𝐢𝐧𝐭𝐫𝐚𝐥𝐢𝐧𝐠𝐮𝐚𝐥 𝐝𝐞𝐬𝐢𝐠𝐧, novel OS structure, and state management.

  - [snarkOS](https://github.com/AleoHQ/snarkOS) <img src="https://img.shields.io/github/stars/AleoHQ/snarkOS?style=social"/> : A Decentralized Operating System for Zero-Knowledge Applications.

  - [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) <img src="https://img.shields.io/github/stars/thepowersgang/rust_os?style=social"/> : An OS kernel written in rust. Non POSIX.

  - [MOROS](https://github.com/vinc/moros) <img src="https://img.shields.io/github/stars/vinc/moros?style=social"/> : MOROS: Obscure Rust Operating System 🦉



- ## Robot Operating System

  - [micro-ROS for Arduino](https://github.com/micro-ROS/micro_ros_arduino) <img src="https://img.shields.io/github/stars/micro-ROS/micro_ros_arduino?style=social"/> : micro-ROS library for Arduino. 

  - [openrr](https://github.com/openrr/openrr) <img src="https://img.shields.io/github/stars/openrr/openrr?style=social"/> : OpenRR (pronounced like "opener") is Open Rust Robotics platform.

  - [erdos](https://github.com/erdos-project/erdos) <img src="https://img.shields.io/github/stars/erdos-project/erdos?style=social"/> : Dataflow system for building self-driving car and robotics applications. 

  - [rosrust](https://github.com/adnanademovic/rosrust) <img src="https://img.shields.io/github/stars/adnanademovic/rosrust?style=social"/> : rosrust is a pure Rust implementation of a [ROS](https://www.ros.org/) client library.

  - [ros2_rust](https://github.com/ros2-rust/ros2_rust) <img src="https://img.shields.io/github/stars/ros2-rust/ros2_rust?style=social"/> : Rust bindings for ROS2.

  - [r2r](https://github.com/sequenceplanner/r2r) <img src="https://img.shields.io/github/stars/sequenceplanner/r2r?style=social"/> : R2R - Easy to use, runtime-agnostic, async rust bindings for ROS2.

  - [rclrust](https://github.com/rclrust/rclrust) <img src="https://img.shields.io/github/stars/rclrust/rclrust?style=social"/> : This is yet another ROS2 client library written in Rust.

  - [RustDDS](https://github.com/jhelovuo/RustDDS) <img src="https://img.shields.io/github/stars/jhelovuo/RustDDS?style=social"/> : [RustDDS](https://atostek.com/en/products/rustdds/) is a pure Rust implementation of [Data Distribution Service](https://www.omg.org/spec/DDS/), developed by [Atostek Oy](https://atostek.com/en/).

  - [rosbag-rs](https://github.com/SkoltechRobotics/rosbag-rs) <img src="https://img.shields.io/github/stars/SkoltechRobotics/rosbag-rs?style=social"/> : A pure Rust crate for reading ROS bag files.

  - [rustros_tf](https://github.com/arjo129/rustros_tf) <img src="https://img.shields.io/github/stars/arjo129/rustros_tf?style=social"/> : This is a rust port of the [ROS tf library](http://wiki.ros.org/tf).

  - [urdf-rs](https://github.com/openrr/urdf-rs) <img src="https://img.shields.io/github/stars/openrr/urdf-rs?style=social"/> : [URDF](http://wiki.ros.org/urdf) parser using [serde-xml-rs](https://github.com/RReverser/serde-xml-rs) for rust.

  - [urdf-viz](https://github.com/openrr/urdf-viz) <img src="https://img.shields.io/github/stars/openrr/urdf-viz?style=social"/> : visualize URDF/XACRO file, URDF Viewer works on Windows/MacOS/Linux.

  - [ros-nalgebra](https://github.com/openrr/ros-nalgebra) <img src="https://img.shields.io/github/stars/openrr/ros-nalgebra?style=social"/> : Generate code to convert geometry_msgs into nalgebra structs, for [rosrust](https://github.com/adnanademovic/rosrust).

  - [strawlab/opencv-ros-camera](https://github.com/strawlab/opencv-ros-camera) <img src="https://img.shields.io/github/stars/strawlab/opencv-ros-camera?style=social"/> : Geometric models of OpenCV/ROS cameras for photogrammetry.

  - [luickk/MinimalRoboticsPlatform](https://github.com/luickk/MinimalRoboticsPlatform/tree/rust_code) <img src="https://img.shields.io/github/stars/luickk/MinimalRoboticsPlatform?style=social"/> : MRP is a minimal microkernel that supports the most fundamental robotic domains. It's thought for highly integrated robotics development. 



- ## FFI Bindings 

  - [PyO3](https://github.com/PyO3/pyo3) <img src="https://img.shields.io/github/stars/PyO3/pyo3?style=social"/> : Rust bindings for the Python interpreter.

  - [C2Rust](https://github.com/immunant/c2rust) <img src="https://img.shields.io/github/stars/immunant/c2rust?style=social"/> : C2Rust helps you migrate C99-compliant code to Rust.

  - [Autocxx](https://github.com/google/autocxx) <img src="https://img.shields.io/github/stars/google/autocxx?style=social"/> : Tool for safe ergonomic Rust/C++ interop driven from existing C++ headers.

  - [bindgen](https://github.com/rust-lang/rust-bindgen) <img src="https://img.shields.io/github/stars/rust-lang/rust-bindgen?style=social"/> : Automatically generates Rust FFI bindings to C (and some C++) libraries. 

  - [cxx](https://github.com/dtolnay/cxx) <img src="https://img.shields.io/github/stars/dtolnay/cxx?style=social"/> : Safe interop between Rust and C++.

  - [Diplomat](https://github.com/rust-diplomat/diplomat) <img src="https://img.shields.io/github/stars/rust-diplomat/diplomat?style=social"/> : Experimental Rust tool for generating FFI definitions allowing many other languages to call Rust code.

  - [zig2rs](https://github.com/natanalt/zig2rs) <img src="https://img.shields.io/github/stars/natanalt/zig2rs?style=social"/> : use zig code in rust - a medium effort shitpost.


- ## GPU Integration 

  - [wgpu](https://github.com/gfx-rs/wgpu) <img src="https://img.shields.io/github/stars/gfx-rs/wgpu?style=social"/> : Safe and portable GPU abstraction in Rust, implementing WebGPU API. https://wgpu.rs/

  - [rust-gpu](https://github.com/EmbarkStudios/rust-gpu) <img src="https://img.shields.io/github/stars/EmbarkStudios/rust-gpu?style=social"/> : 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧 

  - [Rust-CUDA](https://github.com/Rust-GPU/Rust-CUDA) <img src="https://img.shields.io/github/stars/Rust-GPU/Rust-CUDA?style=social"/> : Ecosystem of libraries and tools for writing and executing fast GPU code fully in Rust. 

  - [Vulkano](https://github.com/vulkano-rs/vulkano) <img src="https://img.shields.io/github/stars/vulkano-rs/vulkano?style=social"/> : Safe and rich Rust wrapper around the Vulkan API.

  - [Ash](https://github.com/ash-rs/ash) <img src="https://img.shields.io/github/stars/ash-rs/ash?style=social"/> : Vulkan bindings for Rust.

  - [arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) <img src="https://img.shields.io/github/stars/arrayfire/arrayfire-rust?style=social"/> : Rust wrapper for [ArrayFire](https://github.com/arrayfire/arrayfire). ArrayFire is a general-purpose tensor library that simplifies the process of software development for the parallel architectures found in CPUs, GPUs, and other hardware acceleration devices.

  - [ocl](https://github.com/cogciprocate/ocl) <img src="https://img.shields.io/github/stars/cogciprocate/ocl?style=social"/> : OpenCL for Rust.

  - [opencl3](https://github.com/kenba/opencl3) <img src="https://img.shields.io/github/stars/kenba/opencl3?style=social"/> : A Rust implementation of the Khronos [OpenCL 3.0](https://registry.khronos.org/OpenCL/) API. 




- ## Linear Algebra

  - [ndarray](https://github.com/rust-ndarray/ndarray) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray?style=social"/> : The ndarray crate provides an n-dimensional container for general elements and for numerics.

  - [nalgebra](https://github.com/dimforge/nalgebra) <img src="https://img.shields.io/github/stars/dimforge/nalgebra?style=social"/> : Linear algebra library for the Rust programming language.

  - [elsuizo/static-math](https://github.com/elsuizo/static-math) <img src="https://img.shields.io/github/stars/elsuizo/static-math?style=social"/> : Safe and fast mathematical operations with static arrays in the Rust programming language.


- ## Optimization Algorithm 

  - [OpEn](https://github.com/alphaville/optimization-engine) <img src="https://img.shields.io/github/stars/alphaville/optimization-engine?style=social"/> : Optimization Engine (OpEn) is a solver for Fast & Accurate Embedded Optimization for next-generation Robotics and Autonomous Systems.

  - [mithi/rusty-genes](https://github.com/mithi/rusty-genes) <img src="https://img.shields.io/github/stars/mithi/rusty-genes?style=social"/> : Genetic algorithm implementation in Rust with animated visualizations in Python.


- ## Signal Processing

  - [hortovanyi/Unscented-Kalman-Filter-Rust](https://github.com/hortovanyi/Unscented-Kalman-Filter-Rust) <img src="https://img.shields.io/github/stars/hortovanyi/Unscented-Kalman-Filter-Rust?style=social"/> : UKF written in Rust based on the C++ UKF from the Udacity SD Car Nanodegree.

  - [spdes/kalman-rust](https://github.com/spdes/kalman-rust) <img src="https://img.shields.io/github/stars/spdes/kalman-rust?style=social"/> : A simple implementation of Kalman filter and RTS smoother in Rust (ndarray).

  - [wangxiaochuTHU/yakf](https://github.com/wangxiaochuTHU/yakf) <img src="https://img.shields.io/github/stars/wangxiaochuTHU/yakf?style=social"/> : Yet Another Kalman Filter Implementation. As well as Lie Theory (Lie group and algebra) on SE(3). [no_std] is supported by default. 

  - [MichaelMauderer/filter-rs](https://github.com/MichaelMauderer/filter-rs) <img src="https://img.shields.io/github/stars/MichaelMauderer/filter-rs?style=social"/> : Kalman filters and other optimal and non-optimal estimation filters in Rust.

  - [strawlab/adskalman-rs](https://github.com/strawlab/adskalman-rs) <img src="https://img.shields.io/github/stars/strawlab/adskalman-rs?style=social"/> : Kalman filter implementation in Rust.



- ## Sensor API

  - [shirok1/livox-rs](https://github.com/shirok1/livox-rs) <img src="https://img.shields.io/github/stars/shirok1/livox-rs?style=social"/> : Alternative Livox LiDAR library. 

  - [jerry73204/rust-lidar-utils](https://github.com/jerry73204/rust-lidar-utils) <img src="https://img.shields.io/github/stars/jerry73204/rust-lidar-utils?style=social"/> : Encode and decode Velodyne and Ouster lidar packets in Rust.




- ## Image Processing

  - [opencv-rust](https://github.com/twistedfall/opencv-rust) <img src="https://img.shields.io/github/stars/twistedfall/opencv-rust?style=social"/> : Rust bindings for OpenCV 3 & 4. 

  - [image-rs](https://github.com/image-rs/image) <img src="https://img.shields.io/github/stars/image-rs/image?style=social"/> : Encoding and decoding images in Rust.





- ## Localization and Mapping

  - [pekkaran/violet](https://github.com/pekkaran/violet) <img src="https://img.shields.io/github/stars/pekkaran/violet?style=social"/> : A toy stereo visual inertial odometry (VIO) system.

  - [mpizenberg/visual-odometry-rs](https://github.com/mpizenberg/visual-odometry-rs) <img src="https://img.shields.io/github/stars/mpizenberg/visual-odometry-rs?style=social"/> : Visual Odometry in Rust (vors).





- ## Path Planning

  - [rrt](https://github.com/openrr/rrt) <img src="https://img.shields.io/github/stars/openrr/rrt?style=social"/> : RRT (Rapidly-exploring Random Tree) library in Rust.

  - [gear](https://github.com/openrr/gear) <img src="https://img.shields.io/github/stars/openrr/gear?style=social"/> : Collision Avoidance Path Planning in Rust-lang.

  - [trajectory](https://github.com/openrr/trajectory) <img src="https://img.shields.io/github/stars/openrr/trajectory?style=social"/> : trajectory interpolation library for Rust and robotics.

  - [marcbone/s_curve](https://github.com/marcbone/s_curve) <img src="https://img.shields.io/github/stars/marcbone/s_curve?style=social"/> : S-Curve trajectory generator written in rust.

  - [Sollimann/bonsai](https://github.com/Sollimann/bonsai) <img src="https://img.shields.io/github/stars/Sollimann/bonsai?style=social"/> : Rust implementation of behavior trees. 




- ## Motion Control

  - [k](https://github.com/openrr/k) <img src="https://img.shields.io/github/stars/openrr/k?style=social"/> : k: Kinematics library for rust-lang.

  - [braincore/pid-rs](https://github.com/braincore/pid-rs) <img src="https://img.shields.io/github/stars/braincore/pid-rs?style=social"/> : A PID controller for Rust projects. 



- ## Machine Learning

  - [tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch.

  - [Linfa](https://github.com/rust-ml/linfa) <img src="https://img.shields.io/github/stars/rust-ml/linfa?style=social"/> : A Rust machine learning framework. 