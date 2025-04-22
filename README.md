# Deepfake Detection Project

This project compares deep learning models like ResNet, ViT, and InceptionV3 for deepfake image detection. Using the same training setup, we tested accuracy with and without data augmentation. We also applied Integrated Gradients for explainability. Results show trade-offs between performance and interpretability, aiding better deepfake detection.

A concise implementation of our benchmark study on deepfake image detection.

This repository contains Jupyter notebooks for training, evaluating, and inferring six models under uniform settings, with explainability via Integrated Gradients.

---

Important Links
- *Research Paper*: https://drive.google.com/file/d/1on_rVulJUYvPSynlaRJvg6-wOMor4lhN/view?usp=sharing
- *Report*: https://docs.google.com/document/d/15tSKZ2_JNhHdEaploiR2i1_Huz7T9XoDMGuAnlxSv-o/edit?usp=sharing
- *Models & Scripts*: https://drive.google.com/drive/folders/1wN_Tf4OQJ_8rhi6GGYfpYYaCHpewjp9K?usp=sharing
- 
- *Datasets*:
  - https://huggingface.co/datasets/JamieWithofs/Deepfake-and-real-images 
  - https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images 

---

Repository Structure

├── With Augmentation/         # All the script files with augmentation
├── Without Augmentation/      # All the script files without augmentation
└── README.md       # Project overview (this file)
