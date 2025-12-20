# 🧬 Evolutionary Adversarial Attacks on DCGANs

> **Exploring how adversarial robustness and generative quality evolve under FGSM, PGD, and JSMA attacks — guided by evolutionary algorithms.**

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)


---

## 🧠 Overview
This research combines **Evolutionary Algorithms** and **Adversarial Machine Learning** to analyze how **Deep Convolutional GANs (DCGANs)** behave when subjected to attacks like **FGSM**, **PGD**, and **JSMA** — individually and in sequence.

We use an **evolutionary optimization loop** to:
- Evolve attack combinations over generations.
- Quantify how adversarial stress affects GAN training stability.
- Discover which sequences of attacks cause maximum performance degradation.

---

## 🌌 Key Highlights

- ⚔️ **Multi-Attack Integration** — FGSM, PGD, JSMA, and hybrid sequences.  
- 🧬 **Evolutionary Optimization** — Populations evolve to find strongest attack chains/sequences.  
- 🧠 **Robustness Evaluation** — Measures generator collapse, discriminator confusion, and FID/IS metrics.  
- 🧩 **Modular Design** — Easy to plug in new GANs, attacks, or fitness metrics.  

---


