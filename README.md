# Variational Autoencoders on CIFAR-10 Dataset

This repository contains the implementation of Variational Autoencoders (VAEs) trained on the CIFAR-10 dataset. VAEs are generative models that learn a low-dimensional latent representation of data, enabling the generation of new images.

# Table of Contents
- [Overview](#overview)
- [Dependencies](#dependencies)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

# Overview

Variational Autoencoders (VAEs) are a type of generative model that can learn a compact representation of data. In this project, we train VAEs on the popular dataset: CIFAR-10. The trained model is then evaluated based on its ability to generate realistic images and capture the underlying structure of the data.

# Dependencies

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- tqdm

# Data

The CIFAR-10 dataset contains 60,000 32x32 color images across 10 classes, with 6,000 images per class.

# Model

The project utilizes a Variational Autoencoder architecture, consisting of an encoder network that maps input images to a low-dimensional latent space, and a decoder network that reconstructs the original images from the latent space.

# Evaluation

The performance of the trained models is evaluated using Mean Squared Error (MSE) and Structural Similarity Index (SSIM) metrics, comparing the generated images with the original images. Additionally, t-SNE plots are used to visualize the learned latent space.

# Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/darshan8850/Variational-AutoEncoders-on-CIFAR10-Dataset.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Variational-AutoEncoders-on-CIFAR10-Dataset
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

# Usage

1. Run the `VAE CIFAR-10.ipynb` Jupyter Notebook file to train and evaluate the VAE models.

# Contribution

Contributions are welcome! If you'd like to contribute to this project, please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md).

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the content and layout of the README section to best suit your project's needs!
