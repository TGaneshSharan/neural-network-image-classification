# Neural Network Image Classification

## Project Overview

This project implements a Neural Network using PyTorch to classify handwritten digits.

The model is trained using pixel-based image data and predicts the digit represented by each image.

## Dataset

The dataset contains:

- 1,797 samples
- 64 pixel features
- 1 target column

Each image is represented using 64 pixel values corresponding to an 8 × 8 image.

The target contains handwritten digits from 0 to 9.

## Project Workflow

1. Load the dataset
2. Explore the dataset
3. Check missing values and duplicates
4. Visualize handwritten digit images
5. Separate features and target
6. Split the data into training and testing sets
7. Normalize pixel values
8. Convert the data into PyTorch tensors
9. Create a Neural Network
10. Train the model
11. Evaluate the model
12. Make predictions

## Neural Network Architecture

The Neural Network was implemented using PyTorch.

The architecture consists of:

- Input layer: 64 features
- Hidden layer: 128 neurons
- ReLU activation
- Output layer: 10 neurons

The 10 output neurons represent the digits from 0 to 9.

## Training

The model was trained for 10 epochs.

The following were used during training:

- Loss Function: Cross Entropy Loss
- Optimizer: Adam
- Learning Rate: 0.001

## Results

The trained Neural Network achieved an accuracy of approximately **93.33%** on the test data.

Example prediction:

- Predicted digit: 6
- Actual digit: 6

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- PyTorch
- Jupyter Notebook / Google Colab

## Project Files

- `ann.ipynb` — Complete Jupyter/Colab notebook containing the implementation
- `digits_dl_practice.csv` — Dataset used for the project

## Conclusion

A PyTorch-based Neural Network was successfully trained to classify handwritten digits using pixel-based image data. The model achieved approximately 93.33% test accuracy.
