# Awesome-Rust-Robotics
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🔥🔥🔥 This repository lists some awesome public Rust projects for robotics.

## Contents
- [Awesome-Rust-Robotics](#awesome-rust-robotics)
  - [Summary](#summary)
    - [Official Rust](#official-rust)
    - [Learning Resources](#learning-resources)
    - [Awesome List](#awesome-list)
    - [Code Overview](#code-overview)
  - [Embedded Development](#embedded-development)
  - [Universal Operating System](#universal-operating-system)
  - [Robot Operating System](#robot-operating-system)
  - [FFI Bindings](#ffi-bindings)
  - [GPU Integration](#gpu-integration)  
  - [Linear Algebra](#linear-algebra)
  - [Lie Groups](#lie-groups)
  - [Data Visualization](#data-visualization)
  - [Optimization Algorithm](#optimization-algorithm)
  - [Signal Processing](#signal-processing)
  - [Sensor API](#sensor-api)
  - [Image Processing](#image-processing)
  - [Object Detection](#object-detection)
  - [Localization and Mapping](#localization-and-mapping)
  - [Path Planning](#path-planning)
  - [Motion Control](#motion-control)
  - [Machine-Learning](#machine-learning)




- ## Summary

  - ### Official Rust

    - [Rust](https://github.com/rust-lang/rust) <img src="https://img.shields.io/github/stars/rust-lang/rust?style=social"/> : The Rust Programming Language. Empowering everyone to build reliable and efficient software. [www.rust-lang.org](www.rust-lang.org). [Rust Foundation](https://foundation.rust-lang.org/)

    - [crates.io](https://crates.io/) : The Rust community’s crate registry.

    - [Lib.rs](https://lib.rs/) : Fast, lightweight, opinionated, unofficial alternative to crates.io.



  - ### Learning Resources

    - [Rust Book](https://doc.rust-lang.org/stable/book/) : The Rust Programming Language Book.

    - [Rust Standard Library](https://doc.rust-lang.org/std/index.html) : The Rust Standard Library.

    - [Rust Language Reference](https://doc.rust-lang.org/reference/) : The Rust Reference.

    - [Unsafe Code Guidelines Reference](https://rust-lang.github.io/unsafe-code-guidelines/) : Rust's Unsafe Code Guidelines Reference.

    - [rust-lang/rustlings](hhttps://github.com/rust-lang/rustlings) <img src="https://img.shields.io/github/stars/rust-lang/rustlings?style=social"/> : 🦀 Small exercises to get you used to reading and writing Rust code!

    - [Rust Books](https://lborb.github.io/book/title-page.html) : The Little Book of Rust Books.

    - [Rust文档网](https://rustwiki.org/) : Rust 官方文档中文教程。

    - [Rust参考手册](https://rustwiki.org/zh-CN/reference/) : Rust 参考手册 中文版。

    - [Rust程序设计语言](https://kaisery.github.io/trpl-zh-cn/) : Rust 程序设计语言 简体中文版。

    - [通过例子学Rust](https://rustwiki.org/zh-CN/rust-by-example/) : 通过例子学 Rust 中文版。

    - [Rust语言圣经](https://course.rs/about-book.html) : Rust语言圣经(Rust Course)。

    - [Rust语言实战](https://zh.practice.rs/why-exercise.html) : Rust By Practice( Rust 练习实践 )。

    - [Rust秘典](https://nomicon.purewhite.io/) : Rust 秘典（死灵书）。



  - ### Awesome List

    - [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) <img src="https://img.shields.io/github/stars/rust-embedded/awesome-embedded-rust?style=social"/> : Curated list of resources for Embedded and Low-level development in the Rust programming language.

    - [robotics-rs/robotics.rs](https://github.com/robotics-rs/robotics.rs) <img src="https://img.shields.io/github/stars/robotics-rs/robotics.rs?style=social"/> : List of (awesome) Rust libraries for Robotics. 


  - ### Code Overview

    - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR. 




- ## Embedded Development

  - [stm32-rs](https://github.com/stm32-rs) : Community Rust support projects for STM32 microcontrollers.

  - [rust-embedded](https://github.com/rust-embedded) : Enabling usage of Rust on Embedded Platforms (Embedded Linux / RTOS / Bare Metal).



- ## Universal Operating System

  - [BlogOS](https://github.com/phil-opp/blog_os) <img src="https://img.shields.io/github/stars/phil-opp/blog_os?style=social"/> : This repository contains the source code for the Writing an OS in Rust series at [os.phil-opp.com](https://os.phil-opp.com/).

  - [rust-raspberrypi-OS-tutorials](https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials) <img src="https://img.shields.io/github/stars/rust-embedded/rust-raspberrypi-OS-tutorials?style=social"/> :  📚 Learn to write an embedded OS in Rust 🦀 
  
  - [Tock](https://github.com/tock/tock) <img src="https://img.shields.io/github/stars/tock/tock?style=social"/> : A secure embedded operating system for microcontrollers.

  - [rCore-Tutorial-v3](https://github.com/chyyuu/os_kernel_lab) <img src="https://img.shields.io/github/stars/chyyuu/os_kernel_lab?style=social"/> : OS kernel labs based on Rust/C Lang & RISC-V 64/X86-32.

  - [rCore](https://github.com/rcore-os/rCore) <img src="https://img.shields.io/github/stars/rcore-os/rCore?style=social"/> : Rust version of THU uCore OS. Linux compatible. 

  - [zCore](https://github.com/rcore-os/zCore) <img src="https://img.shields.io/github/stars/rcore-os/zCore?style=social"/> : Reimplement Zircon microkernel in Rust. 

  - [RustSBI](https://github.com/rustsbi/rustsbi) <img src="https://img.shields.io/github/stars/rustsbi/rustsbi?style=social"/> : RISC-V Supervisor Binary Interface (RISC-V SBI) implementation library in Rust; runs on M or HS mode; good support for embedded Rust ecosystem. 

  - [writing-an-os-in-rust](https://github.com/rustcc/writing-an-os-in-rust) <img src="https://img.shields.io/github/stars/rustcc/writing-an-os-in-rust?style=social"/> : 《使用Rust编写操作系统》

  - [Theseus](https://github.com/theseus-os/Theseus) <img src="https://img.shields.io/github/stars/theseus-os/Theseus?style=social"/> : Theseus is a modern OS written from scratch in Rust that explores 𝐢𝐧𝐭𝐫𝐚𝐥𝐢𝐧𝐠𝐮𝐚𝐥 𝐝𝐞𝐬𝐢𝐠𝐧, novel OS structure, and state management.

  - [snarkOS](https://github.com/AleoHQ/snarkOS) <img src="https://img.shields.io/github/stars/AleoHQ/snarkOS?style=social"/> : A Decentralized Operating System for Zero-Knowledge Applications.

  - [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) <img src="https://img.shields.io/github/stars/thepowersgang/rust_os?style=social"/> : An OS kernel written in rust. Non POSIX.

  - [MOROS](https://github.com/vinc/moros) <img src="https://img.shields.io/github/stars/vinc/moros?style=social"/> : MOROS: Obscure Rust Operating System 🦉

  - [EuraliOS](https://github.com/bendudson/EuraliOS) <img src="https://img.shields.io/github/stars/bendudson/EuraliOS?style=social"/> : A hobby x86-64 operating system written in Rust.

  - [SIMDeez](https://github.com/arduano/simdeez) <img src="https://img.shields.io/github/stars/arduano/simdeez?style=social"/> : A library that abstracts over SIMD instruction sets, including ones with differing widths. SIMDeez is designed to allow you to write a function one time and produce SSE2, SSE41, and AVX2 versions of the function.


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

  - [cudarc](https://github.com/coreylowman/cudarc) <img src="https://img.shields.io/github/stars/coreylowman/cudarc?style=social"/> : cudarc: minimal and safe api over the cuda toolkit.


- ## Linear Algebra

  - [mathbench](https://github.com/bitshifter/mathbench-rs) <img src="https://img.shields.io/github/stars/bitshifter/mathbench-rs?style=social"/> : mathbench is a suite of unit tests and benchmarks comparing the output and performance of a number of different Rust linear algebra libraries for common game and graphics development tasks.

  - [ndarray](https://github.com/rust-ndarray/ndarray) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray?style=social"/> : The ndarray crate provides an n-dimensional container for general elements and for numerics.

  - [ndarray-linalg](https://github.com/rust-ndarray/ndarray-linalg) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray-linalg?style=social"/> : Linear algebra package for rust-ndarray using LAPACK binding.

  - [glam](https://github.com/bitshifter/glam-rs) <img src="https://img.shields.io/github/stars/bitshifter/glam-rs?style=social"/> : A simple and fast 3D math library for games and graphics.

  - [nalgebra](https://github.com/dimforge/nalgebra) <img src="https://img.shields.io/github/stars/dimforge/nalgebra?style=social"/> : Linear algebra library for the Rust programming language.

  - [rust-numpy](https://github.com/PyO3/rust-numpy) <img src="https://img.shields.io/github/stars/PyO3/rust-numpy?style=social"/> : PyO3-based Rust bindings of the NumPy C-API.

  - [cgmath](https://github.com/rustgd/cgmath) <img src="https://img.shields.io/github/stars/rustgd/cgmath?style=social"/> : A linear algebra and mathematics library for computer graphics.

  - [ultraviolet](https://github.com/fu5ha/ultraviolet) <img src="https://img.shields.io/github/stars/fu5ha/ultraviolet?style=social"/> : A wide linear algebra crate for games and graphics.

  - [vek](https://github.com/yoanlcq/vek) <img src="https://img.shields.io/github/stars/yoanlcq/vek?style=social"/> : Generic 2D-3D math swiss army knife for game engines, with SIMD support and focus on convenience. 

  - [static-math](https://github.com/elsuizo/static-math) <img src="https://img.shields.io/github/stars/elsuizo/static-math?style=social"/> : Safe and fast mathematical operations with static arrays in the Rust programming language.


- ## Lie Groups

  - [sophus-rs](https://github.com/strasdat/sophus-rs) <img src="https://img.shields.io/github/stars/strasdat/sophus-rs?style=social"/> : Rust bindings for the C++ implementation of Lie Groups using Eigen.


- ## Data Visualization

  - [Plotters](https://github.com/plotters-rs/plotters) <img src="https://img.shields.io/github/stars/plotters-rs/plotters?style=social"/> : A rust drawing library for high quality data plotting for both WASM and native, statically and realtimely 🦀 📈🚀


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

  - [rust-ffmpeg](https://github.com/zmwangx/rust-ffmpeg) <img src="https://img.shields.io/github/stars/zmwangx/rust-ffmpeg?style=social"/> : Safe FFmpeg wrapper.

  - [Simp](https://github.com/Kl4rry/simp) <img src="https://img.shields.io/github/stars/Kl4rry/simp?style=social"/> : 🖼️ Simp is a fast and simple GPU-accelerated image manipulation program. 



- ## Object Detection

    - [12101111/yolo-rs](https://github.com/12101111/yolo-rs) <img src="https://img.shields.io/github/stars/12101111/yolo-rs?style=social"/> : Yolov3 & Yolov4 with TVM and rust.

    - [TKGgunter/yolov4_tiny_rs](https://github.com/TKGgunter/yolov4_tiny_rs) <img src="https://img.shields.io/github/stars/TKGgunter/yolov4_tiny_rs?style=social"/> : A rust implementation of yolov4_tiny algorithm.

    - [flixstn/You-Only-Look-Once](https://github.com/flixstn/You-Only-Look-Once) <img src="https://img.shields.io/github/stars/flixstn/You-Only-Look-Once?style=social"/> : A Rust implementation of Yolo for object detection and tracking.

    - [lenna-project/yolo-plugin](https://github.com/lenna-project/yolo-plugin) <img src="https://img.shields.io/github/stars/lenna-project/yolo-plugin?style=social"/> : Yolo Object Detection Plugin for Lenna.

    - [masc-it/yolov5-api-rust](https://github.com/masc-it/yolov5-api-rust) <img src="https://img.shields.io/github/stars/masc-it/yolov5-api-rust?style=social"/> : yolov5-api-rust.

    - [gsuyemoto/yolo-rust](https://github.com/gsuyemoto/yolo-rust) <img src="https://img.shields.io/github/stars/gsuyemoto/yolo-rust?style=social"/> : Run YOLO computer vision model using Rust and OpenCV and/or Torch.

    - [laclouis5/globox-rs](https://github.com/laclouis5/globox-rs) <img src="https://img.shields.io/github/stars/laclouis5/globox-rs?style=social"/> : Object detection toolbox for parsing, converting and evaluating bounding box annotations.

    - [bencevans/rust-opencv-yolov5](https://github.com/bencevans/rust-opencv-yolov5) <img src="https://img.shields.io/github/stars/bencevans/rust-opencv-yolov5?style=social"/> : YOLOv5 Inference with ONNX & OpenCV in Rust.




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

  - [bohonghuang/rov-host](https://github.com/bohonghuang/rov-host) <img src="https://img.shields.io/github/stars/bohonghuang/rov-host?style=social"/> : A cross-platform, high-performance underwater robot controll program written in Rust. 


- ## Machine Learning

  - [lencx/ChatGPT](https://github.com/lencx/ChatGPT) <img src="https://img.shields.io/github/stars/lencx/ChatGPT?style=social"/> : 🔮 ChatGPT Desktop Application (Mac, Windows and Linux).

  - [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch. 

  - [dfdx](https://github.com/coreylowman/dfdx) <img src="https://img.shields.io/github/stars/coreylowman/dfdx?style=social"/> : Deep learning in Rust, with shape checked tensors and neural networks.

  - [Linfa](https://github.com/rust-ml/linfa) <img src="https://img.shields.io/github/stars/rust-ml/linfa?style=social"/> : A Rust machine learning framework. 

  - [sonos/tract](https://github.com/sonos/tract) <img src="https://img.shields.io/github/stars/sonos/tract?style=social"/> : Sonos' Neural Network inference engine. Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference

  - [webonnx/wonnx](https://github.com/webonnx/wonnx) <img src="https://img.shields.io/github/stars/webonnx/wonnx?style=social"/> : Wonnx is a GPU-accelerated ONNX inference run-time written 100% in Rust, ready for the web.

  - [ptaxom/pnn](https://github.com/ptaxom/pnn) <img src="https://img.shields.io/github/stars/ptaxom/pnn?style=social"/> : pnn is Darknet compatible neural nets inference engine implemented in Rust.