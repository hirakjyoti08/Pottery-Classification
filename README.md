# Pottery-Classification
### Introduction

This project represents the collaborative efforts of a team of four individuals participating in a hackathon competition. The objective of this competition was to develop an AI model capable of accurately classifying pottery into five distinct categories.
### Problem Statement
The challenge presented in this competition involves creation of a custom pottery dataset and the subsequent classification of the pottery items into five distinct classes:
1. Clay Cups
2. Clay Dolls
3. Clay Flower Pots
4. Kalah
5. Saaki

The primary goal was to create an intelligent system that could effectively identify and assign the correct class label to various pottery items based on their visual characteristics.
***
### Dataset Creation
To build our pottery dataset, we employed a web scraping technique to collect images from various online sources. Each class was meticulously scraped, resulting in a comprehensive collection of pottery images. Our dataset comprised over 1700 items for training purposes and an additional 150+ items for testing.

By curating this extensive dataset, we aimed to ensure diversity and representativeness across the five pottery classes. This approach allowed us to train and evaluate our AI model effectively, enabling accurate classification and promoting generalization across different pottery variations.

For access to the dataset, please refer to the following link: [Dataset Link](Dataset)
### Model Training and Evaluation
Our team employed a Convolutional Neural Network (CNN) model for the purpose of pottery classification. The CNN architecture is widely recognized for its effectiveness in image recognition tasks. We trained the model using the carefully curated training dataset, consisting of more than 1700 pottery items.

After an extensive training process, we achieved a commendable test accuracy of 75%. The model demonstrated its ability to accurately classify pottery items into the designated five classes, showcasing its effectiveness in the classification task.
Our training process involved a total of 80 epochs, ensuring thorough exploration of the dataset and optimization of the model's performance. 
***
### Prerequisite
* Install python 3.10.6
* Install OpenCV```pip install opencv-python```
* Install Tensorflow ```pip install tensorflow==1.8```
* Install Matplotlib ```pip install matplotlib```
