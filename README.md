# Deep-Learning-Assignment2
CNN + RNN + GAN (Applied Deep Models)

This project implements core deep learning models using PyTorch, covering image classification, sequence learning, and generative modeling.

---

## Models Implemented

### 1. CNN (Image Classification)
- Dataset: Fashion-MNIST
- Custom CNN with Conv + ReLU + Pooling + Dropout
- Transfer Learning using ResNet18
- Output: Accuracy (~91%), confusion matrix, loss curve

### 2. RNN (Time-Series Prediction)
- Dataset: Synthetic sine wave
- Models:
  - RNN
  - LSTM
  - GRU
- Output: RMSE comparison and loss curves

### 3. GAN (Image Generation)
- Dataset: Fashion-MNIST
- Generator + Discriminator architecture
- Alternating training (D then G)
- Output: Generated images and loss graphs

---

## Results Summary

- CNN Accuracy: ~91%
- RNN RMSE: 0.0370 (Best)
- LSTM RMSE: 0.1052
- GRU RMSE: 0.1097
- GAN: Generated images showing progressive improvement

---

## Requirements

Install the following libraries:
pip install torch torchvision matplotlib scikit-learn

---

## How to Run

1. Download or clone the repository:
   git clone <your-repo-link>

2. Open the project folder.

3. Launch Jupyter Notebook:
   jupyter notebook

4. Open the `.ipynb` file.

5. Run all cells sequentially:
   Kernel → Restart & Run All
   
---

## Outputs Included

- CNN accuracy and confusion matrix
- Training loss curves (CNN, RNN, LSTM, GRU, GAN)
- GAN generated images (`gan_images/` folder)
- Model comparison results

---

## Notes

- ResNet18 is used as a pretrained model and not fully trained due to CPU limitations.
- GAN training is limited to few epochs for faster execution.
