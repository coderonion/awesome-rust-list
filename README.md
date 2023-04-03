# Awesome-Rust-List
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🔥🔥🔥 This repository lists some awesome public Rust projects.

## Contents
- [Awesome-Rust-List](#awesome-rust-list)
  - [Summary](#summary)
    - [Official Rust](#official-rust)
    - [Learning Resources](#learning-resources)
    - [Awesome List](#awesome-list)
  - [Data Structure and Algorithm](#data-structure-and-algorithm)
  - [Design Pattern](#design-pattern)
  - [Asynchronous Runtime](#asynchronous-runtime)
  - [Embedded Development](#embedded-development)
  - [Universal Operating System](#universal-operating-system)
  - [Robot Operating System](#robot-operating-system)
  - [Hardware Description Language](#hardware-description-language)
  - [FFI Bindings](#ffi-bindings)
  - [GPU Computation](#gpu-computation) 
  - [Graphics Library](#graphics-library)  
  - [Shared Memory](#shared-memory) 
  - [Remote Desktop](#remote-desktop) 
  - [Date and Time](#date-and-time)
  - [Scientific Computation](#scientific-computation)
    - [Linear Algebra](#linear-algebra)
    - [Lie Groups](#lie-groups)
    - [Optimization Algorithm](#optimization-algorithm)
    - [Data Analysis and Visualization](#data-analysis-and-visualization)
  - [Sensor and Communication Interface](#sensor-and-communication-interface)
  - [Signal Processing](#signal-processing)
  - [Image and Video Processing](#image-and-video-processing)
  - [Localization and Mapping](#localization-and-mapping)
  - [Path Planning](#path-planning)
  - [Motion Control](#motion-control)
  - [Game Engine](#game-engine)
  - [Machine Learning](#machine-learning)
    - [ML Framework](#ml-framework)
    - [Large Language Model](#large-language-model)
    - [Object Detection](#object-detection)
  - [Web Framework](#web-framework)
  - [Web Crawler](#web-crawler)
  - [WebAssembly Runtime](#webAssembly-runtime)
  - [GUI](#gui)

## Summary

  - ### Official Rust

    - [Rust](https://github.com/rust-lang/rust) <img src="https://img.shields.io/github/stars/rust-lang/rust?style=social"/> : The Rust Programming Language. Empowering everyone to build reliable and efficient software. [www.rust-lang.org](www.rust-lang.org). [Rust Foundation](https://foundation.rust-lang.org/).

    - [crates.io](https://crates.io/) : The Rust community’s crate registry.

    - [Lib.rs](https://lib.rs/) : Fast, lightweight, opinionated, unofficial alternative to crates.io.

    - [Crate std](https://doc.rust-lang.org/std/index.html) : The Rust Standard Library.


  - ### Learning Resources

    - [rust-lang/reference](https://github.com/rust-lang/reference) <img src="https://img.shields.io/github/stars/rust-lang/reference?style=social"/> : [The Rust Reference](https://doc.rust-lang.org/reference/).

    - [rust-lang/book](https://github.com/rust-lang/book) <img src="https://img.shields.io/github/stars/rust-lang/book?style=social"/> : [The Rust Programming Language](https://doc.rust-lang.org/stable/book/).

    - [rust-lang/rust-by-example](https://github.com/rust-lang/rust-by-example) <img src="https://img.shields.io/github/stars/rust-lang/rust-by-example?style=social"/> : [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/).

    - [rust-lang/rustlings](https://github.com/rust-lang/rustlings) <img src="https://img.shields.io/github/stars/rust-lang/rustlings?style=social"/> : 🦀 Small exercises to get you used to reading and writing Rust code!

    - [Rust Language Cheat Sheet](https://github.com/ralfbiedert/cheats.rs/) <img src="https://img.shields.io/github/stars/ralfbiedert/cheats.rs?style=social"/> : [cheats.rs](https://cheats.rs/).

    - [Unsafe Code Guidelines Reference](https://rust-lang.github.io/unsafe-code-guidelines/) : Rust's Unsafe Code Guidelines Reference.

    - [lborb/book](https://github.com/lborb/book) <img src="https://img.shields.io/github/stars/lborb/book?style=social"/> : [The Little Book of Rust Books](https://lborb.github.io/book/title-page.html).

    - [ctjhoa/rust-learning](https://github.com/ctjhoa/rust-learning) <img src="https://img.shields.io/github/stars/ctjhoa/rust-learning?style=social"/> : A bunch of links to blog posts, articles, videos, etc for learning Rust.

    - [Rust文档网](https://rustwiki.org/) : Rust 官方文档中文教程。

    - [rust-boom/rust-boom](https://github.com/rust-boom/rust-boom) <img src="https://img.shields.io/github/stars/rust-boom/rust-boom?style=social"/> : [Rust Boom 💥](https://rust-boom.github.io/rust-boom/). Rust Boom 是一个仓主在学习使用 Rust 的时候，对 Rust 的一些难点的解决方法以及一些 Rust 开源的好玩的库、书籍、文章的整理，希望可以帮助更多的 Rust 初学者来翻过 Rust 这座大山。

    - [rust-lang-cn/reference-cn](https://github.com/rust-lang-cn/reference-cn) <img src="https://img.shields.io/github/stars/rust-lang-cn/reference-cn?style=social"/> : [Rust 参考手册 中文版](https://rustwiki.org/zh-CN/reference/)。

    - [Rust程序设计语言](https://kaisery.github.io/trpl-zh-cn/) : Rust 程序设计语言 简体中文版。

    - [sunface/rust-course](https://github.com/sunface/rust-course) <img src="https://img.shields.io/github/stars/sunface/rust-course?style=social"/> : [Rust语言圣经](https://course.rs/about-book.html)。

    - [rust-lang-cn/rust-by-example-cn](https://github.com/rust-lang-cn/rust-by-example-cn) <img src="https://img.shields.io/github/stars/rust-lang-cn/rust-by-example-cn?style=social"/> : [通过例子学Rust](https://rustwiki.org/zh-CN/rust-by-example/)。

    - [sunface/rust-by-practice](https://github.com/sunface/rust-by-practice) <img src="https://img.shields.io/github/stars/sunface/rust-by-practice?style=social"/> : [Rust By Practice(Rust语言实战)](https://zh.practice.rs/why-exercise.html)。

    - [rust-lang-cn/nomicon-zh-Hans](https://github.com/rust-lang-cn/nomicon-zh-Hans) <img src="https://img.shields.io/github/stars/rust-lang-cn/nomicon-zh-Hans?style=social"/> : [Rust 秘典（死灵书）](https://nomicon.purewhite.io/)。

    - [MacroKata](https://tfpk.github.io/macrokata/) : Welcome to MacroKata, a set of exercises which you can use to learn how to write macros in Rust. 

    - [veykril/tlborm](https://github.com/veykril/tlborm/) <img src="https://img.shields.io/github/stars/veykril/tlborm?style=social"/> : [The Little Book of Rust Macros](https://veykril.github.io/tlborm/). [Rust 宏小册](https://zjp-cn.github.io/tlborm/)。 

    - [tyrchen/geektime-rust](https://github.com/tyrchen/geektime-rust) <img src="https://img.shields.io/github/stars/tyrchen/geektime-rust?style=social"/> :  geektime-rust：我的极客时间 Rust 课程的代码仓库，随课程更新。

    - [Warrenren/inside-rust-std-library](https://github.com/Warrenren/inside-rust-std-library) <img src="https://img.shields.io/github/stars/Warrenren/inside-rust-std-library?style=social"/> : 本书主要对RUST的标准库代码进行分析，并试图给出RUST标准库代码的分析脉络。This project try to give a venation of how reading the RUST standard library source code.

    - [wtklbm/rust-library-i18n](https://github.com/wtklbm/rust-library-i18n) <img src="https://img.shields.io/github/stars/wtklbm/rust-library-i18n?style=social"/> :  Rust 核心库和标准库中文翻译，可作为 IDE 工具的智能提示，并生成本地 API 文档。

    - [pretzelhammer/rust-blog](https://github.com/pretzelhammer/rust-blog/blob/master/posts/translations/zh-hans/common-rust-lifetime-misconceptions.md) <img src="https://img.shields.io/github/stars/pretzelhammer/rust-blog?style=social"/> : Rust 中常见的有关生命周期的误解。

    - [johnthagen/min-sized-rust](https://github.com/johnthagen/min-sized-rust) <img src="https://img.shields.io/github/stars/johnthagen/min-sized-rust?style=social"/> :  🦀 How to minimize Rust binary size 📦 



  - ### Awesome List

    - [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust) <img src="https://img.shields.io/github/stars/rust-unofficial/awesome-rust?style=social"/> : A curated list of Rust code and resources. 

    - [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) <img src="https://img.shields.io/github/stars/rust-embedded/awesome-embedded-rust?style=social"/> : Curated list of resources for Embedded and Low-level development in the Rust programming language.

    - [TaKO8Ki/awesome-alternatives-in-rust](https://github.com/TaKO8Ki/awesome-alternatives-in-rust) <img src="https://img.shields.io/github/stars/TaKO8Ki/awesome-alternatives-in-rust?style=social"/> : A curated list of replacements for existing software written in Rust. 

    - [rust-in-blockchain/awesome-blockchain-rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust) <img src="https://img.shields.io/github/stars/rust-in-blockchain/awesome-blockchain-rust?style=social"/> : Collect libraries and packages about blockchain/cryptography in Rust. 

    - [jetli/awesome-yew](https://github.com/jetli/awesome-yew) <img src="https://img.shields.io/github/stars/jetli/awesome-yew?style=social"/> : 😎 A curated list of awesome things related to Yew / WebAssembly.

    - [vaaaaanquish/Awesome-Rust-MachineLearning](https://github.com/vaaaaanquish/Awesome-Rust-MachineLearning) <img src="https://img.shields.io/github/stars/vaaaaanquish/Awesome-Rust-MachineLearning?style=social"/> : This repository is a list of machine learning libraries written in Rust. It's a compilation of GitHub repositories, blogs, books, movies, discussions, papers, etc. 🦀

    - [awesome-rust-com/awesome-rust](https://github.com/awesome-rust-com/awesome-rust) <img src="https://img.shields.io/github/stars/awesome-rust-com/awesome-rust?style=social"/> :A curated list of awesome Rust frameworks, libraries and software. [awesome-rust](https://awesome-rust.com/)

    - [rust-cc/awesome-cryptography-rust](https://github.com/rust-cc/awesome-cryptography-rust) <img src="https://img.shields.io/github/stars/rust-cc/awesome-cryptography-rust?style=social"/> : Collect libraries and packages about cryptography in Rust. 

    - [ddotta/awesome-polars](https://github.com/ddotta/awesome-polars) <img src="https://img.shields.io/github/stars/ddotta/awesome-polars?style=social"/> : A curated list of [Polars](https://www.pola.rs/) talks, tools, examples & articles. Contributions welcome ! 

    - [ex0dus-0x/awesome-rust-security](https://github.com/ex0dus-0x/awesome-rust-security) <img src="https://img.shields.io/github/stars/ex0dus-0x/awesome-rust-security?style=social"/> : Curated list of awesome projects and resources related to Rust and computer security. 

    - [robotics-rs/robotics.rs](https://github.com/robotics-rs/robotics.rs) <img src="https://img.shields.io/github/stars/robotics-rs/robotics.rs?style=social"/> : List of (awesome) Rust libraries for Robotics. 

    - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR. 


## Data Structure and Algorithm 

  - [sjinzh/hello-algo-rust-zig](https://github.com/sjinzh/hello-algo-rust-zig) <img src="https://img.shields.io/github/stars/sjinzh/hello-algo-rust-zig?style=social"/> : Rust and Zig programming language codes for the famous public project 《Hello, Algorithm》|《 Hello，算法 》 about data structures and algorithms.

  - [EbTech/rust-algorithms](https://github.com/EbTech/rust-algorithms) <img src="https://img.shields.io/github/stars/EbTech/rust-algorithms?style=social"/> : Common data structures and algorithms in Rust. A collection of classic data structures and algorithms, emphasizing usability, beauty and clarity over full generality.

  - [rust-unofficial/too-many-lists](https://github.com/rust-unofficial/too-many-lists) <img src="https://img.shields.io/github/stars/rust-unofficial/too-many-lists?style=social"/> : [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html).

  - [rustlang-cn/rust-algos](https://github.com/rustlang-cn/rust-algos) <img src="https://img.shields.io/github/stars/rustlang-cn/rust-algos?style=social"/> : Rust算法题解，用Rust语言实现常见的算法和数据结构，以及leetcode题解。

  - [QMHTMY/RustBook](https://github.com/QMHTMY/RustBook) <img src="https://img.shields.io/github/stars/QMHTMY/RustBook?style=social"/> : A book about Rust Data Structures and Algorithms.

  - [matey-jack/dl-list-mini.fs](https://gist.github.com/matey-jack/3e19b6370c6f7036a9119b79a82098ca) : Simple doubly-linked list in safe Rust.  


## Design Pattern

  - [fadeevab/design-patterns-rust](https://github.com/fadeevab/design-patterns-rust) <img src="https://img.shields.io/github/stars/fadeevab/design-patterns-rust?style=social"/> : Rust examples for all 23 classic GoF design patterns, and even a little more.

  - [lpxxn/rust-design-pattern](https://github.com/lpxxn/rust-design-pattern) <img src="https://img.shields.io/github/stars/lpxxn/rust-design-pattern?style=social"/> : Rust Design Patterns.


## Asynchronous Runtime

  - [Tokio](https://github.com/tokio-rs/tokio) <img src="https://img.shields.io/github/stars/tokio-rs/tokio?style=social"/> : A runtime for writing reliable, asynchronous, and slim applications with the Rust programming language.


## Embedded Development

  - [stm32-rs](https://github.com/stm32-rs) : Community Rust support projects for STM32 microcontrollers.

  - [rust-embedded](https://github.com/rust-embedded) : Enabling usage of Rust on Embedded Platforms (Embedded Linux / RTOS / Bare Metal).



## Universal Operating System

  - [BlogOS](https://github.com/phil-opp/blog_os) <img src="https://img.shields.io/github/stars/phil-opp/blog_os?style=social"/> : This repository contains the source code for the Writing an OS in Rust series at [os.phil-opp.com](https://os.phil-opp.com/).

  - [rust-raspberrypi-OS-tutorials](https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials) <img src="https://img.shields.io/github/stars/rust-embedded/rust-raspberrypi-OS-tutorials?style=social"/> :  📚 Learn to write an embedded OS in Rust 🦀 
  
  - [Tock](https://github.com/tock/tock) <img src="https://img.shields.io/github/stars/tock/tock?style=social"/> : A secure embedded operating system for microcontrollers. [www.tockos.org](https://www.tockos.org/)

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

  - [yavkOS](https://github.com/yavko/yavkOS) <img src="https://img.shields.io/github/stars/yavko/yavkOS?style=social"/> : Operating system based off of blog_os, with the goal of running wasm modules as executables.


## Robot Operating System

  - [micro-ROS for Arduino](https://github.com/micro-ROS/micro_ros_arduino) <img src="https://img.shields.io/github/stars/micro-ROS/micro_ros_arduino?style=social"/> : micro-ROS library for Arduino. 

  - [openrr](https://github.com/openrr/openrr) <img src="https://img.shields.io/github/stars/openrr/openrr?style=social"/> : Open Rust Robotics. OpenRR (pronounced like "opener") is Open Rust Robotics platform.

  - [rosrust](https://github.com/adnanademovic/rosrust) <img src="https://img.shields.io/github/stars/adnanademovic/rosrust?style=social"/> : rosrust is a pure Rust implementation of a [ROS](https://www.ros.org/) client library.

  - [ros2_rust](https://github.com/ros2-rust/ros2_rust) <img src="https://img.shields.io/github/stars/ros2-rust/ros2_rust?style=social"/> : Rust bindings for ROS2.

  - [r2r](https://github.com/sequenceplanner/r2r) <img src="https://img.shields.io/github/stars/sequenceplanner/r2r?style=social"/> : R2R - Easy to use, runtime-agnostic, async rust bindings for ROS2.

  - [erdos](https://github.com/erdos-project/erdos) <img src="https://img.shields.io/github/stars/erdos-project/erdos?style=social"/> : Dataflow system for building self-driving car and robotics applications. 

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




## GPU Computation 

  - [rust-gpu](https://github.com/EmbarkStudios/rust-gpu) <img src="https://img.shields.io/github/stars/EmbarkStudios/rust-gpu?style=social"/> : 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧 [shader.rs](https://shader.rs/)  

  - [cudarc](https://github.com/coreylowman/cudarc) <img src="https://img.shields.io/github/stars/coreylowman/cudarc?style=social"/> : cudarc: minimal and safe api over the cuda toolkit.

  - [Rust-CUDA](https://github.com/Rust-GPU/Rust-CUDA) <img src="https://img.shields.io/github/stars/Rust-GPU/Rust-CUDA?style=social"/> : Ecosystem of libraries and tools for writing and executing fast GPU code fully in Rust. 

  - [Vulkano](https://github.com/vulkano-rs/vulkano) <img src="https://img.shields.io/github/stars/vulkano-rs/vulkano?style=social"/> : Safe and rich Rust wrapper around the Vulkan API.

  - [wgpu](https://github.com/gfx-rs/wgpu) <img src="https://img.shields.io/github/stars/gfx-rs/wgpu?style=social"/> : Safe and portable GPU abstraction in Rust, implementing WebGPU API. [wgpu.rs](https://wgpu.rs/)

  - [Ash](https://github.com/ash-rs/ash) <img src="https://img.shields.io/github/stars/ash-rs/ash?style=social"/> : Vulkan bindings for Rust.

  - [arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) <img src="https://img.shields.io/github/stars/arrayfire/arrayfire-rust?style=social"/> : Rust wrapper for [ArrayFire](https://github.com/arrayfire/arrayfire). ArrayFire is a general-purpose tensor library that simplifies the process of software development for the parallel architectures found in CPUs, GPUs, and other hardware acceleration devices.

  - [ocl](https://github.com/cogciprocate/ocl) <img src="https://img.shields.io/github/stars/cogciprocate/ocl?style=social"/> : OpenCL for Rust.

  - [opencl3](https://github.com/kenba/opencl3) <img src="https://img.shields.io/github/stars/kenba/opencl3?style=social"/> : A Rust implementation of the Khronos [OpenCL 3.0](https://registry.khronos.org/OpenCL/) API. 



## Graphics Library

  - [rust-skia/rust-skia](https://github.com/rust-skia/rust-skia) <img src="https://img.shields.io/github/stars/rust-skia/rust-skia?style=social"/> : Safe Rust bindings to the [Skia Graphics Library](https://skia.org/).

  - [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) <img src="https://img.shields.io/github/stars/gtk-rs/gtk4-rs?style=social"/> : Rust bindings of GTK 4. [gtk-rs.org/gtk4-rs/](https://gtk-rs.org/gtk4-rs/)

  - [gtk-rs/gtk3-rs](https://github.com/gtk-rs/gtk3-rs) <img src="https://img.shields.io/github/stars/gtk-rs/gtk3-rs?style=social"/> : Rust bindings for GTK 3. [gtk-rs.org](https://gtk-rs.org/)

  - [SabianF/rust_wgpu_3D_vision](https://github.com/SabianF/rust_wgpu_3D_vision) <img src="https://img.shields.io/github/stars/SabianF/rust_wgpu_3D_vision?style=social"/> : A program to simulate stereoscopic 4D vision, using a virtual 3D retina which is created by rapidly displaying all voxels at varying depths of a 3D volume.




## Shared Memory 

  - [elast0ny/shared_memory](https://github.com/elast0ny/shared_memory) <img src="https://img.shields.io/github/stars/elast0ny/shared_memory?style=social"/> : A Rust wrapper around native shared memory for Linux and Windows.


## Remote Desktop

  - [RustDesk](https://github.com/rustdesk/rustdesk) <img src="https://img.shields.io/github/stars/rustdesk/rustdesk?style=social"/> : Virtual / remote desktop infrastructure for everyone! Open source TeamViewer / Citrix alternative. [rustdesk.com](https://rustdesk.com).



## Date and Time

  - [Chrono](https://github.com/chronotope/chrono) <img src="https://img.shields.io/github/stars/chronotope/chrono?style=social"/> : [Chrono](https://docs.rs/chrono/latest/chrono/): Date and Time for Rust.



## Scientific Computation

  - ### Linear Algebra

    - [mathbench](https://github.com/bitshifter/mathbench-rs) <img src="https://img.shields.io/github/stars/bitshifter/mathbench-rs?style=social"/> : mathbench is a suite of unit tests and benchmarks comparing the output and performance of a number of different Rust linear algebra libraries for common game and graphics development tasks.

    - [ndarray](https://github.com/rust-ndarray/ndarray) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray?style=social"/> : The ndarray crate provides an n-dimensional container for general elements and for numerics.

    - [ndarray-linalg](https://github.com/rust-ndarray/ndarray-linalg) <img src="https://img.shields.io/github/stars/rust-ndarray/ndarray-linalg?style=social"/> : Linear algebra package for rust-ndarray using LAPACK binding.

    - [nalgebra](https://github.com/dimforge/nalgebra) <img src="https://img.shields.io/github/stars/dimforge/nalgebra?style=social"/> : Linear algebra library for the Rust programming language.

    - [glam](https://github.com/bitshifter/glam-rs) <img src="https://img.shields.io/github/stars/bitshifter/glam-rs?style=social"/> : A simple and fast 3D math library for games and graphics.

    - [rust-numpy](https://github.com/PyO3/rust-numpy) <img src="https://img.shields.io/github/stars/PyO3/rust-numpy?style=social"/> : PyO3-based Rust bindings of the NumPy C-API.

    - [cgmath](https://github.com/rustgd/cgmath) <img src="https://img.shields.io/github/stars/rustgd/cgmath?style=social"/> : A linear algebra and mathematics library for computer graphics.

    - [ultraviolet](https://github.com/fu5ha/ultraviolet) <img src="https://img.shields.io/github/stars/fu5ha/ultraviolet?style=social"/> : A wide linear algebra crate for games and graphics.

    - [vek](https://github.com/yoanlcq/vek) <img src="https://img.shields.io/github/stars/yoanlcq/vek?style=social"/> : Generic 2D-3D math swiss army knife for game engines, with SIMD support and focus on convenience. 

    - [static-math](https://github.com/elsuizo/static-math) <img src="https://img.shields.io/github/stars/elsuizo/static-math?style=social"/> : Safe and fast mathematical operations with static arrays in the Rust programming language.

    - [custos-math](https://github.com/elftausend/custos-math) <img src="https://img.shields.io/github/stars/elftausend/custos-math?style=social"/> : This crate provides CUDA, OpenCL, CPU (and Stack) based matrix operations using [custos](https://github.com/elftausend/custos).


  - ### Lie Groups

    - [sophus-rs](https://github.com/strasdat/sophus-rs) <img src="https://img.shields.io/github/stars/strasdat/sophus-rs?style=social"/> : Rust bindings for the C++ implementation of Lie Groups using Eigen.


  - ### Optimization Algorithm 

    - [OpEn](https://github.com/alphaville/optimization-engine) <img src="https://img.shields.io/github/stars/alphaville/optimization-engine?style=social"/> : Optimization Engine (OpEn) is a solver for Fast & Accurate Embedded Optimization for next-generation Robotics and Autonomous Systems.

    - [mithi/rusty-genes](https://github.com/mithi/rusty-genes) <img src="https://img.shields.io/github/stars/mithi/rusty-genes?style=social"/> : Genetic algorithm implementation in Rust with animated visualizations in Python.


  - ### Data Analysis and Visualization

    - [Polars](https://github.com/pola-rs/polars) <img src="https://img.shields.io/github/stars/pola-rs/polars?style=social"/> : [Polars](https://www.pola.rs/). Fast multi-threaded, hybrid-out-of-core DataFrame library in Rust | Python | Node.js.

    - [Plotters](https://github.com/plotters-rs/plotters) <img src="https://img.shields.io/github/stars/plotters-rs/plotters?style=social"/> : A rust drawing library for high quality data plotting for both WASM and native, statically and realtimely 🦀 📈🚀

    - [Typst](https://github.com/typst/typst) <img src="https://img.shields.io/github/stars/typst/typst?style=social"/> : A new markup-based typesetting system that is powerful and easy to learn. Typst is a new markup-based typesetting system that is designed to be as powerful as LaTeX while being much easier to learn and use.  [typst.app](https://typst.app/).

    - [Rerun](https://github.com/rerun-io/rerun) <img src="https://img.shields.io/github/stars/rerun-io/rerun?style=social"/> : Rerun: Visualization infrastructure for computer vision. Log images, point clouds, etc, and visualize them effortlessly. Built in Rust using egui. [rerun.io](https://www.rerun.io/)



## Sensor and Communication Interface

  - [scottlamb/moonfire-nvr](https://github.com/scottlamb/moonfire-nvr) <img src="https://img.shields.io/github/stars/scottlamb/moonfire-nvr?style=social"/> : Moonfire NVR, a security camera network video recorder.

  - [l1npengtul/nokhwa](https://github.com/l1npengtul/nokhwa) <img src="https://img.shields.io/github/stars/l1npengtul/nokhwa?style=social"/> : Cross Platform Rust Library for Powerful Webcam/Camera Capture.

  - [shirok1/livox-rs](https://github.com/shirok1/livox-rs) <img src="https://img.shields.io/github/stars/shirok1/livox-rs?style=social"/> : Alternative Livox LiDAR library. 

  - [jerry73204/rust-lidar-utils](https://github.com/jerry73204/rust-lidar-utils) <img src="https://img.shields.io/github/stars/jerry73204/rust-lidar-utils?style=social"/> : Encode and decode Velodyne and Ouster lidar packets in Rust.

  - [hacknus/serial-monitor-rust](https://github.com/hacknus/serial-monitor-rust) <img src="https://img.shields.io/github/stars/hacknus/serial-monitor-rust?style=social"/> : A cross-plattform serial monitor/plotter written entirely in rust. 





## Signal Processing

  - [strawlab/adskalman-rs](https://github.com/strawlab/adskalman-rs) <img src="https://img.shields.io/github/stars/strawlab/adskalman-rs?style=social"/> : Kalman filter implementation in Rust.

  - [nravic/kalmanrs](https://github.com/nravic/kalmanrs) <img src="https://img.shields.io/github/stars/nravic/kalmanrs?style=social"/> : A (yet to be) comprehensive Kalman Filter library in Rust.

  - [spdes/kalman-rust](https://github.com/spdes/kalman-rust) <img src="https://img.shields.io/github/stars/spdes/kalman-rust?style=social"/> : A simple implementation of Kalman filter and RTS smoother in Rust (ndarray).

  - [hortovanyi/Unscented-Kalman-Filter-Rust](https://github.com/hortovanyi/Unscented-Kalman-Filter-Rust) <img src="https://img.shields.io/github/stars/hortovanyi/Unscented-Kalman-Filter-Rust?style=social"/> : UKF written in Rust based on the C++ UKF from the Udacity SD Car Nanodegree.

  - [wangxiaochuTHU/yakf](https://github.com/wangxiaochuTHU/yakf) <img src="https://img.shields.io/github/stars/wangxiaochuTHU/yakf?style=social"/> : Yet Another Kalman Filter Implementation. As well as Lie Theory (Lie group and algebra) on SE(3). [no_std] is supported by default. 

  - [MichaelMauderer/filter-rs](https://github.com/MichaelMauderer/filter-rs) <img src="https://img.shields.io/github/stars/MichaelMauderer/filter-rs?style=social"/> : Kalman filters and other optimal and non-optimal estimation filters in Rust.

  - [rbagd/rust-linearkalman](https://github.com/rbagd/rust-linearkalman) <img src="https://img.shields.io/github/stars/rbagd/rust-linearkalman?style=social"/> : Kalman filtering and smoothing in Rust.




## Image and Video Processing

  - [opencv-rust](https://github.com/twistedfall/opencv-rust) <img src="https://img.shields.io/github/stars/twistedfall/opencv-rust?style=social"/> : Rust bindings for OpenCV 3 & 4. 

  - [photon](https://github.com/silvia-odwyer/photon) <img src="https://img.shields.io/github/stars/silvia-odwyer/photon?style=social"/> : Photon is a high-performance Rust image processing library, which compiles to WebAssembly, allowing for safe, blazing-fast image processing both natively and on the web. [silvia-odwyer.github.io/photon](https://silvia-odwyer.github.io/photon/)

  - [image-rs/image](https://github.com/image-rs/image) <img src="https://img.shields.io/github/stars/image-rs/image?style=social"/> : Encoding and decoding images in Rust.

  - [image-rs/imageproc](https://github.com/image-rs/imageproc) <img src="https://img.shields.io/github/stars/image-rs/imageproc?style=social"/> : An image processing library, based on the [image](https://github.com/image-rs/image) library. 

  - [zshipko/image2-rs](https://github.com/zshipko/image2-rs) <img src="https://img.shields.io/github/stars/zshipko/image2-rs?style=social"/> : A Rust crate focused on generic image processing for a wide range of image formats and data types.

  - [rust-ffmpeg](https://github.com/zmwangx/rust-ffmpeg) <img src="https://img.shields.io/github/stars/zmwangx/rust-ffmpeg?style=social"/> : Safe FFmpeg wrapper.

  - [Simp](https://github.com/Kl4rry/simp) <img src="https://img.shields.io/github/stars/Kl4rry/simp?style=social"/> : 🖼️ Simp is a fast and simple GPU-accelerated image manipulation program. 

  - [rust-cv/cv](https://github.com/rust-cv/cv) <img src="https://img.shields.io/github/stars/rust-cv/cv?style=social"/> : Rust CV mono-repo. Contains pure-Rust dependencies which attempt to encapsulate the capability of OpenCV, OpenMVG, and vSLAM frameworks in a cohesive set of APIs. 

  - [jay3332/ril](https://github.com/jay3332/ril) <img src="https://img.shields.io/github/stars/jay3332/ril?style=social"/> : Rust Imaging Library: A high-level imaging crate for Rust. [crates.io/crates/ril](https://crates.io/crates/ril)

  - [Futsch1/image-sieve](https://github.com/Futsch1/image-sieve) <img src="https://img.shields.io/github/stars/Futsch1/image-sieve?style=social"/> : ImageSieve is a GUI based tool to assist in sorting images based on taken date and similarity, categorize them according to their creation date and archive them in a target folder.







## Localization and Mapping

  - [richardanaya/slamburger](https://github.com/richardanaya/slamburger) <img src="https://img.shields.io/github/stars/richardanaya/slamburger?style=social"/> : A SLAM algorithm for WebAssembly 🍔

  - [pekkaran/violet](https://github.com/pekkaran/violet) <img src="https://img.shields.io/github/stars/pekkaran/violet?style=social"/> : A toy stereo visual inertial odometry (VIO) system.

  - [mpizenberg/visual-odometry-rs](https://github.com/mpizenberg/visual-odometry-rs) <img src="https://img.shields.io/github/stars/mpizenberg/visual-odometry-rs?style=social"/> : Visual Odometry in Rust (vors).

  - [geoeo/visual_odometry](https://github.com/geoeo/visual_odometry) <img src="https://img.shields.io/github/stars/geoeo/visual_odometry?style=social"/> : A rust port of [https://github.com/geoeo/Dense_VO](https://github.com/geoeo/Dense_VO).

  - [geoeo/Vision](https://github.com/geoeo/Vision) <img src="https://img.shields.io/github/stars/geoeo/Vision?style=social"/> : Computer Vision stuff in Rust. 





## Path Planning

  - [pathfinding](https://github.com/samueltardieu/pathfinding) <img src="https://img.shields.io/github/stars/samueltardieu/pathfinding?style=social"/> : Pathfinding library for rust. This crate implements several pathfinding, flow, and graph algorithms in Rust.

  - [rrt](https://github.com/openrr/rrt) <img src="https://img.shields.io/github/stars/openrr/rrt?style=social"/> : RRT (Rapidly-exploring Random Tree) library in Rust.

  - [gear](https://github.com/openrr/gear) <img src="https://img.shields.io/github/stars/openrr/gear?style=social"/> : Collision Avoidance Path Planning in Rust-lang.

  - [trajectory](https://github.com/openrr/trajectory) <img src="https://img.shields.io/github/stars/openrr/trajectory?style=social"/> : trajectory interpolation library for Rust and robotics.

  - [marcbone/s_curve](https://github.com/marcbone/s_curve) <img src="https://img.shields.io/github/stars/marcbone/s_curve?style=social"/> : S-Curve trajectory generator written in rust.

  - [Sollimann/bonsai](https://github.com/Sollimann/bonsai) <img src="https://img.shields.io/github/stars/Sollimann/bonsai?style=social"/> : Rust implementation of behavior trees. 




## Motion Control

  - [k](https://github.com/openrr/k) <img src="https://img.shields.io/github/stars/openrr/k?style=social"/> : k: Kinematics library for rust-lang.

  - [rsasaki0109/RustRobotics](https://github.com/rsasaki0109/RustRobotics) <img src="https://img.shields.io/github/stars/rsasaki0109/RustRobotics?style=social"/> : This package is a rust implementation of [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics). Rust implementation of PythonRobotics such as EKF, DWA, Pure Pursuit, LQR. 

  - [braincore/pid-rs](https://github.com/braincore/pid-rs) <img src="https://img.shields.io/github/stars/braincore/pid-rs?style=social"/> : A PID controller for Rust projects. 

  - [bohonghuang/rov-host](https://github.com/bohonghuang/rov-host) <img src="https://img.shields.io/github/stars/bohonghuang/rov-host?style=social"/> : A cross-platform, high-performance underwater robot controll program written in Rust. 

  - [zaiic/pid_rs](https://github.com/zaiic/pid_rs) <img src="https://img.shields.io/github/stars/zaiic/pid_rs?style=social"/> : A fairly minimal PID controller implementation in Rust.  

  - [josh-tracey/PIDController](https://github.com/josh-tracey/PIDController) <img src="https://img.shields.io/github/stars/josh-tracey/PIDController?style=social"/> : Rust PID Controller library. Rust Crate: [https://crates.io/crates/adriftdev_pid](https://crates.io/crates/adriftdev_pid)

  - [ua-kxie/pid-ctrl](https://github.com/ua-kxie/pid-ctrl) <img src="https://img.shields.io/github/stars/ua-kxie/pid-ctrl?style=social"/> : Flexible pid controller with time delta as argument.

  - [tana/balance-robot2](https://github.com/tana/balance-robot2) <img src="https://img.shields.io/github/stars/tana/balance-robot2?style=social"/> : Self-balancing robot using LQR control, written in Rust.

  - [AlexKaravaev/rust_mpc](https://github.com/AlexKaravaev/rust_mpc) <img src="https://img.shields.io/github/stars/AlexKaravaev/rust_mpc?style=social"/> : MPC racing controller made in [ros2-rust](https://github.com/ros2-rust/ros2_rust).




## Game Engine

  - [Bevy](https://github.com/bevyengine/bevy) <img src="https://img.shields.io/github/stars/bevyengine/bevy?style=social"/> : Bevy is a refreshingly simple data-driven game engine built in Rust. It is free and open-source forever! [bevyengine.org](https://bevyengine.org/)

  - [Rapier](https://github.com/dimforge/rapier) <img src="https://img.shields.io/github/stars/dimforge/rapier?style=social"/> : Rapier is a set of 2D and 3D physics engines for games, animation, and robotics. [rapier.rs](https://rapier.rs/)

  - [bevy_rapier](https://github.com/dimforge/bevy_rapier) <img src="https://img.shields.io/github/stars/dimforge/bevy_rapier?style=social"/> : Official Rapier plugin for the Bevy game engine. 

  - [Parry](https://github.com/dimforge/parry) <img src="https://img.shields.io/github/stars/dimforge/parry?style=social"/> : 2D and 3D collision-detection library for Rust. [parry.rs](https://parry.rs/)

  - [Fyrox](https://github.com/FyroxEngine/Fyrox) <img src="https://img.shields.io/github/stars/FyroxEngine/Fyrox?style=social"/> : 3D and 2D game engine written in Rust. [fyrox.rs](https://fyrox.rs/)




## Machine Learning

  - ### ML Framework

    - [TensorFlow Rust](https://github.com/tensorflow/rust) <img src="https://img.shields.io/github/stars/tensorflow/rust?style=social"/> : Rust language bindings for TensorFlow.

    - [tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch. 

    - [dfdx](https://github.com/coreylowman/dfdx) <img src="https://img.shields.io/github/stars/coreylowman/dfdx?style=social"/> : Deep learning in Rust, with shape checked tensors and neural networks.

    - [Linfa](https://github.com/rust-ml/linfa) <img src="https://img.shields.io/github/stars/rust-ml/linfa?style=social"/> : A Rust machine learning framework. Linfa aims to provide a comprehensive toolkit to build Machine Learning applications with Rust. 

    - [SmartCore](https://github.com/smartcorelib/smartcore) <img src="https://img.shields.io/github/stars/smartcorelib/smartcore?style=social"/> : The most advanced machine learning library in Rust. SmartCore is a comprehensive library for machine learning and numerical computing. The library provides a set of tools for linear algebra, numerical computing, optimization, and enables a generic, powerful yet still efficient approach to machine learning. [smartcorelib.org/](https://smartcorelib.org/)

    - [tract](https://github.com/sonos/tract) <img src="https://img.shields.io/github/stars/sonos/tract?style=social"/> : Sonos' Neural Network inference engine. Tiny, no-nonsense, self-contained, Tensorflow and ONNX inference

    - [ort](https://github.com/pykeio/ort) <img src="https://img.shields.io/github/stars/pykeio/ort?style=social"/> : A Rust wrapper for ONNX Runtime. [docs.rs/ort](https://docs.rs/ort/latest/ort/)

    - [onnxruntime-rs](https://github.com/nbigaouette/onnxruntime-rs) <img src="https://img.shields.io/github/stars/nbigaouette/onnxruntime-rs?style=social"/> : This is an attempt at a Rust wrapper for [Microsoft's ONNX Runtime](https://github.com/microsoft/onnxruntime) (version 1.8).

    - [Wonnx](https://github.com/webonnx/wonnx) <img src="https://img.shields.io/github/stars/webonnx/wonnx?style=social"/> : Wonnx is a GPU-accelerated ONNX inference run-time written 100% in Rust, ready for the web.

    - [pnn](https://github.com/ptaxom/pnn) <img src="https://img.shields.io/github/stars/ptaxom/pnn?style=social"/> : pnn is [Darknet](https://github.com/alexeyAB/darknet) compatible neural nets inference engine implemented in Rust. By optimizing was achieved significant performance increment(especially in FP16 mode). pnn provide CUDNN-based and TensorRT-based inference engines.

    - [goldstraw/RustCNN](https://github.com/goldstraw/RustCNN) <img src="https://img.shields.io/github/stars/goldstraw/RustCNN?style=social"/> : Rust convolutional neural network from scratch.

    - [michaelgiba/ggml-rs](https://github.com/michaelgiba/ggml-rs) <img src="https://img.shields.io/github/stars/michaelgiba/ggml-rs?style=social"/> : Work in progress rust bindings to ggml.

    - [elftausend/gradients](https://github.com/elftausend/gradients) <img src="https://img.shields.io/github/stars/elftausend/gradients?style=social"/> : Deep Learning library using [custos](https://github.com/elftausend/custos) and [custos-math](https://github.com/elftausend/custos-math).



    
  - ### Large Language Model

    - [yetone/openai-translator](https://github.com/yetone/openai-translator) <img src="https://img.shields.io/github/stars/yetone/openai-translator?style=social"/> : The translator that does more than just translation - powered by OpenAI.

    - [lencx/ChatGPT](https://github.com/lencx/ChatGPT) <img src="https://img.shields.io/github/stars/lencx/ChatGPT?style=social"/> : 🔮 ChatGPT Desktop Application (Mac, Windows and Linux). [NoFWL](https://app.nofwl.com/).

    - [ChatGPT-Desktop](https://github.com/ChatGPT-Desktop/ChatGPT-Desktop) <img src="https://img.shields.io/github/stars/ChatGPT-Desktop/ChatGPT-Desktop?style=social"/> : ChatGPT 跨平台客户端，快捷键快速唤醒窗口，问答快人一步！ 基于 tauri + vue3 开发的跨平台桌面端应用。 

    - [sonnylazuardi/chat-ai-desktop](https://github.com/sonnylazuardi/chat-ai-desktop) <img src="https://img.shields.io/github/stars/sonnylazuardi/chat-ai-desktop?style=social"/> : Chat AI Desktop App. Unofficial ChatGPT desktop app for Mac & Windows menubar using Tauri & Rust.

    - [rustformers/llama-rs](https://github.com/rustformers/llama-rs) <img src="https://img.shields.io/github/stars/rustformers/llama-rs?style=social"/> : Run LLaMA inference on CPU, with Rust 🦀🚀🦙.

    - [m1guelpf/browser-agent](https://github.com/m1guelpf/browser-agent) <img src="https://img.shields.io/github/stars/m1guelpf/browser-agent?style=social"/> : A browser AI agent, using GPT-4. [docs.rs/browser-agent](https://docs.rs/browser-agent/latest/browser_agent/)

    - [Noeda/rllama](https://github.com/Noeda/rllama) <img src="https://img.shields.io/github/stars/Noeda/rllama?style=social"/> : Rust+OpenCL+AVX2 implementation of LLaMA inference code.

    - [sigoden/aichat](https://github.com/sigoden/aichat) <img src="https://img.shields.io/github/stars/sigoden/aichat?style=social"/> : Using ChatGPT/GPT-3.5/GPT-4 in the terminal. 

    - [uiuifree/rust-openai-chatgpt-api](https://github.com/uiuifree/rust-openai-chatgpt-api) <img src="https://img.shields.io/github/stars/uiuifree/rust-openai-chatgpt-api?style=social"/> : "rust-openai-chatgpt-api" is a Rust library for accessing the ChatGPT API, a powerful NLP platform by OpenAI. The library provides a simple and efficient interface for sending requests and receiving responses, including chat. It uses reqwest and serde for HTTP requests and JSON serialization. 




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

  - [Deno](https://github.com/denoland/deno) <img src="https://img.shields.io/github/stars/denoland/deno?style=social"/> : Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust. [deno.land](https://deno.land/)

  - [Hyper](https://github.com/vercel/hyper) <img src="https://img.shields.io/github/stars/vercel/hyper?style=social"/> : A terminal built on web technologies. [hyper.is](https://hyper.is/)

  - [Yew](https://github.com/yewstack/yew) <img src="https://img.shields.io/github/stars/yewstack/yew?style=social"/> : Yew is a modern Rust framework for creating multi-threaded front-end web apps with WebAssembly. [swc.rs](https://swc.rs/)

  - [SWC](https://github.com/swc-project/swc) <img src="https://img.shields.io/github/starsswc-project/swc?style=social"/> : SWC (stands for Speedy Web Compiler) is a super-fast TypeScript / JavaScript compiler written in Rust. [yew.rs](https://yew.rs/)

  - [Rocket](https://github.com/SergioBenitez/Rocket) <img src="https://img.shields.io/github/stars/SergioBenitez/Rocket?style=social"/> : A web framework for Rust. [rocket.rs](https://rocket.rs/)

  - [Actix](https://github.com/actix/actix-web) <img src="https://img.shields.io/github/stars/actix/actix-web?style=social"/> : Actix Web is a powerful, pragmatic, and extremely fast web framework for Rust. [actix.rs](https://actix.rs/)

  - [Axum](https://github.com/tokio-rs/axum) <img src="https://img.shields.io/github/stars/tokio-rs/axum?style=social"/> : Ergonomic and modular web framework built with Tokio, Tower, and Hyper.

  - [Salvo](https://github.com/salvo-rs/salvo) <img src="https://img.shields.io/github/stars/salvo-rs/salvo?style=social"/> : [Salvo](https://salvo.rs/) is a powerful and simplest web server framework in Rust world.

  - [Leptos](https://github.com/leptos-rs/leptos) <img src="https://img.shields.io/github/stars/leptos-rs/leptos?style=social"/> : Build fast web applications with Rust. 

  - [zino](https://github.com/photino/zino) <img src="https://img.shields.io/github/stars/photino/zino?style=social"/> : zino is a full-featured web application framework for Rust with a focus on productivity and performance.



## Web Crawler

  - [Spider](https://github.com/spider-rs/spider) <img src="https://img.shields.io/github/stars/spider-rs/spider?style=social"/> : Spider: The fastest web crawler and indexer. [docs.rs/spider/](https://docs.rs/spider/latest/spider/)

  - [a11ywatch/crawler](https://github.com/a11ywatch/crawler) <img src="https://img.shields.io/github/stars/a11ywatch/crawler?style=social"/> : A [gRPC](https://grpc.io/) web indexer turbo charged for performance.

  - [Antosser/web-crawler](https://github.com/Antosser/web-crawler) <img src="https://img.shields.io/github/stars/Antosser/web-crawler?style=social"/> : Rust Web Crawler that finds every page, image, and script on a website (and downloads it) 

  - [ravenxd0/crawler](https://github.com/ravenxd0/crawler) <img src="https://img.shields.io/github/stars/ravenxd0/crawler?style=social"/> : Web Crawler in Rust.

  - [lonexw/rust-crawler](https://github.com/lonexw/rust-crawler) <img src="https://img.shields.io/github/stars/lonexw/rust-crawler?style=social"/> : A simple crawler, built with Rust lang. 

  - [tawilkinson/rust_web_crawler](https://github.com/tawilkinson/rust_web_crawler) <img src="https://img.shields.io/github/stars/tawilkinson/rust_web_crawler?style=social"/> : A simple web crawler in rust.


  



## WebAssembly Runtime

  - [Wasmer](https://github.com/wasmerio/wasmer) <img src="https://img.shields.io/github/stars/wasmerio/wasmer?style=social"/> : Wasmer is a fast and secure [WebAssembly](https://webassembly.org/) runtime that enables super lightweight containers to run anywhere: from Desktop to the Cloud, Edge and IoT devices. [wasmer.io](https://wasmer.io/)

  - [wasmtime](https://github.com/bytecodealliance/wasmtime) <img src="https://img.shields.io/github/stars/bytecodealliance/wasmtime?style=social"/> : A fast and secure runtime for WebAssembly. [wasmtime.dev/](https://wasmtime.dev/)




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


