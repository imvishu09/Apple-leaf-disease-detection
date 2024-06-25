# Plant Disease Classification using TensorFlow

This repository implements a plant disease classification system using a Convolutional Neural Network (CNN) with TensorFlow. The model is trained on the PlantVillage dataset, specifically focusing on categorizing images of apple leaves into four classes: Apple scab, Black rot, Cedar apple rust, and Healthy.

## Requirements

Ensure you have the following dependencies installed:

- TensorFlow
- Matplotlib
- NumPy

You can install them using pip:

```bash
pip install tensorflow matplotlib numpy
```

## Dataset

The dataset used is structured as follows:

```
PlantVillage2/
    Apple___Apple_scab/
    Apple___Black_rot/
    Apple___Cedar_apple_rust/
    Apple___healthy/
```

## Model Architecture

The CNN model architecture includes:

- Convolutional layers with ReLU activation
- MaxPooling layers
- Dense (Fully Connected) layers with ReLU activation
- Output layer with Softmax activation

## Training

The model is trained for 50 epochs with a batch size of 32. Training and validation accuracy and loss are monitored and plotted during the training process.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/imvishu09/Apple-leaf-disease-detection.git
   ```

2. Organize the PlantVillage dataset under `PlantVillage2/` directory.

3. Start training:

   ```bash
   python train.py
   ```

---

This summary should give a clear and structured overview of your project, from requirements and dataset organization to model architecture and training specifics. If you need further details or adjustments, feel free to ask!
