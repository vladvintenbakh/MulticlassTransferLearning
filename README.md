# Transfer Learning for Face Classification (Gender, Race, and Age)

## Project Objective
The objective of this project is to classify faces based on gender, race, and age using a transfer learning approach. We will leverage a pre-trained model on facial recognition tasks and fine-tune it for multi-class classification on a dataset containing 20,000 face images. The dataset includes faces of individuals aged 0 to 116, with targets including gender (male/female), race (white/black/asian/indian/other), and age. The goal is to develop an accurate classification model using transfer learning and explore how well it generalizes to these specific tasks.

### Dataset
* [UTKFace Dataset](https://susanqq.github.io/UTKFace/): A dataset containing images of people with various ages, genders, and races, where all pictures are of the same size and the faces are centered.

### Methods Used
* Transfer Learning
* Fine-tuning
* Image Classification
* Model Evaluation

### Technologies
* Python
* Jupyter/Google Colab
* TensorFlow/Keras
* Pandas
* NumPy
* Matplotlib

## Project Description
In this project, we use a pre-trained VGGFace model (based on VGGFace2 dataset) to classify face images by gender, race, and age. VGGFace2 contains millions of images with variations in pose, age, and ethnicity, making it a suitable base for transfer learning. The project involves loading the pre-trained model, fine-tuning it for our specific tasks, and evaluating its performance on a test set.

Key steps include:
1. Loading a pre-trained model (ResNet50 architecture based on VGGFace2).
2. Fine-tuning the model to classify face images into different gender, race, and age groups.
3. Evaluating the model's performance using accuracy and other relevant metrics.
4. Visualizing model predictions and analyzing any misclassifications.

## Project Needs
- Data preprocessing and augmentation
- Transfer learning and model fine-tuning
- Model evaluation and visualization
- Reporting results

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Download the UTKFace dataset from [here](https://susanqq.github.io/UTKFace/). Ensure that the dataset is properly structured with all images centered and resized as required.
3. The pretrained VGGFace model (ResNet50 architecture) can be downloaded [here](https://drive.google.com/open?id=1oHJxVZCcVwp1dgcwDIZL4h97uInxOGWO).
4. Install the dependencies listed in requirements.txt and run the notebook.

## Featured Notebooks
* [VGG_Multiclass_Transfer_Learning.ipynb](https://github.com/vladvintenbakh/MulticlassTransferLearning/blob/main/VGG_Multiclass_Transfer_Learning.ipynb)
