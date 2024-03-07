# Project Overview
This project aims to develop an image colorization system using Generative Adversarial Networks (GANs) to convert fixed-size black and white images into colorized versions of the same dimensions. By training a GAN model on a dataset of grayscale images paired with their corresponding-colored counterparts, the project demonstrates the efficacy of GANs in generating realistic and visually pleasing colorizations. The system's potential applications span photography, digital art, and historical image restoration. Throughout the project, challenges in training are addressed, and strategies for improvement are explored. Overall, this research contributes to the advancement of image processing techniques, particularly in the domain of colorization, opening avenues for future exploration and application.

## Methodology
- **Data Preprocessing**: Converting grayscale images to L*a*b model.
- **GAN Model**:
  Generator: This network takes a random noise vector as input and generates a color image.
  Discriminator: This network aims to distinguish between real (ground truth color images) and fake (generated color images) produced by the generator.
- **Training**: Train the GAN in an adversarial manner. 
- **Colorization**: The trained generator can be used to colorize new grayscale images by providing a random noise vector as input, resulting in a realistic and detailed colorized image.

## Pre-Requisites
- Python 3.6+
- PyTorch 1.0+
- torchvision
- Numpy
- PIL (Python Imaging Library)

### Installation

1. Clone the repository:
git clone https://github.com/YourUsername/Image-Colorization-GAN-UNet.git

2. Navigate to the project directory:
cd Image-Colorization-GAN-UNet

3. Install the required dependencies:
pip install -r requirements.txt


### Dataset

The project utilizes a dataset of grayscale images for training. The dataset should be sufficiently large to effectively train the model. It is recommended to split the dataset into training and validation sets for model training and evaluation.

### Training the Model

To train the model, execute the training script with the appropriate dataset path and other training parameters. The script will guide you through setting up the generator and discriminator models, defining the loss functions, and training the model on your dataset.

## Results and Examples

The model should be capable of colorizing grayscale images with high realism upon successful training. The project includes examples of the model's output to showcase the quality of colorization achieved.

## Conclusion

This project demonstrates the potential of GANs, particularly when combined with the U-Net architecture, for the task of image colorization. By leveraging the strengths of both models, we can achieve high-quality, realistic colorization of grayscale images, opening up new possibilities for image processing and enhancement.

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit a pull request. 
:)
