# Skin-Cancer-Detection
The Skin Cancer Detection Project aims to develop a deep learning model capable of accurately classifying skin lesion images into benign (non-cancerous) and malignant (cancerous) categories. Skin cancer is one of the most common types of cancer, and early detection plays a critical role in improving patient outcomes. This project leverages state-of-the-art deep learning techniques to assist dermatologists in diagnosing skin cancer more effectively.
## Dataset used
The dataset used in this project is the [Skin Cancer: Malignant vs. Benign](https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign) dataset.
This dataset contains a balanced dataset of images of benign skin moles and malignant skin moles from ISIC-Archive.
## Model Architecture
The skin cancer detection model is based on a pre-trained convolutional neural network (CNN) architecture. The model leverages transfer learning by using a pre-trained model, Xception-CNN as a feature extractor. The extracted features are then fed into fully connected layers for classification.

![image](https://github.com/Bhuvananand/Skin-Cancer-Detection/assets/135426406/f07432e7-4156-484e-9390-077e240d05de)
## Data Preprocessing
The images that we have chosen has a standard size of 224×224. These images are cropped and converted to grayscale for better representation of lesions which in turn aids in better feature extraction when passed into CNN. Further, the thin and think hair present in the image are removed using DullRazor algorithm which performs morphological scaling hence displaying the darker hairy regions of skin. Gaussian filter is applied to the images which removes the noise and later another morphological operation called blackhat filter is used which enhances and extracts dark or small structures from an image. Thus, the resulting outputreceived are clear images free from hair.

Before training the model, the skin lesion images are preprocessed to enhance the model's performance. The preprocessing steps include resizing images to a standard size, data augmentation, normalization, and splitting the data into training and validation sets.

![image](https://github.com/Bhuvananand/Skin-Cancer-Detection/assets/135426406/ad9a6d41-59eb-4446-8b66-480350351cd0)
## Results
The performance and results of the skin cancer detection model are presented in the "Results" section of the notebook.
This includes metrics and visualizations showing how the model performs in classifying benign and malignant skin lesions.
