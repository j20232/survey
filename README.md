# 🍓Survey 
## 🦑 Paper Summary
https://github.com/j20232/survey/issues

---

## 🌊 Continuum Simulation

### Material Point Method
- [MPM COURSES FROM SIGGRAPH](https://www.seas.upenn.edu/~cffjiang/mpmcourse.html): introduction about MPM by top researchers
- [Joseph M. Teran](https://www.math.ucla.edu/~jteran/): computational biomechanics/virtual surgery, computational solid and fluid mechanics, meshing, collision detection/contact modeling, multigrid methods, parallel computing and solid/fluid coupling
- [Chenfanfu Jiang](https://www.seas.upenn.edu/~cffjiang/): there are many useful links about MPM
   - [squarefk/ziran2019](https://github.com/squarefk/ziran2019): open source MPM implementations
- [Craig Schroeder](https://www.cs.ucr.edu/~craigs/research.html): some researches
- [Yonghao Yue](http://mns.k.u-tokyo.ac.jp/~yonghao/): he mainly study the mixing of particles
- [AndrewSelle](http://www.andyselle.com/): currently, he doesn't study MPM
- [Taichi](https://github.com/yuanming-hu/taichi): programming language for high-performance sparse visual computing
- [GitHub's Tag](https://github.com/topics/material-point-method)

### Fluid Simulation
- [Shiokaze framework](https://github.com/ryichando/shiokaze): open-source fluid simulation solver for computer graphics
- [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH): open-source library about SPH, which is a popular meshless Lagrangian approach to simulate complex fluid effects
- [thunil/Physics-Based-Deep-Learning](https://github.com/thunil/Physics-Based-Deep-Learning): links to works on deep learning algorithms for physics problems, with a particular emphasis on fluid flow, i.e., Navier-Stokes related problems
- [InteractiveComputerGraphics/SPH-Tutorial](https://github.com/InteractiveComputerGraphics/SPH-Tutorial): "Smoothed Particle Hydrodynamics for Physically-Based Simulation of Fluids and Solids", Eurographics Tutorial, 2019
- [tunabrain/incremental-fluids](https://github.com/tunabrain/incremental-fluids): The purpose of this project is to provide simple, easy to understand fluid solver implementations in C++, together with code documentation, algorithm explanation and recommended reading
- [tum-pbs/PhiFlow](https://github.com/tum-pbs/PhiFlow): Research-oriented differentiable fluid simulation framework

### Position Based Dynamics
- [InteractiveComputerGraphics/PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics): a library for the physically-based simulation of rigid bodies, deformable solids and fluids.
- [ltt1598/Quasi-Newton-Methods-for-Real-time-Simulation-of-Hyperelastic-Materials](https://github.com/ltt1598/Quasi-Newton-Methods-for-Real-time-Simulation-of-Hyperelastic-Materials): approximation methods for realtime PBD

### Physics Engine
- [bulletphysics/bullet3](https://github.com/bulletphysics/bullet3): official C++ source code repository of the Bullet Physics SDK: real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc
- [yuanming-hu/difftaichi](https://github.com/yuanming-hu/difftaichi): 10 Differentiable Physical Simulators Built with Taichi Differentiable Programming (DiffTaichi)

---

## 📷 Computer Vision
### General
- [kornia/kornia](https://github.com/kornia/kornia): Open Source Differentiable Computer Vision Library for PyTorch

### 3D Vision
- [pqhieu/torch3d](https://github.com/pqhieu/torch3d): a PyTorch library consisting of datasets, model architectures, and common operations for 3D deep learning
- [NVIDIAGameWorks/kaolin](https://github.com/NVIDIAGameWorks/kaolin): a PyTorch Library for Accelerating 3D Deep Learning Research
- [holistic-3d/holistic-3d-resources](https://github.com/holistic-3d/holistic-3d-resources): a  list of papers and resources for holistic 3D reconstruction

### Object Detection
- [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2): Facebook AI Research's SOTA implementation for object detection

### SLAM
- [MIT-SPARK/Kimera](https://github.com/MIT-SPARK/Kimera):  C++ library for real-time metric-semantic simultaneous localization and mapping, which uses camera images and inertial data to build a semantically annotated 3D mesh of the environment
- [xdspacelab/openvslam](https://github.com/xdspacelab/openvslam): a monocular, stereo, and RGBD visual SLAM system

---

## 🐰 Computer Graphics

### GPU acceleration
- [jgbit/vuda](https://github.com/jgbit/vuda): a header-only library based on Vulkan that provides a CUDA Runtime API interface for writing GPU-accelerated applications

### Renderer
- [mitsuba-renderer/mitsuba](https://github.com/mitsuba-renderer/mitsuba):  research-oriented rendering system in the style of PBRT, from which it derives much inspiration. It is written in portable C++, implements unbiased as well as biased techniques, and contains heavy optimizations targeted towards current CPU architectures 
- [BachiLi/redner](https://github.com/BachiLi/redner): A differentiable Monte Carlo path tracer
- [google/filament](https://github.com/google/filament): a real-time physically based rendering engine for Android, iOS, Windows, Linux, macOS and WASM/WebGL
- [SaschaWillems/Vulkan](https://github.com/SaschaWillems/Vulkan): a comprehensive collection of open source C++ examples for Vulkan
- [SaschaWillems/Vulkan-glTF-PBR](https://github.com/SaschaWillems/Vulkan-glTF-PBR): physical based rendering with Vulkan using glTF 2.0 models
- [CaffeineViking/vkhr](https://github.com/CaffeineViking/vkhr): Real-Time Hybrid Hair Rendering using Vulkan
- [techlabxe/vulkan_book_1](https://github.com/techlabxe/vulkan_book_1): sample code of "Vulkan Programming Vol.1"

### Skinning
- [electronicarts/dem-bones](https://github.com/electronicarts/dem-bones): An automated algorithm to extract the linear blend skinning (LBS) from a set of example poses

### Material
- [Material Database](https://rgl.epfl.ch/materials): an interactive interface to materials

### Visualization
- [Kitware/VTK](https://github.com/Kitware/VTK): an open-source software system for image processing, 3D graphics, volume rendering and visualization
- [pyvista/pyvista](https://github.com/pyvista/pyvista): 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK)

---

## 🌐 Data Structure

### General
- [assimp/assimp](https://github.com/assimp/assimp): a library to import and export various 3d-model-formats including scene-post-processing to generate missing render data
- [mitsuba-renderer/enoki](https://github.com/mitsuba-renderer/enoki): structured vectorization and differentiation on modern processor architectures

### Geometry
- [sunglok/3dv_tutorial](https://github.com/sunglok/3dv_tutorial): an introductory tutorial on 3D vision (a.k.a. geometric vision or visual geometry or multi-view geometry
- [libigl/libigl](https://github.com/libigl/libigl): a simple C++ geometry processing library

### Vector
- [facebookresearch/faiss](https://github.com/facebookresearch/faiss): library for efficient similarity search and clustering of dense vectors

### Mesh
- [MPI-IS/mesh](https://github.com/MPI-IS/mesh): Package contains core functions for manipulating meshes and visualizing them by MPI
- [REAL VIRTUAL HUMANS](https://virtualhumans.mpi-inf.mpg.de/): research group at MPI to make virtual humans that look, move and eventually think like real ones
- [optimad/mimmo](https://github.com/optimad/mimmo): a C++ library for Manipulation and Morphing of surface/volume meshes

### Point cloud
- [InteractiveComputerGraphics/CompactNSearch](https://github.com/InteractiveComputerGraphics/CompactNSearch): a C++ library to compute neighborhood information for point clouds within a fixed radius. Suitable for many applications, e.g. neighborhood search for SPH fluid simulations.

### Graph
- [dmlc/dgl](https://github.com/dmlc/dgl): Python package built to ease deep learning on graph, on top of existing DL frameworks

### exr
- [AcademySoftwareFoundation/openexr](https://github.com/AcademySoftwareFoundation/openexr): the specification and reference implementation of the EXR file format, the professional-grade image storage format of the motion picture industry
- [syoyo/tinyexr](https://github.com/syoyo/tinyexr): a small, single header-only library to load and save OpenEXR(.exr) images

### obj
- [syoyo/tinyobjloader](https://github.com/syoyo/tinyobjloader): Tiny but powerful single file wavefront obj loader written in C++03

### glTF
- [AnalyticalGraphicsInc/obj2gltf](https://github.com/AnalyticalGraphicsInc/obj2gltf): Convert OBJ assets to glTF
- [syoyo/tinygltf](https://github.com/syoyo/tinygltf): Header only C++11 tiny glTF 2.0 library

---

## 📈 Numerical Calculation

### Linear Algebra
- [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page): a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms
- [GLM](https://glm.g-truc.net/0.9.9/index.html):  a header only C++ mathematics library for graphics software based on the OpenGL Shading Language (GLSL) specifications.
- [sgorsten/linalg](https://github.com/sgorsten/linalg): a single header, public domain, short vector math library for C++

### Optimization
- [facebookresearch/higher](https://github.com/facebookresearch/higher): pytorch library allowing users to obtain higher order gradients over losses spanning training loops rather than individual training steps
- [williamFalcon/pytorch-lightning](https://github.com/williamFalcon/pytorch-lightning): a very lightweight wrapper on PyTorch
- [ceres-solver/ceres-solver](https://github.com/ceres-solver/ceres-solver): an open source C++ library for modeling and solving large, complicated optimization problems
- [google/jax](https://github.com/google/jax): Composable transformations of Python+NumPy programs: differentiate, vectorize, JIT to GPU/TPU, and more

### Algorithm
- [Algorithm Visualizer](https://algorithm-visualizer.org/): an interactive online platform that visualizes algorithms from code

### Parallel Programming
- [intel/tbb](https://github.com/intel/tbb): C++ library for shared memory parallel programming and heterogeneous computing (intra-node distributed memory programming)

---

## 💻 Web Tools
### Web Design
- [Hover.css](http://ianlunn.github.io/Hover/): a collection of CSS3 powered hover effects to be applied to links, buttons, logos, SVG, featured images and so on
