# MNIST GAN — Generate Handwritten Digits

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) trained to generate realistic handwritten digits from the MNIST dataset. All components — including data loading, model definitions, training loop, and visualization — are contained in a single, well-organized Jupyter Notebook.

---

## Project Structure

- `DCGAN_MNIST_digit_generation.ipynb` — Full project implementation, including:
  - Generator and Discriminator models
  - Adversarial training loop
  - TensorBoard logging
  - Sample image generation and visualization

---

## Results

After training for approximately 50–100 epochs, the Generator produces realistic handwritten digits across all classes.  
Sample improvement over training:

| Early Epochs | Later Epochs |
|:------------:|:------------:|
| ![epoch_001](generated_samples/epoch_001.png) | ![epoch_050](generated_samples/epoch_050.png) |

Digits sharpen and become more structured as training progresses.

---

## Key Features

- Deep Convolutional Generator and Discriminator networks
- Label smoothing for improved Discriminator stability
- Careful learning rate tuning for Generator and Discriminator
- TensorBoard integration for live training monitoring
- Image sampling every few epochs to visualize Generator improvement

---

## Requirements

Install the necessary dependencies with:

```bash
pip install -r requirements.txt

