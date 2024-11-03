# Breast Cancer Classification using Deep Learning

This project is a comparative analysis of four CNN models (DenseNet, VGG16, ResNet50, and MobileNetV2) for classifying breast ultrasound images as either benign or malignant. By leveraging these models, the goal is to improve diagnostic accuracy for breast cancer.

## Project Overview

Breast cancer is one of the most common cancers, and early detection is crucial for successful treatment. This project applies four pre-trained CNN models (DenseNet121, VGG16, ResNet50, and MobileNetV2) to classify breast ultrasound images into two categories: benign and malignant. A key focus is on achieving high classification accuracy by comparing these models' performance on the dataset.

## Dataset

Breast cancer is one of the most common causes of death among women worldwide. Early detection helps in reducing the number of early deaths. This dataset includes medical images of breast cancer using ultrasound scans, categorized into three classes: normal, benign, and malignant. Breast ultrasound images can produce great results in classification, detection, and segmentation of breast cancer when combined with machine learning.

Dataset Link : https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset/data
### Data

The data collected at baseline include breast ultrasound images among women in ages between 25 and 75 years old. This data was collected in 2018 and includes images from 600 female patients. The dataset consists of 780 images with an average image size of 500x500 pixels, stored in PNG format. Ground truth images are provided alongside original images for reference. The images are categorized into three classes: normal, benign, and malignant.
### Dataset Samples
![sample images](https://github.com/user-attachments/assets/3ca0aae5-c63f-4ca5-b934-faa05dffc06b)

## Evaluation and Visualization
The DenseNet121 model achieved an accuracy of 84% on the test dataset, demonstrating its effectiveness in classifying breast ultrasound images as either malignant or benign. Its architecture, which promotes feature reuse, enhances its performance in this task.
![graph](https://github.com/user-attachments/assets/ca542c25-f7f6-4684-b6b7-cd08e1ceebab)


## Result

Prediction Using DenseNet121 Model
![DenseNet121 model](https://github.com/user-attachments/assets/a0fdde2d-60db-42a0-870f-96aa772488d5)

Prediction Using VGG16 Model
![VGG16 model](https://github.com/user-attachments/assets/123d7bf7-06b9-4195-b7c4-dd3825140815)

Prediction Using ResNet50 Model
![ResNet50 model](https://github.com/user-attachments/assets/71eb5573-5bcd-457a-9846-1176e7ad3b44)

Prediction Using MobileNetV2 Model
![MobileNetv2 model](https://github.com/user-attachments/assets/eb52f4da-a92a-4c67-bfc5-624240647bd1)
