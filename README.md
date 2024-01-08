# Malaria Diagnosis using TensorFlow

## Overview
The Malaria Diagnosis project leverages TensorFlow, a powerful open-source machine learning library, 
to develop an intelligent system for diagnosing malaria based on blood cell images.
Malaria is a life-threatening disease caused by parasites transmitted through the bites of infected mosquitoes. 
Early and accurate diagnosis is crucial for effective treatment.

## Key Features
**Deep Learning Model**: Utilizes a convolutional neural network (CNN) implemented with TensorFlow for the automatic detection of malaria-infected blood cells.

**Dataset**: The model is trained on a comprehensive dataset of blood cell images, containing both healthy and infected samples.

**Data Preprocessing**: Implements image resizing, normalization, and augmentation techniques to enhance the robustness of the model.

**Results Visualization**: Showcases the model's predictions with visualizations and provides insights into its performance.

## How to Use
1. Make sure to have python installed along with Jupyter Notebook. Install JB using the following ```pip install jupyter```
2. Clone the repository to your local machine using  ```git clone```
3. Navigate into the repository you just cloned using ```cd MachineLearning```
4. Launch Jupyter Notebook using the following command while still in the MachineLearning directory: ```jupyter notebook```.
5. The project should appear in a python notebook file and should be ready to run.

## Results
The model achieves high accuracy (94%) in differentiating between healthy and malaria-infected blood cells. 
The results, including precision, recall, and F1-score, are presented in the notebook for further analysis.
The last code block in the notebook file should lay out 9 cells with two letter on top (P for parasitic and U for unparasitic).
The first letter determines its actual infected status and the following letter shows the predicted.
