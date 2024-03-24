# CNN-image-classification
To identify and classify images as cats or dogs 

```markdown
# Cat and Dog Image Classification using Convolutional Neural Networks

This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs. The dataset consists of grayscale images resized to 128x128 pixels.

## Requirements

- Python (>=3.6)
- PyTorch (>=1.7.0)
- torchvision
- matplotlib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/cat_dog_classification.git
   ```

2. Install dependencies:

   ```bash
   pip install torch torchvision matplotlib
   ```

3. Organize your dataset:

   - Place your training images in the `/content/Cat_Dog_data/train` directory.
   - Place your test images in the `/content/Cat_Dog_data/test` directory.

4. Run the script:

   ```bash
   python cat_dog_classification.py
   ```

## Description

- `cat_dog_classification.py`: Main Python script containing the CNN model definition, training loop, and evaluation loop.
- `README.md`: This file, providing an overview of the project, setup instructions, and usage details.

## Architecture

The CNN model architecture consists of multiple convolutional layers followed by batch normalization, ReLU activation, and max-pooling operations. The final layers include fully connected layers and a softmax activation function for classification.

## Results

After training the model for 15 epochs, the accuracy on the test set reached approximately 85%. Further optimizations and adjustments can be made to improve the performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

