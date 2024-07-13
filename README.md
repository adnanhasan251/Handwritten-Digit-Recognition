# Handwritten-Digit-Recognition

This project trains a neural network to recognize handwritten digits using the MNIST dataset. After training, the model can be used to predict digits from external 28x28 pixel images placed in the `digits` directory.

## Project Structure

- `train_model.py`: Script to train the model on the MNIST dataset.
- `digits/`: Directory where you can add your 28x28 pixel images for prediction.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages (see `requirements.txt`)

### Installing

1. Clone the repository:
    ```bash
    git clone https://github.com/adnanhasan251/Handwritten-Digit-Recognition.git
    cd Handwritten-Digit-Recognition
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Training the Model

1. Run the `train_model.py` script to train the neural network on the MNIST dataset:
    ```bash
    python train_model.py
    ```

2. The trained model will be saved as `handwritten_digits.keras`.

### Predicting Digits

1. Place your 28x28 pixel images in the `digits/` directory.

2. Run the `train_model.py` script to predict the digits in the images:
    ```bash
    python train_model.py
    ```

3. The script will output the predicted digits for each image in the `digits/` directory.

## Example

Add 28x28 pixel images into the `digits` directory and run the prediction script:
```bash
python train_model.py
