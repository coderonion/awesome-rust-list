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
  - [Hardware Description Language](#hardware-description-language)
  - [FFI Bindings](#ffi-bindings)
  - [GPU Integration](#gpu-integration)  
  - [Shared Memory](#shared-memory) 
  - [Remote Desktop](#remote-desktop) 
  - [Scientific Computation](#scientific-computation)
    - [Linear Algebra](#linear-algebra)
    - [Lie Groups](#lie-groups)
    - [Data Analysis and Visualization](#data-analysis-and-visualization)
    - [Optimization Algorithm](#optimization-algorithm)
  - [Signal Processing](#signal-processing)
  - [Image Processing](#image-processing)
  - [Sensor API](#sensor-api)
  - [Localization and Mapping](#localization-and-mapping)
  - [Path Planning](#path-planning)
  - [Motion Control](#motion-control)
  - [Machine Learning](#machine-learning)
    - [Framework](#framework)
    - [Large Language Model](#large-language-model)
    - [Object Detection](#object-detection)
  - [Web Framework](#web-framework)
  - [GUI](#gui)

## Summary

  - ### Official Rust

    - [Rust](https://github.com/rust-lang/rust) <img src="https://img.shields.io/github/stars/rust-lang/rust?style=social"/> : The Rust Programming Language. Empowering everyone to build reliable and efficient software. [www.rust-lang.org](www.rust-lang.org). [Rust Foundation](https://foundation.rust-lang.org/).

    - [crates.io](https://crates.io/) : The Rust community’s crate registry.

    - [Lib.rs](https://lib.rs/) : Fast, lightweight, opinionated, unofficial alternative to crates.io.


  - ### Learning Resources

    - [Rust Standard Library](https://doc.rust-lang.org/std/index.html) : The Rust Standard Library.

    - [rust-lang/reference](https://github.com/rust-lang/reference) <img src="https://img.shields.io/github/stars/rust-lang/reference?style=social"/> : [The Rust Reference](https://doc.rust-lang.org/reference/).

    - [rust-lang/book](https://github.com/rust-lang/book) <img src="https://img.shields.io/github/stars/rust-lang/book?style=social"/> : [The Rust Programming Language](https://doc.rust-lang.org/stable/book/).

    - [Unsafe Code Guidelines Reference](https://rust-lang.github.io/unsafe-code-guidelines/) : Rust's Unsafe Code Guidelines Reference.

    - [rust-lang/rust-by-example](https://github.com/rust-lang/rust-by-example) <img src="https://img.shields.io/github/stars/rust-lang/rust-by-example?style=social"/> : [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/).

    - [rust-lang/rustlings](https://github.com/rust-lang/rustlings) <img src="https://img.shields.io/github/stars/rust-lang/rustlings?style=social"/> : 🦀 Small exercises to get you used to reading and writing Rust code!

    - [lborb/book](https://github.com/lborb/book) <img src="https://img.shields.io/github/stars/lborb/book?style=social"/> : [The Little Book of Rust Books](https://lborb.github.io/book/title-page.html).

    - [rust-unofficial/too-many-lists](https://github.com/rust-unofficial/too-many-lists) <img src="https://img.shields.io/github/stars/rust-unofficial/too-many-lists?style=social"/> : [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html).

    - [Rust文档网](https://rustwiki.org/) : Rust 官方文档中文教程。

    - [rust-lang-cn/reference-cn](https://github.com/rust-lang-cn/reference-cn) <img src="https://img.shields.io/github/stars/rust-lang-cn/reference-cn?style=social"/> : [Rust 参考手册 中文版](https://rustwiki.org/zh-CN/reference/)。

    - [Rust程序设计语言](https://kaisery.github.io/trpl-zh-cn/) : Rust 程序设计语言 简体中文版。

    - [sunface/rust-course](https://github.com/sunface/rust-course) <img src="https://img.shields.io/github/stars/sunface/rust-course?style=social"/> : [Rust语言圣经](https://course.rs/about-book.html)。

    - [rust-lang-cn/rust-by-example-cn](https://github.com/rust-lang-cn/rust-by-example-cn) <img src="https://img.shields.io/github/stars/rust-lang-cn/rust-by-example-cn?style=social"/> : [通过例子学Rust](https://rustwiki.org/zh-CN/rust-by-example/)。

    - [sunface/rust-by-practice](https://github.com/sunface/rust-by-practice) <img src="https://img.shields.io/github/stars/sunface/rust-by-practice?style=social"/> : [Rust By Practice(Rust语言实战)](https://zh.practice.rs/why-exercise.html)。

    - [rust-lang-cn/nomicon-zh-Hans](https://github.com/rust-lang-cn/nomicon-zh-Hans) <img src="https://img.shields.io/github/stars/rust-lang-cn/nomicon-zh-Hans?style=social"/> : [Rust 秘典（死灵书）](https://nomicon.purewhite.io/)。

    - [MacroKata](https://tfpk.github.io/macrokata/) : Welcome to MacroKata, a set of exercises which you can use to learn how to write macros in Rust. 

    - [veykril/tlborm](https://github.com/veykril/tlborm/) <img src="https://img.shields.io/github/stars/veykril/tlborm?style=social"/> : [The Little Book of Rust Macros](https://veykril.github.io/tlborm/). [Rust 宏小册](https://zjp-cn.github.io/tlborm/)。

    - [Warrenren/inside-rust-std-library](https://github.com/Warrenren/inside-rust-std-library) <img src="https://img.shields.io/github/stars/Warrenren/inside-rust-std-library?style=social"/> : 本书主要对RUST的标准库代码进行分析，并试图给出RUST标准库代码的分析脉络。This project try to give a venation of how reading the RUST standard library source code.

    - [rustlang-cn/rust-algos](https://github.com/rustlang-cn/rust-algos) <img src="https://img.shields.io/github/stars/rustlang-cn/rust-algos?style=social"/> : Rust算法题解，用Rust语言实现常见的算法和数据结构，以及leetcode题解。

    - [QMHTMY/RustBook](https://github.com/QMHTMY/RustBook) <img src="https://img.shields.io/github/stars/QMHTMY/RustBook?style=social"/> : A book about Rust Data Structures and Algorithms.

    - [pretzelhammer/rust-blog](https://github.com/pretzelhammer/rust-blog/blob/master/posts/translations/zh-hans/common-rust-lifetime-misconceptions.md) <img src="https://img.shields.io/github/stars/pretzelhammer/rust-blog?style=social"/> : Rust 中常见的有关生命周期的误解。

    - [fadeevab/design-patterns-rust](https://github.com/fadeevab/design-patterns-rust) <img src="https://img.shields.io/github/stars/fadeevab/design-patterns-rust?style=social"/> : Rust examples for all 23 classic GoF design patterns, and even a little more.

    - [lpxxn/rust-design-pattern](https://github.com/lpxxn/rust-design-pattern) <img src="https://img.shields.io/github/stars/lpxxn/rust-design-pattern?style=social"/> : Rust Design Patterns.



  - ### Awesome List

    - [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) <img src="https://img.shields.io/github/stars/rust-embedded/awesome-embedded-rust?style=social"/> : Curated list of resources for Embedded and Low-level development in the Rust programming language.

    - [robotics-rs/robotics.rs](https://github.com/robotics-rs/robotics.rs) <img src="https://img.shields.io/github/stars/robotics-rs/robotics.rs?style=social"/> : List of (awesome) Rust libraries for Robotics. 


  - ### Code Overview

    - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR. 




## Embedded Development

  - [stm32-rs](https://github.com/stm32-rs) : Community Rust support projects for STM32 microcontrollers.

  - [rust-embedded](https://github.com/rust-embedded) : Enabling usage of Rust on Embedded Platforms (Embedded Linux / RTOS / Bare Metal).



## Universal Operating System

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


## Robot Operating System

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




## Hardware Description Language

  - [dalance/veryl](https://github.com/dalance/veryl) <img src="https://img.shields.io/github/stars/dalance/veryl?style=social"/> : Veryl: A Modern Hardware Description Language.



## FFI Bindings 

  - [PyO3](https://github.com/PyO3/pyo3) <img src="https://img.shields.io/github/stars/PyO3/pyo3?style=social"/> : Rust bindings for the Python interpreter.

  - [bindgen](https://github.com/rust-lang/rust-bindgen) <img src="https://img.shields.io/github/stars/rust-lang/rust-bindgen?style=social"/> : Automatically generates Rust FFI bindings to C (and some C++) libraries. 

  - [cxx](https://github.com/dtolnay/cxx) <img src="https://img.shields.io/github/stars/dtolnay/cxx?style=social"/> : Safe interop between Rust and C++.

  - [Autocxx](https://github.com/google/autocxx) <img src="https://img.shields.io/github/stars/google/autocxx?style=social"/> : Tool for safe ergonomic Rust/C++ interop driven from existing C++ headers.

  - [C2Rust](https://github.com/immunant/c2rust) <img src="https://img.shields.io/github/stars/immunant/c2rust?style=social"/> : C2Rust helps you migrate C99-compliant code to Rust.

  - [embed-c](https://github.com/zdimension/embed-c) <img src="https://img.shields.io/github/stars/zdimension/embed-c?style=social"/> : Embed C code at compile time inside Rust using C2Rust.

  - [rust-cpp](https://github.com/mystor/rust-cpp) <img src="https://img.shields.io/github/stars/mystor/rust-cpp?style=social"/> : Embed C++ directly inside your rust code! 

  - [Diplomat](https://github.com/rust-diplomat/diplomat) <img src="https://img.shields.io/github/stars/rust-diplomat/diplomat?style=social"/> : Experimental Rust tool for generating FFI definitions allowing many other languages to call Rust code.

  - [natanalt/zig2rs](https://github.com/natanalt/zig2rs) <img src="https://img.shields.io/github/stars/natanalt/zig2rs?style=social"/> : use zig code in rust - a medium effort shitpost.

  - [emilHof/zigc](https://github.com/emilHof/zigc) <img src="https://img.shields.io/github/stars/emilHof/zigc?style=social"/> : A tool for compiling and linking Zig libraries to Rust projects. 

  - [ogxd/ffidji](https://github.com/ogxd/ffidji) <img src="https://img.shields.io/github/stars/ogxd/ffidji?style=social"/> : 🐶 FFIDJI is a tool to automatically generate bindings between languages, like calling Rust code from C# for instance.

  - [Deukhoofd/csharp_binder](https://github.com/Deukhoofd/csharp_binder) <img src="https://img.shields.io/github/stars/Deukhoofd/csharp_binder?style=social"/> : A simple library to generate C# bindings for a Rust foreign function interface (FFI).

  - [toolness/csharpbindgen](https://github.com/toolness/csharpbindgen) <img src="https://img.shields.io/github/stars/toolness/csharpbindgen?style=social"/> : A Rust library for generating C# bindings from Rust code.




## GPU Integration 

  - [wgpu](https://github.com/gfx-rs/wgpu) <img src="https://img.shields.io/github/stars/gfx-rs/wgpu?style=social"/> : Safe and portable GPU abstraction in Rust, implementing WebGPU API. https://wgpu.rs/

  - [rust-gpu](https://github.com/EmbarkStudios/rust-gpu) <img src="https://img.shields.io/github/stars/EmbarkStudios/rust-gpu?style=social"/> : 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧 

  - [Rust-CUDA](https://github.com/Rust-GPU/Rust-CUDA) <img src="https://img.shields.io/github/stars/Rust-GPU/Rust-CUDA?style=social"/> : Ecosystem of libraries and tools for writing and executing fast GPU code fully in Rust. 

  - [cudarc](https://github.com/coreylowman/cudarc) <img src="https://img.shields.io/github/stars/coreylowman/cudarc?style=social"/> : cudarc: minimal and safe api over the cuda toolkit.

  - [Vulkano](https://github.com/vulkano-rs/vulkano) <img src="https://img.shields.io/github/stars/vulkano-rs/vulkano?style=social"/> : Safe and rich Rust wrapper around the Vulkan API.

  - [Ash](https://github.com/ash-rs/ash) <img src="https://img.shields.io/github/stars/ash-rs/ash?style=social"/> : Vulkan bindings for Rust.

  - [arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) <img src="https://img.shields.io/github/stars/arrayfire/arrayfire-rust?style=social"/> : Rust wrapper for [ArrayFire](https://github.com/arrayfire/arrayfire). ArrayFire is a general-purpose tensor library that simplifies the process of software development for the parallel architectures found in CPUs, GPUs, and other hardware acceleration devices.

  - [ocl](https://github.com/cogciprocate/ocl) <img src="https://img.shields.io/github/stars/cogciprocate/ocl?style=social"/> : OpenCL for Rust.

  - [opencl3](https://github.com/kenba/opencl3) <img src="https://img.shields.io/github/stars/kenba/opencl3?style=social"/> : A Rust implementation of the Khronos [OpenCL 3.0](https://registry.khronos.org/OpenCL/) API. 



## Shared Memory 

  - [elast0ny/shared_memory](https://github.com/elast0ny/shared_memory) <img src="https://img.shields.io/github/stars/elast0ny/shared_memory?style=social"/> : A Rust wrapper around native shared memory for Linux and Windows.


## Remote Desktop

  - [RustDesk](https://github.com/rustdesk/rustdesk) <img src="https://img.shields.io/github/stars/rustdesk/rustdesk?style=social"/> : Virtual / remote desktop infrastructure for everyone! Open source TeamViewer / Citrix alternative. rustdesk.com.




## Scientific Computation

  - ### Linear Algebra

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

  - ### Lie Groups

    - [sophus-rs](https://github.com/strasdat/sophus-rs) <img src="https://img.shields.io/github/stars/strasdat/sophus-rs?style=social"/> : Rust bindings for the C++ implementation of Lie Groups using Eigen.

  - ### Data Analysis and Visualization

    - [Polars](https://github.com/pola-rs/polars) <img src="https://img.shields.io/github/stars/pola-rs/polars?style=social"/> : Fast multi-threaded, hybrid-out-of-core DataFrame library in Rust | Python | Node.js.

    - [Plotters](https://github.com/plotters-rs/plotters) <img src="https://img.shields.io/github/stars/plotters-rs/plotters?style=social"/> : A rust drawing library for high quality data plotting for both WASM and native, statically and realtimely 🦀 📈🚀


  - ### Optimization Algorithm 

    - [OpEn](https://github.com/alphaville/optimization-engine) <img src="https://img.shields.io/github/stars/alphaville/optimization-engine?style=social"/> : Optimization Engine (OpEn) is a solver for Fast & Accurate Embedded Optimization for next-generation Robotics and Autonomous Systems.

    - [mithi/rusty-genes](https://github.com/mithi/rusty-genes) <img src="https://img.shields.io/github/stars/mithi/rusty-genes?style=social"/> : Genetic algorithm implementation in Rust with animated visualizations in Python.



## Signal Processing

  - [strawlab/adskalman-rs](https://github.com/strawlab/adskalman-rs) <img src="https://img.shields.io/github/stars/strawlab/adskalman-rs?style=social"/> : Kalman filter implementation in Rust.

  - [nravic/kalmanrs](https://github.com/nravic/kalmanrs) <img src="https://img.shields.io/github/stars/nravic/kalmanrs?style=social"/> : A (yet to be) comprehensive Kalman Filter library in Rust.

  - [spdes/kalman-rust](https://github.com/spdes/kalman-rust) <img src="https://img.shields.io/github/stars/spdes/kalman-rust?style=social"/> : A simple implementation of Kalman filter and RTS smoother in Rust (ndarray).

  - [hortovanyi/Unscented-Kalman-Filter-Rust](https://github.com/hortovanyi/Unscented-Kalman-Filter-Rust) <img src="https://img.shields.io/github/stars/hortovanyi/Unscented-Kalman-Filter-Rust?style=social"/> : UKF written in Rust based on the C++ UKF from the Udacity SD Car Nanodegree.

  - [wangxiaochuTHU/yakf](https://github.com/wangxiaochuTHU/yakf) <img src="https://img.shields.io/github/stars/wangxiaochuTHU/yakf?style=social"/> : Yet Another Kalman Filter Implementation. As well as Lie Theory (Lie group and algebra) on SE(3). [no_std] is supported by default. 

  - [MichaelMauderer/filter-rs](https://github.com/MichaelMauderer/filter-rs) <img src="https://img.shields.io/github/stars/MichaelMauderer/filter-rs?style=social"/> : Kalman filters and other optimal and non-optimal estimation filters in Rust.


## Image Processing

  - [opencv-rust](https://github.com/twistedfall/opencv-rust) <img src="https://img.shields.io/github/stars/twistedfall/opencv-rust?style=social"/> : Rust bindings for OpenCV 3 & 4. 

  - [image-rs](https://github.com/image-rs/image) <img src="https://img.shields.io/github/stars/image-rs/image?style=social"/> : Encoding and decoding images in Rust.

  - [rust-ffmpeg](https://github.com/zmwangx/rust-ffmpeg) <img src="https://img.shields.io/github/stars/zmwangx/rust-ffmpeg?style=social"/> : Safe FFmpeg wrapper.

  - [Simp](https://github.com/Kl4rry/simp) <img src="https://img.shields.io/github/stars/Kl4rry/simp?style=social"/> : 🖼️ Simp is a fast and simple GPU-accelerated image manipulation program. 



## Sensor API

  - [shirok1/livox-rs](https://github.com/shirok1/livox-rs) <img src="https://img.shields.io/github/stars/shirok1/livox-rs?style=social"/> : Alternative Livox LiDAR library. 

  - [jerry73204/rust-lidar-utils](https://github.com/jerry73204/rust-lidar-utils) <img src="https://img.shields.io/github/stars/jerry73204/rust-lidar-utils?style=social"/> : Encode and decode Velodyne and Ouster lidar packets in Rust.


## Localization and Mapping

  - [pekkaran/violet](https://github.com/pekkaran/violet) <img src="https://img.shields.io/github/stars/pekkaran/violet?style=social"/> : A toy stereo visual inertial odometry (VIO) system.

  - [mpizenberg/visual-odometry-rs](https://github.com/mpizenberg/visual-odometry-rs) <img src="https://img.shields.io/github/stars/mpizenberg/visual-odometry-rs?style=social"/> : Visual Odometry in Rust (vors).



## Path Planning

  - [rrt](https://github.com/openrr/rrt) <img src="https://img.shields.io/github/stars/openrr/rrt?style=social"/> : RRT (Rapidly-exploring Random Tree) library in Rust.

  - [gear](https://github.com/openrr/gear) <img src="https://img.shields.io/github/stars/openrr/gear?style=social"/> : Collision Avoidance Path Planning in Rust-lang.

  - [trajectory](https://github.com/openrr/trajectory) <img src="https://img.shields.io/github/stars/openrr/trajectory?style=social"/> : trajectory interpolation library for Rust and robotics.

  - [marcbone/s_curve](https://github.com/marcbone/s_curve) <img src="https://img.shields.io/github/stars/marcbone/s_curve?style=social"/> : S-Curve trajectory generator written in rust.

  - [Sollimann/bonsai](https://github.com/Sollimann/bonsai) <img src="https://img.shields.io/github/stars/Sollimann/bonsai?style=social"/> : Rust implementation of behavior trees. 




## Motion Control

  - [k](https://github.com/openrr/k) <img src="https://img.shields.io/github/stars/openrr/k?style=social"/> : k: Kinematics library for rust-lang.

  - [braincore/pid-rs](https://github.com/braincore/pid-rs) <img src="https://img.shields.io/github/stars/braincore/pid-rs?style=social"/> : A PID controller for Rust projects. 

  - [bohonghuang/rov-host](https://github.com/bohonghuang/rov-host) <img src="https://img.shields.io/github/stars/bohonghuang/rov-host?style=social"/> : A cross-platform, high-performance underwater robot controll program written in Rust. 




## Machine Learning

  - ### Framework

    - [tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch. 

    - [dfdx](https://github.com/coreylowman/dfdx) <img src="https://img.shields.io/github/stars/coreylowman/dfdx?style=social"/> : Deep learning in Rust, with shape checked tensors and neural networks.

    - [Linfa](https://github.com/rust-ml/linfa) <img src="https://img.shields.io/github/stars/rust-ml/linfa?style=social"/> : A Rust machine learning framework. 

    - [sonos/tract](https://github.com/sonos/tract) <img src="https://img.shields.io/github/stars/sonos/tract?style=social"/> : Sonos' Neural Network inference engine. Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference

    - [webonnx/wonnx](https://github.com/webonnx/wonnx) <img src="https://img.shields.io/github/stars/webonnx/wonnx?style=social"/> : Wonnx is a GPU-accelerated ONNX inference run-time written 100% in Rust, ready for the web.

    - [pykeio/ort](https://github.com/pykeio/ort) <img src="https://img.shields.io/github/stars/pykeio/ort?style=social"/> : A Rust wrapper for ONNX Runtime.

    - [ptaxom/pnn](https://github.com/ptaxom/pnn) <img src="https://img.shields.io/github/stars/ptaxom/pnn?style=social"/> : pnn is Darknet compatible neural nets inference engine implemented in Rust.


  - ### Large Language Model

    - [lencx/ChatGPT](https://github.com/lencx/ChatGPT) <img src="https://img.shields.io/github/stars/lencx/ChatGPT?style=social"/> : 🔮 ChatGPT Desktop Application (Mac, Windows and Linux). [NoFWL](https://app.nofwl.com/).

    - [rustformers/llama-rs](https://github.com/rustformers/llama-rs) <img src="https://img.shields.io/github/stars/rustformers/llama-rs?style=social"/> : Run LLaMA inference on CPU, with Rust 🦀🚀🦙.

    - [sonnylazuardi/chat-ai-desktop](https://github.com/sonnylazuardi/chat-ai-desktop) <img src="https://img.shields.io/github/stars/sonnylazuardi/chat-ai-desktop?style=social"/> : Chat AI Desktop App. Unofficial ChatGPT desktop app for Mac & Windows menubar using Tauri & Rust.

    - [Noeda/rllama](https://github.com/Noeda/rllama) <img src="https://img.shields.io/github/stars/Noeda/rllama?style=social"/> : Rust+OpenCL+AVX2 implementation of LLaMA inference code.


  - ### Object Detection

    - [bencevans/rust-opencv-yolov5](https://github.com/bencevans/rust-opencv-yolov5) <img src="https://img.shields.io/github/stars/bencevans/rust-opencv-yolov5?style=social"/> : YOLOv5 Inference with ONNX & OpenCV in Rust.

    - [masc-it/yolov5-api-rust](https://github.com/masc-it/yolov5-api-rust) <img src="https://img.shields.io/github/stars/masc-it/yolov5-api-rust?style=social"/> : yolov5-api-rust.

    - [12101111/yolo-rs](https://github.com/12101111/yolo-rs) <img src="https://img.shields.io/github/stars/12101111/yolo-rs?style=social"/> : Yolov3 & Yolov4 with TVM and rust.

    - [TKGgunter/yolov4_tiny_rs](https://github.com/TKGgunter/yolov4_tiny_rs) <img src="https://img.shields.io/github/stars/TKGgunter/yolov4_tiny_rs?style=social"/> : A rust implementation of yolov4_tiny algorithm.

    - [flixstn/You-Only-Look-Once](https://github.com/flixstn/You-Only-Look-Once) <img src="https://img.shields.io/github/stars/flixstn/You-Only-Look-Once?style=social"/> : A Rust implementation of Yolo for object detection and tracking.

    - [lenna-project/yolo-plugin](https://github.com/lenna-project/yolo-plugin) <img src="https://img.shields.io/github/stars/lenna-project/yolo-plugin?style=social"/> : Yolo Object Detection Plugin for Lenna.

    - [gsuyemoto/yolo-rust](https://github.com/gsuyemoto/yolo-rust) <img src="https://img.shields.io/github/stars/gsuyemoto/yolo-rust?style=social"/> : Run YOLO computer vision model using Rust and OpenCV and/or Torch.

    - [laclouis5/globox-rs](https://github.com/laclouis5/globox-rs) <img src="https://img.shields.io/github/stars/laclouis5/globox-rs?style=social"/> : Object detection toolbox for parsing, converting and evaluating bounding box annotations.


## Web Framework

  - [Axum](https://github.com/tokio-rs/axum) <img src="https://img.shields.io/github/stars/tokio-rs/axum?style=social"/> : Ergonomic and modular web framework built with Tokio, Tower, and Hyper.

  - [Salvo](https://github.com/salvo-rs/salvo) <img src="https://img.shields.io/github/stars/salvo-rs/salvo?style=social"/> : [Salvo](https://salvo.rs/) is a powerful and simplest web server framework in Rust world.

  - [Yew](https://github.com/yewstack/yew) <img src="https://img.shields.io/github/stars/yewstack/yew?style=social"/> : Rust / Wasm framework for building client web apps. yew.rs.



## GUI

  - [Tauri](https://github.com/tauri-apps/tauri) <img src="https://img.shields.io/github/stars/tauri-apps/tauri?style=social"/> : Tauri is a framework for building tiny, blazingly fast binaries for all major desktop platforms. Developers can integrate any front-end framework that compiles to HTML, JS and CSS for building their user interface. The backend of the application is a rust-sourced binary with an API that the front-end can interact with.

  - [Pake](https://github.com/tw93/Pake) <img src="https://img.shields.io/github/stars/tw93/Pake?style=social"/> : 🤱🏻 Turn any webpage into a desktop app with Rust. 🤱🏻 很简单的用 Rust 打包网页生成很小的桌面 App.

  - [Iced](https://github.com/iced-rs/iced) <img src="https://img.shields.io/github/stars/iced-rs/iced?style=social"/> : A cross-platform GUI library for Rust focused on simplicity and type-safety. Inspired by [Elm](https://elm-lang.org/).

  - [egui](https://github.com/emilk/egui) <img src="https://img.shields.io/github/stars/emilk/egui?style=social"/> : egui: an easy-to-use immediate mode GUI in Rust that runs on both web and native.

  - [Slint](https://github.com/slint-ui/slint) <img src="https://img.shields.io/github/stars/slint-ui/slint?style=social"/> : Slint is a toolkit to efficiently develop fluid graphical user interfaces for any display: embedded devices and desktop applications. 

  - [Xilem](https://github.com/linebender/xilem) <img src="https://img.shields.io/github/stars/linebender/xilem?style=social"/> : An experimental Rust architecture for reactive UI.

  - [Druid](https://github.com/linebender/druid) <img src="https://img.shields.io/github/stars/linebender/druid?style=social"/> : A data-first Rust-native UI toolkit.

  - [Dioxus](https://github.com/DioxusLabs/dioxus) <img src="https://img.shields.io/github/stars/DioxusLabs/dioxus?style=social"/> : Friendly React-like GUI library for desktop, web, mobile, and more.

  - [marek-g/rust-fui](https://github.com/marek-g/rust-fui) <img src="https://img.shields.io/github/stars/marek-g/rust-fui?style=social"/> : MVVM Rust UI Framework Library.

  - [KDAB/cxx-qt](https://github.com/KDAB/cxx-qt) <img src="https://img.shields.io/github/stars/KDAB/cxx-qt?style=social"/> : Safe interop between Rust and Qt.

  - [KDE/rust-qt-binding-generator](https://github.com/KDE/rust-qt-binding-generator) <img src="https://img.shields.io/github/stars/KDE/rust-qt-binding-generator?style=social"/> : Generate bindings to use Rust code in Qt and QML.


