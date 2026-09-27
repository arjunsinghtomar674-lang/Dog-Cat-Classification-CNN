# 🐱🐶 Dog vs Cat Classification using CNN

This project uses a Convolutional Neural Network (CNN) to classify images into two classes:

- Cat
- Dog

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pillow
- Jupyter Notebook

## Project Workflow

Image Dataset
→ Image Preprocessing
→ CNN
→ Model Training
→ Model Evaluation
→ New Image
→ Prediction

## Input

A cat or dog image.

## Output

The model predicts whether the image is:

- Cat
- Dog

## Image Preprocessing

Images are resized to 128 × 128 pixels and normalized by dividing pixel values by 255.

## Model

A Convolutional Neural Network is used for binary image classification.

## Prediction

The trained model can be used to predict new images.

## Project Structure

```text
Dog-Cat-Classification-CNN/
│
├── Cat-vs-Dog-Classification.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
├── model/
│   └── dog_cat_cnn.keras
│
└── sample_images/
    ├── cat.jpg
    └── dog.jpg