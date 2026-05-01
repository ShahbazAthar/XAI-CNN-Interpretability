# Explainable AI in CNN-based Image Classification

##  Overview
This project presents an ante-hoc Explainable AI (XAI) framework that integrates interpretability directly into CNN training. Unlike post-hoc methods, the model jointly learns spatial importance masks alongside classification.

##  Key Contributions
- Designed an ante-hoc XAI framework with joint optimization of classification and explanation
- Introduced causality-driven constraints: sufficiency, necessity, sparsity, and entropy-based loss terms
- Benchmarked against post-hoc XAI methods including Grad-CAM, ScoreCAM, and Guided Backpropagation

##  Tech Stack
- Python
- PyTorch
- OpenCV
- NumPy

##  Results
- MNIST: 97.12% accuracy with interpretable masks
- FER-2013: 60.62% accuracy
- Improved spatial precision and causal validity compared to baseline XAI methods

##  Project Status
 Code will be uploaded soon.  
This repository currently documents the methodology, experiments, and results from ongoing M.Tech thesis work.

##  Future Work
- Extension to RGB datasets
- Application to real-world domains (e.g., healthcare)
- Integration with advanced architectures

##  Contact
Feel free to connect via LinkedIn for discussion or collaboration.
