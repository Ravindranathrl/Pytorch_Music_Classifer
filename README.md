Music Genre Classifier using PyTorch
This repository contains the code and resources for a Music Genre Classification project using the GTZAN dataset. The goal of this project is to classify audio tracks into one of 10 different genres using a machine learning model built with PyTorch.

Features
Data Collection: The GTZAN dataset is used, which includes 10 genres: blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock. The dataset is downloaded and prepared using a set of scripts.
Data Loading: A custom data loader is implemented to handle audio files, applying various transformations and augmentations to improve the model's robustness.
Audio Augmentation: The project utilizes a series of audio augmentations such as noise addition, pitch shifting, and reverb to enhance the model's performance and generalization.
Model Training: The model is trained using PyTorch, leveraging techniques such as data augmentation, batch normalization, and learning rate scheduling.

