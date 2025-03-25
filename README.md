# Rostro-AI

This project demonstrates how to train a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate images of human faces.

## Overview

Generative Adversarial Networks (GANs) offer a unique approach to generative modeling, where two neural networks, a Generator and a Discriminator, are trained in tandem. The generator creates "fake" samples from random noise, while the discriminator tries to distinguish between real samples from the training data and the fake ones produced by the generator.

This project uses a human face dataset to train the DCGAN.

## Project Structure

*   `rostro.ipynb`: Jupyter notebook containing the code for training the DCGAN.

## Getting Started

### Prerequisites

*   Python 3
*   PyTorch
*   Other common data science libraries (NumPy, Matplotlib, etc.)

### Running the Code

#### Option 1: Using Online Resources (Recommended)

1.  Click the "Run" button at the top of the notebook.
2.  Select "Run on Colab" to execute the code on Google Colab (free online platform with GPU support).

#### Option 2: Running Locally

1.  Download the notebook (`rostro.ipynb`).
2.  Install Conda: Instructions in the original notebook.
3.  Install the required libraries.  See the original notebook for specific library install instructions.
4.  Open the notebook using Jupyter Notebook or JupyterLab.

## Training

The notebook `rostro.ipynb` contains detailed instructions and code for training the DCGAN model. Key steps include:

1.  **Data Preparation:** Loading and preprocessing the human face dataset.
2.  **Model Definition:** Defining the Generator and Discriminator networks.
3.  **Training Loop:** Training the GAN by alternating between training the discriminator and the generator.
4.  **Visualization:**  Visualizing the generated images during training.
