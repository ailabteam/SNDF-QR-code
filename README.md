# SNDF-QR-code
# SNDF: Siamese Network for Discriminative Feature Learning  
_**Robust QR-Code Phishing (“Quishing”) Detection from Low-Resolution Sources**_

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)  
![Python](https://img.shields.io/badge/python-3.9%20|%203.10%20|%203.11-blue) ![PyTorch](https://img.shields.io/badge/pytorch-2.1+-red)

---

## 📜 Abstract
QR-code–based phishing (quishing) attacks embed malicious payloads in an opaque matrix that evades traditional URL and e-mail filters. Detecting these threats directly **before** the QR code is scanned is hard because public datasets provide only low-resolution images whose fine pixel patterns are easily destroyed by naïve up-scaling.  
**SNDF** tackles this challenge with a **Siamese metric-learning framework** trained via **contrastive loss** to separate benign and malicious codes in feature space—_without ever decoding the QR content_, thereby preserving user privacy. On a balanced benchmark of **9 ,987 codes**, SNDF reaches **AUC = 0.9918** and **F<sub>1</sub> = 0.9830**, beating the previous XGBoost and CNN baselines by a large margin.

---

## 📂 Repository Layout
