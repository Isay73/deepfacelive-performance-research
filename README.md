# DeepFaceLive Performance Research

## Overview

This repository documents my research into improving the performance and stability of a real-time AI face swapping pipeline.

The project focused on GPU acceleration, runtime optimization and improving the quality of real-time face tracking while maintaining stable performance.

This repository intentionally documents the engineering process rather than publishing implementation details.

---

## Objectives

- Improve face tracking stability
- Improve mask quality during head movement
- Reduce latency
- Improve GPU utilization
- Increase runtime stability
- Optimize inference pipeline

---

## Technologies

- DeepFaceLive
- CUDA
- TensorRT
- ONNX Runtime
- NVIDIA RTX 4090
- MediaPipe FaceMesh
- YOLOv8 Face
- InsightFace
- Python

---

## Research Areas

- CUDA optimization
- TensorRT inference
- Mixed Precision (FP16)
- GPU memory optimization
- ONNX Runtime
- Face tracking
- Face alignment
- Runtime stability
- Multiprocessing
- Asynchronous pipeline
- Performance profiling

---

## Project Screenshots

### Running Application

![Application](screenshots/application.png)

---

### Face Tracking

![Tracking](screenshots/tracking.png)

---

### Runtime Output

![Runtime](screenshots/runtime-output.png)

---

### Project Structure

![Structure](screenshots/project-structure.png)

---

## Challenges

The default DeepFaceLive environment required significant work to achieve stable real-time performance.

The main areas of research included:

- Face tracking quality
- Mask stability during head movement
- Runtime optimization
- GPU acceleration
- CUDA compatibility
- ONNX Runtime compatibility
- Pipeline stability
- Performance bottlenecks

---

## Results

After extensive experimentation the project achieved:

- More stable real-time tracking
- Better mask quality during movement
- Improved runtime stability
- Faster inference
- Better GPU utilization
- More reliable application behavior

Performance numbers and implementation details are intentionally omitted.

---

## What I Learned

During this project I gained practical experience with:

- CUDA
- TensorRT
- ONNX Runtime
- GPU optimization
- AI inference pipelines
- Performance profiling
- Multiprocessing
- Runtime debugging
- AI application architecture

---

## Research Notes

This repository focuses on documenting the engineering process rather than publishing proprietary implementation details.

The optimization techniques, configuration files, custom pipeline and internal modifications are intentionally not included.

---

## Future Work

- Better face tracking
- Additional GPU optimizations
- Multi-GPU support
- Further runtime improvements
- Pipeline simplification
