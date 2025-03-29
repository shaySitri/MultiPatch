# Multi-Orientation Adversarial Patch 🛡️

[![🚀 Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1q7P3rQt5di3NT-V2iR0xGsEKHqw7LXm6?usp=sharing)

This repository explores the creation and evaluation of adversarial patches for deep learning models, focusing on targeted attacks and the impact of patch rotation.

## Description 📝

The notebook investigates two methodologies for generating adversarial patches:

1. **Projected Gradient Descent (PGD)**: This approach iteratively adjusts the patch's design using gradients to optimize its misleading effect.
2. **Fast Gradient Sign Method (FGSM)**: This method focuses on rapid updates based on gradient signs, enabling efficient patch optimization.

Both techniques aim to create patches that can manipulate a model's classification output by causing misclassifications, even when rotated at various angles (90°, 30°, 60°, 360°).

## Experiments 🔬

The notebook includes a range of experiments, including:

- **Baseline Patch Evaluation:** Tests patches with no rotation to understand their basic effectiveness.
- **Rotation Effects:** Investigates how rotations affect the attack's success, focusing on specific class targets.
- **Patch Shape Evaluation:** Compares the performance of square patches and circular patches in the attacks.

## Results 📊

The notebook provides detailed results of the experiments, including:

- Accuracy and top-5 accuracy metrics for the attacks under rotations.
- Visualizations of the generated adversarial patches.
- Analysis of the impact of patch size and shape on attack performance.

## Insights ✨

The results highlight the effectiveness of adversarial patches and how rotations significantly influence their performance. The experiments demonstrate the challenges and nuances of applying adversarial attacks using rotated patches.
