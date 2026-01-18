# Quantum Kernel Learning for Binary Classification

A quantum machine learning framework that implements and benchmarks quantum kernel methods for classical classification tasks.

## Overview
This project explores quantum-enhanced machine learning by encoding classical features into quantum states and computing similarity through quantum circuits. It implements both baseline and parameterized quantum kernels, benchmarking them against classical SVM with RBF kernel.

## Features
- **Quantum Kernel Implementation**: Encode classical data into quantum states using custom feature maps
- **Parameterized Quantum Circuits**: Trainable kernels with optimizable quantum circuit parameters
- **Classical Benchmarking**: Comprehensive comparison against classical SVM
- **Modular Design**: Easy experimentation with different quantum encodings and kernels

## Quick Start
```bash
git clone https://github.com/yourusername/quantum-kernel-learning.git
cd quantum-kernel-learning
pip install -r requirements.txt
python main.py --dataset iris --kernel_type parametric
