# Python GPU Environment Setup

This repository documents the complete setup, configuration, validation, and troubleshooting of a Python GPU environment for Artificial Intelligence (AI) and Machine Learning (ML) development on Windows.

The environment was configured using Anaconda, NVIDIA CUDA Toolkit, cuDNN, Jupyter Notebook, and PyTorch, followed by GPU validation and benchmarking to verify correct installation and performance.

## Objectives

- Configure a GPU-enabled Python environment
- Install NVIDIA CUDA Toolkit
- Configure cuDNN
- Create and manage Conda environments
- Configure Jupyter Notebook
- Validate PyTorch GPU acceleration
- Benchmark CPU vs GPU performance
- Document common installation and troubleshooting procedures

## Hardware Configuration

| Component | Specification |
|-----------|---------------|
| Operating System | Windows 10 |
| GPU | NVIDIA GeForce GTX 1050 Ti (4 GB) |
| Python | 3.10 |
| CUDA | 11.8 |
| cuDNN | 9.1 |
| PyTorch | 2.7.1 + cu118 |

## Validation Results

✅ CUDA successfully detected

✅ cuDNN enabled

✅ GPU available in PyTorch

✅ Jupyter GPU kernel configured

✅ GPU benchmark completed

### Performance Benchmark

```
CPU Time : 2.633 sec

GPU Time : 0.140 sec

Speedup : 18.75×
```

## Repository Contents

- GPU Validation Notebook
- CUDA Installation Notes
- cuDNN Configuration
- Conda Environment Setup
- Jupyter Configuration
- GPU Benchmark Results
- Troubleshooting Guide

## Skills Demonstrated

- NVIDIA Driver Installation
- CUDA Installation
- cuDNN Configuration
- Conda Environment Management
- Python Environment Configuration
- Jupyter Notebook Setup
- PyTorch GPU Validation
- GPU Performance Benchmarking
- Environment Troubleshooting

## Purpose

This repository serves as a practical reference for configuring and validating a reproducible GPU environment for Machine Learning and Deep Learning development using Python.
