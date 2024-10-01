# Adversarial Robustness in Deep Learning

This project explores techniques to improve the robustness of deep neural networks against adversarial attacks. We implemented and evaluated four adversarial attacks (PGD, FGSM, BIM, and DeepFool) and three defensive techniques (Adversarial Training, Defensive Distillation, and Adversarial Logit Pairing) on the MNIST dataset.

## Overview

- Dataset: MNIST
- Model: CNN inspired by LeNet-5 architecture
- Adversarial Attacks: PGD, FGSM, BIM, DeepFool
- Defensive Techniques: Adversarial Training, Defensive Distillation, Adversarial Logit Pairing (ALP)

## Key Findings

- Adversarial Training and ALP were the most effective defenses
- Trade-off observed between robustness and accuracy on clean data
