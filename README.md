# Multi-fidelity-Data-Fusion-for-In-elastic-Woven-Composites
  Surrogate Deep Learning for Homogenization of Woven Composites

This repository contains the code and datasets for our research on surrogate deep learning models for homogenizing meso-scale woven composites. Our approach integrates transfer learning with gated recurrent neural networks (GRUs) to efficiently predict elasto-plastic mechanical behavior while reducing computational costs.

Key Features:
Multi-Fidelity Learning: Combines low-fidelity mean-field homogenization (MFH) data with high-fidelity full-field simulation (FFT) data to enhance model accuracy.
Temporal Correlation Awareness: Captures the time-dependent path-dependent behavior of non-linear materials, essential for stress-strain predictions.
Dataset Generation & Augmentation: Utilizes diverse loading conditions (random walking & proportional cyclic loading) and employs linear interpolation for data augmentation.
Efficient Transfer Learning: Leverages knowledge from coarse-grained models to improve predictions with limited high-fidelity data.
Results & Impact:
Our framework enables accurate and efficient surrogate modeling of woven composites, significantly improving computational efficiency while preserving fidelity. The provided code allows for training, fine-tuning, and evaluating models under different loading scenarios.

🔗 Usage Instructions & Installation: See docs/installation.md

📄 Full Paper & Methodology: 
E. Ghane, M. Fagretrsöm, M. Mirkhalaf, ``Multi-fidelity Data Fusion for In-elastic Woven Composites: Combining Recurrent Neural Networks with Transfer Learning,'' (under review), 2024.

Contributions and discussions are welcome! 🚀
