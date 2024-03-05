# Project Name: Fingerprint Presentation Attack Detection

## Overview
This project focuses on developing a Vision Transformer-based model for detecting presentation attacks on fingerprint biometrics. The model achieved a high accuracy rate of 95%, showcasing its effectiveness in classifying fingerprint images.

## Problem Addressed
Presentation attacks involve impostors attempting to deceive the system by using counterfeit fingerprints to gain unauthorized access. The implemented solution prevents such attacks, ensuring the security of fingerprint biometrics.

## Vision Transformer-based Model
### Working of Vision Transformer
- *Patch Embeddings:* Fingerprint images are divided into smaller patches, processed by the Vision Transformer.
- *Transformer Encoder:* A stack of transformer encoder layers captures complex spatial relationships.
- *Positional Encodings:* Retained positional information aids in fingerprint analysis.
- *Classification Head:* Results in a binary classification (real or fake) output.
- *Training and Optimization:* Parameters optimized through backpropagation, with fine-tuning strategies applied post-evaluation.

## Results
- *Dense Blocks:* Utilized DenseNet121 for efficient feature extraction.
- *Key Features:* Dense connectivity, parameter efficiency, and effective feature extraction contributed to competitive image classification.
- *Model Accuracy:* Achieved a 95% accuracy rate, surpassing the initial goal of 85%.
