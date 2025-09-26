# FedAlign: Federated Domain Generalization with Cross-Client Feature Alignment

**Authors:** Sunny Gupta, Vinay Sutar, Varunav Singh, Amit Sethi  
**Conference:** CVPR 2025  
**Paper:** [arXiv:2501.15486](https://arxiv.org/abs/2501.15486)

---

## 🔍 Overview

**FedAlign** is a lightweight, privacy-preserving framework for **Federated Domain Generalization (FedDG)** that enhances generalization to unseen domains without compromising data privacy. It addresses key challenges such as:

- Strict privacy constraints in Federated Learning (FL)
- Non-i.i.d. data distributions across clients
- Limited domain diversity

### 🚀 Key Contributions

- **Cross-Client Feature Extension Module**  
  Enhances local domain representation using domain-invariant feature perturbation and selective cross-client feature transfer.

- **Dual-Stage Alignment Module**  
  Aligns both feature embeddings and predictions across clients to extract robust, domain-invariant representations.

- **Lightweight & Scalable**  
  Requires minimal computation and communication overhead, making it suitable for real-world federated setups.

---

## 📁 Dataset Preparation

To use a dataset, place it in the following directory structure:

