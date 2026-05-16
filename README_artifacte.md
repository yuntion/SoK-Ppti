# SoK: Private Transformer-Based Model Inference

This repository contains the open-source code implementation for the paper in our SoK, as well as a curated integration of mainstream privacy-preserving computation (PPC) frameworks and cryptographic libraries. 

To help researchers and developers get started quickly and eliminate the hassle of complex environment setups, we provide a unified, plug-and-play development environment. The core objective of this project is to offer a convenient experimentation and benchmarking platform for scholars and engineers in the privacy-preserving computation field. 
---

## Key Contents

This repository consists of two main contributions:

### 1. Artifacts & Paper Implementation
* **Full Coverage:** Contains the complete implementation of the schemes evaluated in our paper.


### 2. Integrated Privacy-Preserving Computation Libraries
We have wrapped and modularized several mainstream cryptographic and MPC frameworks widely adopted in both academia and industry, including but not limited to:
* **EMP-toolkit:** For efficient Garbled Circuit (GC) and Oblivious Transfer (OT) primitives.
* **MP-SPDZ:** For benchmarking versatile MPC protocols across various security models.
* **CryptFlow2:** For secure inference and privacy-preserving neural network operations.

---

## Target Audience & Use Cases

This platform is highly suitable for:
* **Prototyping:** Rapidly implementing and verifying new privacy-preserving protocols or tailored operators (e.g., non-linear activation layers, matrix multiplications).
* **Benchmarking:** Measuring fine-grained performance metrics such as computation runtime, communication overhead, and network adaptation capabilities under different bandwidths/latencies.
* **Comparative Evaluation:** Conducting fair, apple-to-apple comparisons between different baseline methods under identical hardware constraints.

---

## Contributing

We warmly welcome and highly appreciate contributions from the community! 

If you have:
* Optimized the compilation or deployment scripts,
* Documented unique observations regarding the usability or quirks of specific frameworks,

Please feel free to submit a **Pull Request** or reach out to us via **Email**. Your contributions will significantly benefit the broader privacy-preserving computation research community.

---

## Citation

Papers are available [here](https://eprint.iacr.org/2026/491). For citation in academic work, use the following BibTeX entries.

```
@misc{cryptoeprint:2026/491,
      author = {Yuntian Chen and Tianpei Lu and Zhanyong Tang and Bingsheng Zhang and Zhiying Shi and Yuxiang Luan and Zhuzhu Wang},
      title = {{SoK}: Private Transformer-Based Model Inference},
      howpublished = {Cryptology {ePrint} Archive, Paper 2026/491},
      year = {2026},
      url = {https://eprint.iacr.org/2026/491}
}
```