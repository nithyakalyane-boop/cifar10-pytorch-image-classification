
# CIFAR-10 Image Classification Using PyTorch

## Project Overview
Built a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset into 10 object categories.

## Objectives
- Load and preprocess image data using torchvision.
- Build a CNN with convolutional, activation, pooling, and fully connected layers.
- Train the model using Cross-Entropy Loss and the Adam optimizer.
- Evaluate model performance on the test dataset.
- Visualize predictions and analyze classification results.

## Dataset
CIFAR-10 contains 60,000 color images of size 32x32 pixels across 10 classes:
airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

## Model Architecture
- Convolutional layers
- Batch normalization (if implemented)
- ReLU activation
- Max pooling
- Fully connected layers
- Cross-Entropy Loss
- Adam optimizer

## Results
- Test accuracy: 62.57%
- Training epochs: 20
- Evaluation: Test-set loss and classification accuracy

## How to Run
1. Open `CIFAR10_CNN.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Allow torchvision to download CIFAR-10 when needed.
4. Review training metrics and test predictions.

## Future Improvements
- Add data augmentation.
- Compare different CNN architectures.
- Analyze per-class precision, recall, and confusion matrix.
- Experiment with learning rates and regularization.

## Author
Nithyakalyane Rengasamy
