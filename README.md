# Disease-Detection-in-Finger-Millet-Using-Deep-Learning
This project detects six types of diseases in finger millet using VGG16.

## Dataset
The dataset consists of 6 classes:
- Downy
- Healthy
- Mottle
- Seedling
- Smut
- Wilt

Download the dataset from [Google Drive](https://drive.google.com/file/d/1-TPd87xN2y7eZNeMbwj25XCP_W4GaEJn/view?usp=sharing)

- File: `ragidataset.zip`
- Structure: Contains 6 folders (`downy`, `healthy`, `mottle`, `seedling`, `smut`, `wilt`)

Each class is stored in a separate folder. Used via Google Drive in Colab.

## Model
- Pretrained **VGG16** from Keras
- Fine-tuned with ImageDataGenerator
- Accuracy achieved: **85%**

## How to Run
1. Mount Google Drive in Google Colab
2. Place dataset in: `MyDrive/Ragi/ragi dataset`
3. Run all cells in `finger_millet_vgg16.ipynb`
