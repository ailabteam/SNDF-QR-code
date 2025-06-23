# SNDF-QR-code
# SNDF: Siamese Network for Discriminative Feature Learning  
_**Robust QR-Code Phishing (“Quishing”) Detection from Low-Resolution Sources**_

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)  
![Python](https://img.shields.io/badge/python-3.9%20|%203.10%20|%203.11-blue) ![PyTorch](https://img.shields.io/badge/pytorch-2.1+-red)

---

## 📜 Abstract
QR code-based phishing (``quishing'') attacks bypass traditional filters by embedding malicious payloads in an opaque format, exposing users to threats before content can be analyzed. Detecting these attacks directly from the low-resolution source images common in public datasets is a key challenge, as the subtle pixel patterns that indicate malicious intent can be distorted during the upscaling required for deep learning models. To address this, we propose SNDF (Siamese Network for Discriminative Feature Learning), a deep metric learning framework. Trained with a contrastive loss objective, SNDF learns to distinguish benign from malicious codes by mapping their raw pixel patterns to a feature space where they are clearly separable, eliminating the need for decoding and preserving user privacy. On a balanced dataset of 9,987 QR codes, SNDF achieves a state-of-the-art AUC of 0.9918 and an F1-score of 0.9830, significantly outperforming the previous XGBoost benchmark and multiple deep learning baselines. This work is the first to validate that a pairwise metric learning approach can provide a near-perfect and practical solution for pre-scan quishing detection from low-resolution sources


