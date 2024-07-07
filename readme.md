# Balinese Mask Classification using VGG16

This repository contains the code for a deep learning project aimed at classifying Balinese mask images into seven different categories using the VGG16 architecture.

## Overview

In this project, we leverage the power of deep learning to classify Balinese masks based on their visual features. The dataset consists of images categorized into seven classes: bujuh, dalem, keras, penasar, sidakarya, tua, and wijil. We used transfer learning with the VGG16 model pre-trained on ImageNet to achieve high accuracy and efficiency.

## Project Structure

- **`balinese-mask/`**: Contains the dataset downloaded from Kaggle (not included in this repository).
- **`dataset/`**: Contains the preprocessed dataset divided into train, valid, and test sets (not included in this repository). Users need to generate this by running `data_preprocessing.ipynb`.
- **`data_preprocessing.ipynb`**: Jupyter notebook for data preprocessing and splitting the dataset into train, valid, and test sets.
- **`training_model.ipynb`**: Jupyter notebook for training the VGG16 model.
- **`best_model.h5`**: The trained model saved in HDF5 format.

## Getting Started

### Installation

Follow these steps to set up the environment and install the necessary dependencies for the project:

1. **Clone the Repository**:

   First, clone the repository from GitHub to your local machine:

   ```bash
   git clone https://github.com/your-username/balinese-mask-classification.git
   cd balinese-mask-classification

2. **Install the Required Packages**:

   Install the required Python packages using pip and the requirements.txt file:

   ```bash
   pip install -r requirements.txt

## Data Preparation

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/suryapradana/balinese-mask) and place it in the       `balinese-mask/` folder.

2. Run the `data_preprocessing.ipynb` notebook to preprocess the dataset and split it into train, valid, and test sets. This will create the `dataset/` folder with the preprocessed data.

## Training

1. Open and run the `training_model.ipynb` notebook to train the VGG16 model on your dataset.

## Usage

### Data Preparation:

- Ensure your dataset is structured and labeled correctly.
- Run data_preprocessing.ipynb to preprocess the data and split it into train, valid, and test sets.

### Training:

- Run `training_model.ipynb` to train the VGG16 model on your dataset.
- Adjust hyperparameters as needed in the notebook.

## Results
Our model achieved outstanding results with an accuracy of 1.0 across all classes during validation. For detailed metrics and visualizations, refer to our Medium post.

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/suryapradana/balinese-mask).
