# Fine-Tune Vision Transformers for Emotion Classification

This project focuses on **fine-tuning Vision Transformers (ViT)** to classify human emotions based on facial images. The dataset consists of 800 images categorized into 8 classes: `anger`, `contempt`, `disgust`, `fear`, `happy`, `neutral`, `sad`, and `surprise`. The dataset is sourced from **Hugging Face**.

## Project Overview

The key components of this project include:
1. **Vision Transformers (ViT)**: A state-of-the-art model architecture used for image classification tasks, fine-tuned for this specific use case.
2. **Emotion Dataset**: A curated dataset of 800 facial images labeled with emotional categories.
3. **Fine-Tuning Process**: Optimization of the pre-trained ViT model for classifying emotions, using transfer learning techniques.

## Technologies Used
- **Python**: For implementing the fine-tuning process and running experiments.
- **Hugging Face Transformers**: To utilize pre-trained Vision Transformer models.
- **PyTorch**: For deep learning and model training.
- **Matplotlib & Seaborn**: For visualizing training metrics and results.

## Features
- **Fine-Tuning Vision Transformers**: Leverages transfer learning to adapt a pre-trained ViT model to the emotion classification task.
- **Multi-Class Emotion Detection**: Supports 8 distinct emotional classes.
- **Performance Metrics**: Evaluates the model using metrics like accuracy, precision, recall, and F1 score.

## Dataset
The dataset contains 800 labeled images distributed across 8 emotion categories:
- `anger`
- `contempt`
- `disgust`
- `fear`
- `happy`
- `neutral`
- `sad`
- `surprise`
