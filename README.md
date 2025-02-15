# Multi-Label Classification with FastAI 🖼️🤖

This project demonstrates **multi-label classification** using the **FastAI** library on the **PASCAL 2007** dataset. The goal is to classify images into multiple categories using a **ResNet18** model. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **FastAI** to build and train a multi-label classification model. 🤖📸
- Leverages the **PASCAL 2007** dataset for training and validation. 🧠🔍
- Implements data augmentation, normalization, and evaluation using accuracy metrics. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install fastai
!pip install torch torchvision
!pip install pandas matplotlib
```

---

## Usage 🖥️

1. **Load Dataset**: The script loads the PASCAL 2007 dataset using FastAI's data block API.
2. **Preprocess Data**: Applies data augmentation, resizing, and normalization.
3. **Build Model**: Uses a pre-trained ResNet18 model for multi-label classification.
4. **Train Model**: Fine-tunes the model using the `fit_one_cycle` method.
5. **Evaluate Results**: Evaluates model performance using accuracy metrics.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Loads the PASCAL 2007 dataset and prepares it for training.
  - Defines data loaders, transformations, and normalization.

- **Model Definition**:
  - Uses a pre-trained ResNet18 model for multi-label classification.
  - Implements binary cross-entropy loss for multi-label classification.

- **Training**:
  - Fine-tunes the model using the `fit_one_cycle` method.
  - Tracks training metrics and evaluates model performance.

- **Evaluation**:
  - Uses accuracy metrics to evaluate model performance.
  - Visualizes training progress and model predictions.

---

## Results 📊

- **Training Accuracy**: The model achieves high accuracy in multi-label classification.
- **Accuracy Metrics**: The model's performance is evaluated using accuracy metrics.
- **Visualization**: Displays training progress and model predictions.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1: train_loss=0.123, val_loss=0.045, accuracy=0.987
Epoch 2: train_loss=0.045, val_loss=0.032, accuracy=0.991
```

---

## Dependencies 📦

- `fastai`
- `torch`
- `torchvision`
- `pandas`
- `matplotlib`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
