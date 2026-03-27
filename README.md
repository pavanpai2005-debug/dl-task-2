Deep Learning Assignment 2:
CNN, RNN, and GAN (Applied Models)
This project focuses on implementing important deep learning architectures using PyTorch. It covers three main areas: image classification, sequence prediction, and image generation.
________________________________________
Models Developed
1. Convolutional Neural Network (CNN) – Image Classification
•	Dataset Used: Fashion-MNIST 
•	Designed a custom CNN architecture including: 
o	Convolutional layers 
o	ReLU activation 
o	Pooling layers 
o	Dropout for regularization 
•	Also applied transfer learning using a pretrained ResNet18 model 
•	Results: 
o	Achieved around 91% accuracy 
o	Generated a confusion matrix 
o	Plotted training loss curves 
________________________________________
2. Recurrent Neural Network (RNN) – Time Series Forecasting
•	Dataset Used: Artificial sine wave data 
•	Implemented and compared three models: 
o	Basic RNN 
o	LSTM (Long Short-Term Memory) 
o	GRU (Gated Recurrent Unit) 
•	Results: 
o	Compared models using RMSE (Root Mean Square Error) 
o	Visualized training loss for each model 
________________________________________
3. Generative Adversarial Network (GAN) – Image Generation
•	Dataset Used: Fashion-MNIST 
•	Built two main components: 
o	Generator (creates images) 
o	Discriminator (evaluates images) 
•	Used alternating training strategy (training discriminator and generator step-by-step) 
•	Results: 
o	Generated sample images 
o	Displayed training loss graphs 
________________________________________
Performance Summary
•	CNN Accuracy: ~91% 
•	RNN RMSE: 0.0370 (best performing model) 
•	LSTM RMSE: 0.1052 
•	GRU RMSE: 0.1097 
•	GAN: Generated images improved gradually over training epochs 
________________________________________
Requirements
Install the required libraries using:
pip install torch torchvision matplotlib scikit-learn
________________________________________
Execution Steps
1.	Clone or download the project repository 
2.	Open the project directory 
3.	Start Jupyter Notebook:
jupyter notebook
4.	Open the .ipynb file 
5.	Run all cells in order: 
o	Go to Kernel → Restart & Run All 
________________________________________
Generated Outputs
•	CNN accuracy results and confusion matrix 
•	Loss curves for CNN, RNN, LSTM, GRU, and GAN 
•	Generated images stored in the gan_images/ folder 
•	Comparative performance results 
________________________________________
Additional Notes
•	The ResNet18 model is used in pretrained mode and not fully fine-tuned due to limited CPU resources 
•	GAN training is kept short (few epochs) to ensure faster execution

