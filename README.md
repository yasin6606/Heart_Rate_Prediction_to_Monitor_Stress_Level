Deep Learning Stress Classification Project
# Overview
Welcome to the Deep Learning Stress Classification project! This repository contains a deep learning model designed to classify a dataset of **369,289 samples** into three distinct classes: ‘no stress,’ ‘interruption,’ and ‘time pressure.’ The classification is based on seven input features.

# Download Dataset and Reference
[Download Dataset on Kaggle](https://www.kaggle.com/datasets/vinayakshanawad/heart-rate-prediction-to-monitor-stress-level/data)
This dataset provides the necessary samples and features for training and testing the model.

# Model Architecture
The model utilizes **Multi-Layer Perceptron (MLP)** _networks_ to achieve high accuracy in classification tasks. The architecture consists of the following layers:

1. Input Layer: Accepts the seven features.
2. First Hidden Layer: 32 neurons.
3. Second Hidden Layer: 64 neurons.
4. Third Hidden Layer: 32 neurons.
5. Output Layer: 3 neurons (one for each class).

# Layer Details
* Activation Function: **ReLU (Rectified Linear Unit)** is employed after each hidden layer to introduce non-linearity into the model.
* Output Layer: The model’s final layer outputs probabilities for each of the three classes.

# Loss Function
For training, the model utilizes **CrossEntropyLoss** from PyTorch, which inherently includes a Softmax layer; hence, a separate Softmax layer is not required in the architecture.

# Performance Metrics
Upon evaluating the model on a test dataset of **41,034 samples**, it achieved impressive results:
* Accuracy: Approximately 97%
* Cross Entropy Loss: 0.08

# Conclusion
This project demonstrates the effectiveness of **MLP** _networks_ in classifying stress-related data based on specific features. The high accuracy indicates a strong model performance, making it a valuable tool for applications in psychological research and stress management.

# Getting Started
To get started with this project, clone the repository and follow the instructions in the documentation for setting up the environment and running the model.
### Required Packages
1. [torch](https://pypi.org/project/torch/)
2. [scikit-learn](https://pypi.org/project/scikit-learn/)
3. [pandas](https://pypi.org/project/pandas/)
4. [matplotlib](https://pypi.org/project/matplotlib/)
5. [tqdm](https://pypi.org/project/tqdm/)
6. [torchmetrics](https://pypi.org/project/torchmetrics/)

# Contact
Thank you for your interest in this project! If you have any questions or suggestions, feel free to reach out.

Email: [yassingourkani@outlook.com](yassingourkani@outlook.com)

LinkedIn: [Yasin LinkedIn](https://www.linkedin.com/in/yassingourkani/)
