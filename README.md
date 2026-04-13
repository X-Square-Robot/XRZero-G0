# XRZero-G0: Pushing the Frontier of Dexterous Robotic Manipulation 🚀
[![Paper](https://img.shields.io/badge/Paper-PDF-red)](#) 
[![Dataset](https://img.shields.io/badge/Dataset-G0--Dataset-blue)](#) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
> **XRZero-G0** is a hardware-software co-designed framework for scalable, high-fidelity, and ergonomic robot-free data collection. By systematically addressing the "quality black-box" and establishing empirical **Data Mixing Laws**, XRZero-G0 achieves performance comparable to purely real-robot datasets at **1/20th of the acquisition cost**.
<div align="center">
  <img src="imgs/head.pdf" alt="XRZero-G0 Teaser" width="100%">
  <p><em>Figure 1: XRZero-G0 enables scalable robot-free data collection and cross-embodiment policy transfer.</em></p>
</div>

---
## ✨ Highlights
*   🕹️ **Ergonomic Decoupled Interface:** Replaces traditional SLAM-based handhelds with a backpack-powered VR rig (PICO 4) and specialized dual-mode grippers. Eliminates tracking drift and reduces operator fatigue.
*   🛡️ **Closed-Loop Quality Verification:** A rigorous pipeline featuring visual cleansing and Inverse Kinematics (IK) validation, ensuring an **85% data validity rate** before training.
*   ⚖️ **Empirical Data-Mixing Laws:** Demonstrates the *Few-Shot Physical Anchoring* effect. A **10:1 ratio** (massive robot-free data + minimal real-robot data) matches the performance of 100% real-robot data.
*   🌍 **Zero-Shot Cross-Embodiment:** Generates data natively compatible with leading VLA (Vision-Language-Action) models (e.g., Wall-OSS, $\pi_0$, $\pi_{0.5}$), enabling direct transfer to structurally different dual-arm robots (CX001 & EX001).
---

---
## 📦 The G0-Dataset
Using the XRZero-G0 framework, we have collected one of the most comprehensive human-centric embodied datasets to date.
*   **Scale:** Over **2,000 hours** of high-fidelity, multi-modal data.
*   **Diversity:** **3,000 distinct manipulation tasks** following a pronounced long-tail distribution (from fundamental operations to fine-grained semantic tasks).
*   **Throughput:** Operators achieved a peak collection speed of up to **93.2 episodes per hour**.
---
