# Fruit-classifier-using-CNN
Train a model using CNN 
Overview
This project implements a Convolutional Neural Network (CNN) to identify and classify different types of fruits from images. It aims to demonstrate the practical use of deep learning in computer vision, with applications in agriculture, retail automation, and fruit sorting systems.

Key Features
Dataset: Utilizes a curated dataset (e.g. Fruits‑360 or custom images) featuring multiple fruit categories—commonly apple, banana, mango, orange, pineapple, etc.

Preprocessing: Images normalized and resized to dimensions such as 100×100 or 224×224 pixels; includes optional data augmentation (rotation, flip, color jitter).

Model Architecture:

2–3 convolutional layers with ReLU activation (e.g., 32–64 filters, kernel 3×3 or 5×5)

Max pooling layers after conv layers

Dropout layers (e.g. rate 0.25–0.5) to reduce overfitting

One or two fully connected (dense) layers ending with softmax for classification

Training:

Optimizer: Typically Adam or SGD

Loss function: Categorical Cross‑Entropy

Trained over multiple epochs (e.g. 10–25), with batch sizes varying by experiment

Performance: Achieves high accuracy (often > 95%) on training and validation/test sets, depending on data and architecture.

Implementation Stack
Programming Language: Python

Deep Learning Framework: TensorFlow / Keras (or PyTorch if specified)

Development Tools: Jupyter Notebooks for experiments; Streamlit or Flask for simple demos (if included)

Dependencies: Listed in requirements.txt (e.g., numpy, matplotlib, tensorflow, opencv)
