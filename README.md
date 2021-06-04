# Glass vs No-Glass Classification
Pattern Recognition &amp; Machine Learning (CSL2050) Major Course Project Developed under the guidance of Dr. Richa Singh

## Data
- [Google Drive link](https://drive.google.com/drive/folders/1-3zxkbFzaMDwzBtJsi-De0nV41EqlFxc?usp=sharing)
- [Data from Kaggle competition](https://www.cs.toronto.edu/~kriz/cifar.html)

## Loading data?
Import Data from Kaggle. It has train features, train label and test labels. For MLP , KNN , SVM we can directly use these features (latent vectors). For CNN we produce images by Latent vector.

## How to Execute?
The collab notebook is written sequentially. Just run the blocks one by one. Some block may even take few hours to run.

## Structure of Code
The code is divided into multiple selection. 
- Dependencies & Data Loading (imoprt neccesary libraries and data)
- Data Preparation (Latent Vector to image. Separating these images into different directories with respect to their label and train/val/test.)
- Data Preprocessing (For images make training testing set by ImageDataGenerator. For latent vector split into train/test , standardized data and reduced dimentioned data.)
-  MLP , KNN , SVM (Three Classification model. Each model has 3 set {1. Noraml , 2. Dimensionality Reduction , 3. Feature selection})
-   CNN (A three layer CNN model for image classification)

