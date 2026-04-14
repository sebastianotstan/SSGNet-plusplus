SSGNet++

SSGNet++: Data-Efficient Medical Image Learning via Generative Augmentation and Ensemble Pseudo-Label Refinement

This repository will contain the official implementation of SSGNet++, a framework designed to improve medical image classification and segmentation performance under limited annotation settings.

SSGNet++ combines class-specific generative augmentation with semi-supervised pseudo-label refinement, enabling more robust learning from small or imbalanced datasets. The framework integrates multiple complementary strategies, including:

Class-specific synthetic data generation using StyleGAN3
Iterative pseudo-label training for segmentation tasks
Ensemble diversity through multi-base and multi-head architectures
Edge-aware refinement methods (e.g., DenseCRF, Joint Bilateral Filtering)
Feature-space refinement for improved pseudo-label consistency

The goal of this work is to improve data efficiency while maintaining stable and generalisable performance across multiple medical imaging benchmarks.

Status

This repository is currently a placeholder created to support the reproducibility statement of the associated manuscript.

The implementation code, training scripts, and experiment configurations will be made publicly available upon acceptance of the paper.

Planned contents

The full repository is expected to include:

Training pipelines for classification and segmentation tasks
StyleGAN3-based synthetic data generation scripts
Ensemble prediction framework (multi-base and multi-head)
Pseudo-label refinement modules
Experiment configuration files
Instructions for reproducing reported results
