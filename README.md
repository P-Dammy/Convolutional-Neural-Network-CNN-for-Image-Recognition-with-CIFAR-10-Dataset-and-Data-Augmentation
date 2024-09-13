# Convolutional Neural Network (CNN) for Image Recognition with CIFAR-10 Dataset and Data Augmentation

This project implements a **Convolutional Neural Network (CNN)** for image classification using the **CIFAR-10 dataset**. It explores various techniques to improve model accuracy, including **data augmentation** using Keras' `ImageDataGenerator`. The project demonstrates how augmentation can enhance model generalization by introducing diverse image variations during training.

## Introduction

In this project, a **CNN** is trained on the **CIFAR-10 dataset**, a popular dataset for image classification containing 60,000 32x32 color images in 10 classes. This CNN model is designed to classify these images into categories such as **airplane**, **car**, **bird**, **cat**, etc.

A key focus of this project is on improving model accuracy using **data augmentation**. Data augmentation is a technique that artificially enlarges the training dataset by creating modified versions of images through random transformations, such as rotations, shifts, and flips.

---

## Data Description

The **CIFAR-10 dataset** consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is split into 50,000 training images and 10,000 test images. Each image is labeled with one of the following categories:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

**Dataset Source:** The dataset is available as part of the `tensorflow.keras.datasets` module.

---

**Using Data Augmentation**

To further improve the model’s performance, data augmentation was applied using the ImageDataGenerator from the Keras library. Data augmentation generates new, slightly modified versions of images on the fly during training, which helps prevent overfitting and improves generalization to unseen data.
