# Nepali Currency Recognition Classifier

This repository contains code for a Nepali currency recognition classifier implemented in Python using TensorFlow and Keras.

## Overview

The classifier is based on a pre-trained VGG16 model with additional layers added for fine-tuning to the specific task of recognizing Nepali currency notes. It is trained on a dataset consisting of images of Nepali currency notes belonging to 7 different classes.

## Files

- `Nepali_Currency_Recognition_Classifier.ipynb`: Jupyter Notebook containing the code for the classifier.
- `currency_classifier_model.h5`: Saved model file containing the trained classifier model.
- `Prediction Checker/`: Folder containing test images for evaluating the classifier.

## Usage

1. **Training**: The notebook contains code for training the classifier. Simply run the notebook cells to train the model.

2. **Testing**: Once trained, you can test the classifier on new images by placing them in the `Prediction Checker/` folder and running the prediction code provided in the notebook.

## Dataset

Please note that the training dataset is not included in this repository due to its size. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/gauravneupane/nepali-rupees-collection). After downloading, extract the dataset and arrange the folder structure as follows:

```
dataset/
│
├── train/
│   ├── class_1/
│   ├── class_2/
│   ├── ...
│   └── class_n/
│
└── valid/
    ├── class_1/
    ├── class_2/
    ├── ...
    └── class_n/

```



Replace `class_1`, `class_2`, etc., with the actual class names or labels of the currency notes.

## Dependencies

- TensorFlow
- Keras
- Matplotlib
- NumPy

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.

