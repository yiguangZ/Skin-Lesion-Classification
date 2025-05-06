
# 🩺 Skin Lesion Classification with CNN and VGG16 (HAM10000 Dataset)

This project utilizes the HAM10000 dataset—a large collection of dermatoscopic images of skin lesions—to build and compare two deep learning models: a custom Convolutional Neural Network (CNN) and a fine-tuned VGG16 model.

## 🎯 Objective

- Train a custom CNN and a fine-tuned VGG16 model to classify images of skin lesions into seven diagnostic categories.
- Compare the classification performance of both models on the HAM10000 dataset.
- Contrast the results with previous experiments using the wafer map dataset.

## 🧰 Features

- Preprocessing of directory-based image dataset
- Custom PyTorch dataset class for HAM10000
- Custom CNN implementation from scratch
- Transfer learning using pre-trained VGG16
- Training and validation pipelines
- Performance evaluation with accuracy and loss metrics

## 📂 File Structure

- `ECE_157A_272A_F24_Homework3_HAM10000_nn_undergraduate.ipynb`: Main notebook with training, evaluation, and comparison code
- `ham10000/`: Folder (after unzipping) containing labeled image directories
- `README.md`: Overview and setup instructions

## 📦 Dependencies

- torch
- torchvision
- pandas
- numpy
- matplotlib
- sklearn
- PIL

## 🚀 How to Run

1. Download and unzip the HAM10000 dataset from [this UCSB Box link](https://ucsb.box.com/shared/static/vz9pmd1h7eexf2qxr5odvjy0xew5aqpo.zip).
2. Place the unzipped folder in your working directory.
3. Run all cells in the notebook to preprocess, train, and evaluate both models.

## 👤 Author

Yiguang Zhu (ECE 157A/272A Fall 2024)
