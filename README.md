# Food Recognition Using MobileNetV2

## Project Overview
A deep learning project that classifies images into two categories: Food and Non-Food using MobileNetV2 Transfer Learning.

## Dataset
Food-5K Dataset – 5,000 images.

- Training: 3,000 images
- Validation: 1,000 images
- Evaluation: 1,000 images

[Dataset Link](https://www.kaggle.com/datasets/trolukovich/food5k-image-dataset)

## Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Matplotlib
- Google Colab

## Model Architecture
- Pretrained MobileNetV2
- Data Augmentation
- Global Average Pooling
- Dropout
- Sigmoid Output Layer

## Project Files
- `Food_Recognition_Using_MobileNetV2.ipynb` – Training notebook
- `food_recognition_model.keras` – Trained model
- `food5k_training_graph.png` – Training graph
- `requirements.txt` – Dependencies

## Results
See the notebook for actual evaluation accuracy and loss.

## Note
This model performs binary classification (Food vs Non-Food). It does not identify specific dishes or estimate calories.
