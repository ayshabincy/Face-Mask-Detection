# Face-Mask-Detection using Deep Learning
This project aims to develop a deep learning model to detect whether a person is wearing a mask or not from images using Convolutional Neural Networks (CNNs). The model can be deployed in various applications to enforce mask-wearing policies, enhance safety in public spaces, and mitigate the spread of contagious diseases.

# Overview
With the ongoing COVID-19 pandemic, wearing masks has become a crucial preventive measure to reduce virus transmission. Automated mask detection systems can assist in enforcing mask-wearing guidelines in public spaces, workplaces, and healthcare facilities. In this project, we leverage CNNs, a class of deep learning models well-suited for image classification tasks, to detect the presence of masks in images.

# Key Features
Data Collection: Gather a dataset of labeled images containing people with and without masks, ensuring diversity in lighting conditions, angles, and backgrounds.

Data Preprocessing: Preprocess the images by resizing them to a standard size (e.g., 128x128 pixels) and normalizing pixel values to the range [0, 1].

Model Architecture: Build a CNN model consisting of convolutional layers followed by max-pooling layers to extract features from input images. The final layers are fully connected (dense) layers for classification.

Model Training: Split the dataset into training and testing sets. Train the CNN model on the training data using binary cross-entropy loss and the Adam optimizer.

Model Evaluation: Evaluate the trained model's performance on the test set using accuracy as the primary metric. Additionally, visualize the model's predictions on new images to assess its real-world applicability.
