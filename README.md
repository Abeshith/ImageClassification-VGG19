# Vegetable Image Classification using VGG19

## Project Overview
This project focuses on classifying images of vegetables into 15 distinct categories using the VGG19 architecture. VGG19 is a Convolutional Neural Network (CNN) that has been pre-trained on the ImageNet dataset and fine-tuned for this specific task.

## Key Components

### Dataset
- The dataset contains images of 15 different vegetables.
- Images are divided into training, validation, and test sets.
- Preprocessing is applied to all images before feeding them into the model.

### Model Architecture
- **VGG19**: A powerful pre-trained CNN model originally designed for large-scale image classification tasks.
- **Transfer Learning**: The VGG19 model is fine-tuned for this classification task by adding custom layers on top of the pre-trained network.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- Streamlit

## Usage
- The model is deployed using Streamlit for easy interaction and classification of uploaded images.
- Users can upload an image of a vegetable, and the model will predict the vegetable's class.

## How to Run
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit app with `streamlit run app.py`.
4. Upload a vegetable image to get the prediction.

## Results
- The model accurately classifies the uploaded vegetable images into one of the 15 categories.

