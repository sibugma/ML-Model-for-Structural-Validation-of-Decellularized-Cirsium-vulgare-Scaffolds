# ML-Model-for-Structural-Validation-of-Decellularized-Cirsium-vulgare-Scaffolds
Overview

This repository contains code for the machine learning model developed to assess the structural similarity of Cirsium vulgare scaffolds to human bone tissue. Using SEM images, the model aids in pre-screening scaffold suitability for bone tissue engineering applications.
Model Architecture

    Feature Extraction: Pre-trained VGG16 model (top layers removed for transfer learning).
    Classification Layers: Dense layers with ReLU and sigmoid activation, with dropout for regularization.
    Training Data: 918 SEM images (459 bone, 459 non-bone), augmented for robustness.

Performance

    Accuracy: 95.1%
    F1 Score: 96.1%
    Confusion Matrix: High accuracy in distinguishing bone and non-bone structures.

Requirements

    Python 3.6
    TensorFlow 1.8.0
    Keras 2.1.6
