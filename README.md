# Multiple Myeloma Detection

## Overview
This project is designed to tackle the challenge of detecting multiple myeloma, a type of blood cancer that affects plasma cells in the bone marrow. Multiple myeloma can be diagnosed through the analysis of microscopic images of bone marrow samples. To enhance the diagnostic process, this project employs Convolutional Neural Networks (CNNs), a type of deep learning model specifically suited for image classification.

**What is Multiple Myeloma?**
Multiple myeloma is a cancer of plasma cells, a type of white blood cell that produces antibodies. In multiple myeloma, these cells become cancerous and form tumors in the bone marrow. Early detection is crucial for effective treatment. The project leverages CNNs to automate the detection process from microscopic images, enabling faster and potentially more accurate diagnoses.

**Dataset: Harvard Dataverse MiMM_SBILab Dataset**
The CNN model was trained and evaluated on the Harvard Dataverse MiMM_SBILab Dataset: Microscopic Images of Multiple Myeloma. This dataset consists of a total of 85 images, including both cancerous and non-cancerous samples. The project aims to utilize this dataset to develop a model capable of distinguishing between cancerous and non-cancerous samples, aiding medical professionals in their diagnostic efforts.

Link: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/XCX7ST

## Module 1: Data Preparation and Model Building

### Description

Module 1 focuses on data preparation, data preprocessing, and the initial steps of model building. It includes the following tasks:

- Loading and organizing the dataset: Images are loaded and labeled accordingly.
- Data preprocessing: Images are resized, and image enhancement techniques such as Contrast Limited Adaptive Histogram Equalization (CLAHE) are applied to improve image quality.
- Data segmentation: Images are segmented to highlight regions of interest, which are essential for medical image analysis.
- Data splitting: The dataset is divided into training and testing sets to prepare it for model training and evaluation.
  
## Module 2: Deep Learning Model Training and Evaluation

### Description

Module 2 is dedicated to the development, training, and evaluation of a deep learning model for image classification. It includes the following key components:

- Building a Convolutional Neural Network (CNN): A CNN architecture is defined to extract features from the segmented images and make predictions.
- Model training: The CNN model is trained on the prepared training data using appropriate loss functions and optimization techniques.
- Model evaluation: The trained model is evaluated on the testing data, and performance metrics such as accuracy, loss, and classification reports are generated.
- Visualizing results: The module includes visualizations of training history and model performance.
  
