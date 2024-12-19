# Neural Network Project

## Overview
This repository showcases multiple stages of building and optimizing neural networks from scratch, implementing custom architectures, and adapting advanced models for image recognition tasks.

### Project Highlights
1. **Building a Neural Network from Scratch**
2. **Optimizing the Neural Network**
3. **Creating a Neural Network for Grayscale Alphabet and Number Image Recognition**
4. **Implementing VGG-13**

---

## Part 1: Neural Network from Scratch
In this part, a neural network (NN) is built from scratch using Python. The key specifications of the NN are:

### Neural Network Configuration
- **Input Neurons:** 7
- **Output Neurons:** 1
- **Activation Function (Hidden Layers):** ReLU
- **Activation Function (Output Layer):** Sigmoid (with BCEWithLogitsLoss for training)
- **Number of Hidden Layers:** 4
- **Dropout:** Enabled

### Features
- Implemented forward and backward propagation manually.
- Utilized dropout for regularization.
- Loss function: Binary Cross Entropy (BCE).


---

## Part 2: Optimizing the Neural Network
Building upon the initial implementation, optimization techniques were applied to improve the performance of the neural network:

### Optimization Techniques
1. **Learning Rate Schedulers:** Adjusted learning rate dynamically during training.
2. **Weight Initialization:** Improved convergence using methods like Xavier and He initialization.
3. **Batch Normalization:** Enhanced gradient flow for stable training.
4. **Advanced Optimizers:** Switched to optimizers like Adam and RMSProp.

---

## Part 3: Neural Network for Grayscale Alphabet and Number Recognition
This part extends the neural network to handle image classification tasks for grayscale images containing alphabets and numbers. 

### Dataset
- Grayscale images of size **28x28 pixels**.
- Contains **36 categories** (26 alphabets + 10 digits).
- Each category has **2,800 examples** (total: 100,800 samples).

### Features
- Input Layer adapted for **28x28=784** input features.
- Output Layer contains **36 neurons** for multi-class classification.
- Used **Cross-Entropy Loss** for multi-class predictions.

---

## Part 4: VGG-13 Implementation
The final part of the project implements the **VGG-13** architecture, a well-known convolutional neural network for image recognition tasks.

### Key Highlights
- Implemented VGG-13 using Python.
- Adapted the architecture for grayscale input images.
- Trained on the same alphabet and number dataset.
- Achieved significant performance improvements over custom NN implementations.

### Link For Dataset
- [Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)


---


## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- NumPy
- Matplotlib
- Torch (PyTorch)


---

## Results
- **Part 1:** Demonstrated the ability to build and train a neural network manually.
- **Part 2:** Achieved faster convergence and improved accuracy through optimization techniques.
- **Part 3:** Successfully recognized grayscale images of alphabets and numbers with custom NN.
- **Part 4:** Leveraged VGG-13 for state-of-the-art performance on the dataset.

## Acknowledgments
- Inspired by deep learning resources and documentation from PyTorch.
- VGG-13 reference paper: *Very Deep Convolutional Networks for Large-Scale Image Recognition.*

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
