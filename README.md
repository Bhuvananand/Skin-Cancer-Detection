# Skin-Cancer-Detection
The Skin Cancer Detection Project aims to develop a deep learning model capable of accurately classifying skin lesion images into benign (non-cancerous) and malignant (cancerous) categories. Skin cancer is one of the most common types of cancer, and early detection plays a critical role in improving patient outcomes. This project leverages state-of-the-art deep learning techniques to assist dermatologists in diagnosing skin cancer more effectively.
## Dataset used
The dataset used in this project is the [Skin Cancer: Malignant vs. Benign](https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign) dataset.
This dataset contains a balanced dataset of images of benign skin moles and malignant skin moles from ISIC-Archive.
## Model Architecture
The skin cancer detection model is based on a pre-trained convolutional neural network (CNN) architecture. The model leverages transfer learning by using a pre-trained model, Xception-CNN as a feature extractor. The extracted features are then fed into fully connected layers for classification.
![image](https://github.com/Bhuvananand/Skin-Cancer-Detection/assets/135426406/f07432e7-4156-484e-9390-077e240d05de)
