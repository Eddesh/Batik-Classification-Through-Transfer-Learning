# Batik-Classification

https://drive.google.com/file/d/1GOGlxX3OVCwHzs1yzknMm0aepfV7KiFA/view?usp=sharing

## Project Overview
This project addresses the classification of Indonesian batik motifs using deep learning models. By leveraging both custom convolutional neural networks and pretrained models, the project aims to distinguish between different batik motifs with a focus on achieving high accuracy. The project utilizes a dataset containing images of batik motifs such as batik-parang, batik-megamendung, and batik-kawung.

### Dataset Description
The dataset consists of batik motif images classified into three categories: batik-parang, batik-megamendung, and batik-kawung. Each image is preprocessed to a resolution of 224x224 pixels. Data augmentation techniques were applied to expand the dataset and improve the model's generalization ability. The dataset is split into training, validation, and test sets for thorough model evaluation.

### Step 1: Data Preprocessing and Splitting
Images are resized and augmented to improve model robustness. Augmentations include rotations, shifts, and flips. The dataset is split into training, validation, and test sets, ensuring an unbiased evaluation of the model’s performance.

### Step 2: Model Training
The project involves training various models:
- Custom CNN Models: These models are built from scratch with layers such as Conv2D, MaxPooling, and Dense layers for feature extraction and classification.
- Transfer Learning Models: Pretrained models like VGG16, Xception, and InceptionV3 were fine-tuned on the batik dataset to leverage their feature extraction capabilities.

### Step 3: Evaluation and Analysis
Models are evaluated using metrics such as accuracy, precision, and loss on both training and validation sets. Confusion matrices and accuracy curves are used to analyze model performance and ensure the models are well-suited for the classification task.

## Testing
The models trained in this project include:
1. Custom CNN Model 1: A baseline model with basic convolutional and pooling layers, achieving moderate accuracy.
2. Custom CNN Model 2: An improved version with batch normalization and dropout, providing enhanced performance and stability.
3. Transfer Learning Models: VGG16, Xception, and InceptionV3, with Xception showing the highest accuracy on the test set.

## Author
Davin Edbert Santoso Halim, Felicia Andrea Tandoko, Steve Marcello Liem
