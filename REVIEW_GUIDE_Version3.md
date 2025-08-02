# Review Guide for @dennybritz/nn-from-scratch

This document organizes useful links and modules related to neural network fundamentals and best practices, for convenient review and quick reference as you work through this repository.

---

## 📚 External Course & Reading Links

1. **Stanford CS231n: Convolutional Neural Networks for Visual Recognition**
   - [Neural Networks Case Study (CS231n)](https://cs231n.github.io/neural-networks-case-study/)

2. **StackExchange: Image Normalization**
   - [Why normalize images by subtracting dataset’s image mean instead of the current image mean?](https://stats.stackexchange.com/questions/211436/why-normalize-images-by-subtracting-datasets-image-mean-instead-of-the-current)

3. **Stack Overflow: IPython autoreload**
   - [Autoreload of modules in IPython](https://stackoverflow.com/questions/1907993/autoreload-of-modules-in-ipython)

---

## 📦 Relevant Modules in This Repository

Below are the core modules and scripts in `@dennybritz/nn-from-scratch` that directly relate to foundational neural network learning and experimentation:

| Module/Script      | Purpose/Contents                         | Concepts Covered                          |
|--------------------|------------------------------------------|-------------------------------------------|
| `1_neural_network.py` | Basic neural network implementation    | Forward/backward pass, weight updates     |
| `2_neural_network_with_bias.py` | Adds bias to network          | Bias units, improved training             |
| `3_mnist_network.py` | Network for MNIST digit recognition     | Data normalization, multi-layer network   |
| `4_neural_network_class.py` | OOP version of neural network   | Code organization, modularity             |
| `utils.py`         | Utility functions (data load/prep, etc.) | Preprocessing, normalization              |

**Tip:** For image normalization examples and code, review the relevant functions in `utils.py` and normalization steps in `3_mnist_network.py`.

---

## 📝 How to Use This Guide

- **Review Order Suggestion:**
  1. Read the CS231n case study to understand the context and motivation behind each neural network component.
  2. Check the StackExchange link for best normalization practices.
  3. Step through the scripts in order (`1_neural_network.py` → `4_neural_network_class.py`).
  4. Use Stack Overflow link for improving your interactive workflow (e.g., IPython autoreload when experimenting).
- **Reference back to this guide whenever you need to quickly find the right module or external reading.**

---

*Happy Reviewing!*