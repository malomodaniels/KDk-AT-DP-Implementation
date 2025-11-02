📘 Overview

This project implements a dual-defense framework for Vertical Federated Learning (VFL) that combines
Adversarial Training (AT) and Differential Privacy (DP) to defend against both Adversarial and Label Inference Attacks (LIAs).
The approach balances model utility, robustness, and privacy, improving on KDk by integrating gradient- and embedding-level defenses.

⚙️ Experimental Setup

Domains: Vision (CIFAR-10/100, CINIC-10) | Text (Yahoo! Answers) | Tabular (Criteo CTR)

Framework: PyTorch 3.12 | Colab A100 GPU

Metrics: Clean ACC, Robust ACC, ASR, Privacy Leakage Index (PLI)
