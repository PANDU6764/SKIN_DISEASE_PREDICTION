# SKIN_DISEASE_PREDICTION

# Skin Disease Prediction Using CNN

This project is a machine learning application that predicts skin diseases from images using a Convolutional Neural Network (CNN). It utilizes the [HAM10000 dataset from Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000?select=hmnist_8_8_RGB.csv), which contains over 10,000 dermatoscopic images of various skin lesions.

## Objective
The goal of this project is to automatically classify skin lesions into their respective disease categories to assist in early detection and diagnosis.

## Dataset
The HAM10000 dataset includes images labeled with the following skin lesion types:
- Actinic Keratoses
- Basal Cell Carcinoma
- Benign Keratosis
- Dermatofibroma
- Melanocytic Nevi
- Melanoma
- Vascular Skin Lesions

## Approach
1. **Data Preprocessing**: Images are resized, normalized, and split into training and testing sets.
2. **CNN Model**: A Convolutional Neural Network is trained to learn features from the images.
3. **Training & Evaluation**: The model is trained on the training set, and performance is evaluated using accuracy and loss metrics.
4. **Prediction**: Users can input a new image, and the model predicts the skin disease.

## Features
- Image-based skin disease classification
- High accuracy using CNN
- Easy to use with any skin lesion image input

## Installation
1. Clone the repository:
```bash
git clone https://github.com/PANDU6764/SKIN_DISEASE_PREDICTION.git
```
2. Navigate to the project directory:
```bash
cd SKIN_DISEASE_PREDICTION
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the main script:
```bash
python main.py
```
2. Upload a skin image when prompted to get the predicted disease type.

## Model Details
- Convolutional layers with ReLU activation
- MaxPooling layers
- Dense layers for classification
- Softmax output layer for multi-class classification

## Contributing
Feel free to fork the project, raise issues, or submit pull requests to improve the application.

## License
This project is licensed under the MIT License.

---
This README is structured so that others can easily understand your project, the dataset used, and how the CNN model works.
