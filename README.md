# NumNet

**NumNet** is a simple and effective neural network designed to classify handwritten digits using the MNIST dataset. Built with TensorFlow, it demonstrates core deep learning techniques for image classification.

## Features

* Classifies digits 0–9 from handwritten images
* Achieves **91% accuracy** on test data
* Built using TensorFlow and Keras
* Clean, efficient, and easy to understand

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/keneandita/numnet.git
   cd numnet
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

Run the training notebook cell by cell:

```
Training_Notebook.ipynb
```

## File Structure

```
NumNet/
├── Training_Notebook.ipynb    # Main training Notebook
├── NumNet.keras    # Exported Model
├── digits/    # where the test digits i made are stored
├── .gitignore
├── requirements.txt
└── README.md
```

## Requirements

* Python 3.7+
* TensorFlow
* NumPy
* Matplotlib (optional for visualization)

## Results

The model achieves a test accuracy of **91%**, providing a good baseline for handwritten digit classification tasks.
