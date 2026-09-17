# 🧠 Deep Learning Foundations: Zero to Hero

A ground-up implementation of core Deep Learning mechanics and architectures, built from scratch to deeply understand the math and engineering behind modern AI.

## 🎯 Overview

This repository tracks my progress and implementations based on Andrej Karpathy's [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) series. 

Instead of treating Neural Networks as "black boxes" using high-level APIs, this project focuses on building the foundational components—from automatic differentiation engines to Transformer models—in pure Python and PyTorch. The goal is a complete understanding of backpropagation, tensor operations, and network architecture.

## 🗺️ Project Roadmap

As I progress through the material, I am building the following components:

- [x] **Micrograd:** A scalar-valued autograd engine and a simple Multi-Layer Perceptron (MLP) built in pure Python (understanding the exact math of backpropagation).
- [ ] **Makemore (MLP & Internals):** Character-level language models, exploring Batch Normalization, gradient flow, and internal network health.
- [ ] **Makemore (WaveNet):** Implementing tree-like convolutional neural networks for sequence modeling.
- [ ] **GPT from Scratch:** Implementing the Transformer architecture (Self-Attention, Positional Encoding, LayerNorm) following the *Attention is All You Need* paper.
- [ ] **Tokenizer:** Building a Byte Pair Encoding (BPE) tokenizer from scratch.

*(Checkboxes will be updated as modules are completed).*

## 🛠️ Tech Stack

- **Python 3.x**
- **PyTorch** (for efficient Tensor operations and GPU acceleration)
- **NumPy & Matplotlib** (for mathematical operations and gradient visualizations)
- **Jupyter Notebook** (for interactive step-by-step implementation)

## 🚀 Getting Started

Clone the repository and set up the local environment:

```bash
git clone [https://github.com/YourUsername/Zero-to-Hero-DL.git](https://github.com/YourUsername/Zero-to-Hero-DL.git)
cd Zero-to-Hero-DL

# Create virtual environment
python -m venv .venv

# Activate environment (Linux/macOS)
source .venv/bin/activate
# Activate environment (Windows)
.venv\Scripts\activate

# Install dependencies
pip install torch numpy matplotlib jupyter