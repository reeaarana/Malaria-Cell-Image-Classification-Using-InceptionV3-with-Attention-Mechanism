# Malaria Cell Image Classification Using InceptionV3 with Attention Mechanism

This repository provides a comprehensive solution for classifying malaria-infected and uninfected cell images using a hybrid deep learning architecture based on the InceptionV3 model and an attention mechanism. The project leverages transfer learning, data augmentation, and a customized attention module to enhance the model's capability in focusing on critical regions of the images. By combining the powerful feature extraction capabilities of InceptionV3 with multi-head self-attention, this approach delivers robust performance for medical image analysis tasks.

The dataset used in this project is the publicly available "Cell Image Classification" dataset, which contains images labeled as either "Parasitized" or "Uninfected." The pipeline includes efficient preprocessing, data stratification, and augmentation to ensure balanced training and testing splits.

![image](https://github.com/user-attachments/assets/a117115a-74c5-452c-bc87-d771874cfaa5)

Key features include:

Use of Multi-Head Attention to improve feature representation.
Incorporation of Gaussian Noise and Dropout layers for regularization.
Transfer learning with pre-trained InceptionV3 layers to boost accuracy on small datasets.
Visualization of training progress through loss and accuracy graphs.

![image](https://github.com/user-attachments/assets/bb824b34-2150-4ac5-b021-1b90a1dbc6c3)
