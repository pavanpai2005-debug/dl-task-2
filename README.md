Deep Learning Assignment 2:
CNN, RNN, and GAN (Applied Models)

This project focuses on implementing important deep learning architectures using PyTorch. It covers three main areas: image classification, sequence prediction, and image generation.

Models Developed
1. Convolutional Neural Network (CNN) – Image Classification
Dataset Used: Fashion-MNIST
Designed a custom CNN architecture including:
Convolutional layers
ReLU activation
Pooling layers
Dropout for regularization
Also applied transfer learning using a pretrained ResNet18 model
Results:
Achieved around 91% accuracy
Generated a confusion matrix
Plotted training loss curves
2. Recurrent Neural Network (RNN) – Time Series Forecasting
Dataset Used: Artificial sine wave data
Implemented and compared three models:
Basic RNN
LSTM (Long Short-Term Memory)
GRU (Gated Recurrent Unit)
Results:
Compared models using RMSE (Root Mean Square Error)
Visualized training loss for each model
3. Generative Adversarial Network (GAN) – Image Generation
Dataset Used: Fashion-MNIST
Built two main components:
Generator (creates images)
Discriminator (evaluates images)
Used alternating training strategy (training discriminator and generator step-by-step)
Results:
Generated sample images
Displayed training loss graphs
Performance Summary
CNN Accuracy: ~91%
RNN RMSE: 0.0370 (best performing model)
LSTM RMSE: 0.1052
GRU RMSE: 0.1097
GAN: Generated images improved gradually over training epochs
Requirements

Install the required libraries using:

pip install torch torchvision matplotlib scikit-learn
Execution Steps
Clone or download the project repository
Open the project directory

Start Jupyter Notebook:

jupyter notebook
Open the .ipynb file
Run all cells in order:
Go to Kernel → Restart & Run All
Generated Outputs
CNN accuracy results and confusion matrix
Loss curves for CNN, RNN, LSTM, GRU, and GAN
Generated images stored in the gan_images/ folder
Comparative performance results
Additional Notes
The ResNet18 model is used in pretrained mode and not fully fine-tuned due to limited CPU resources
GAN training is kept short (few epochs) to ensure faster execution
