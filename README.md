
# Brain Tumor Image Classification with VGG19

This project focuses on the prediction of brain tumors using MRI images. It leverages the power of deep learning, specifically the VGG19 model, to classify images as either having a brain tumor or not. The VGG19 model, pre-trained on the ImageNet dataset, is known for its robustness and high performance in image recognition tasks.

## Features

- **Data Preprocessing**: Utilizes OpenCV for image processing, including conversion to grayscale, Gaussian blur, thresholding, erosion, and dilation.
- **Data Augmentation**: Employs `ImageDataGenerator` to enhance the training dataset, helping the model generalize better.
- **VGG19 Model**: Utilizes the VGG19 architecture pre-trained on ImageNet, fine-tuned for the task of brain tumor classification.
- **High Accuracy**: Achieves an accuracy of approximately 89.1% on the test dataset.

## Setup Instructions

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zeerakb1/brain-tumor-classification.git
   ```

2. Navigate to the project directory:
   ```bash
   cd brain-tumor-classification
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project

- To run the project, follow the instructions provided in the source code. Typically, this involves preprocessing the data, training the model, and evaluating its performance on a test dataset.

