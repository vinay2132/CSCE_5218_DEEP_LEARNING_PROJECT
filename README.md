# CSCE_5218_DEEP_LEARNING_PROJECT: Deep Learning Approach for Gender and Age Prediction Using CNN

This is a deep learning project for predicting age and gender using convolutional neural networks (CNNs) in Python. The model architecture is based on a research paper by [Gil Levi and Tal Hassner](https://talhassner.github.io/home/publication/2015_CVPR), with slight modifications for improved performance on the [UTKFace dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new).

# Repository Structure

The code in **age_and_gender_prediction.ipynb** loads data from the **archive/UTKFace** folder and processes it to predict age and gender using specified models.


# Frameworks used

-   **Tensorflow:** Used for deep learning tasks. Install with &nbsp;&nbsp; `pip install tensorflow`
-   **NumPy:** Used for numerical computing. Install with &nbsp;&nbsp; `pip install numpy`
-  ** Keras:** Used for building neural networks. Install with &nbsp;&nbsp; `pip install keras`
-   **Seaborn:** Used for statistical data visualization. &nbsp;&nbsp; `pip install seaborn`
-  ** tqdm**: Used for creating progress bars. &nbsp;&nbsp; `pip install tqdm`

# Performance of model

**Gender Accuracy Graph:​** The plot depicts training and validation accuracies for gender prediction over epochs, with the blue line indicating training accuracy and the red line representing validation accuracy, both showing steady improvement, affirming the model's gender prediction capability.​

![Gender Accuracy Graph](https://github.com/vinay2132/CSCE_5218_DEEP_LEARNING_PROJECT/assets/63947925/fde2bbfa-2c08-4e68-ac21-f7664e987f50)


**Gender Loss Graph:​** The graph demonstrates decreasing training and validation losses for gender prediction across epochs, reflecting consistent improvement in model performance.​

![Gender Loss Graph](https://github.com/vinay2132/CSCE_5218_DEEP_LEARNING_PROJECT/assets/63947925/2acfef1d-cae8-4237-8e60-f0f10d124cb5)

**MAE Graph for Age:​** The plot illustrates the Mean Absolute Error (MAE) for age prediction during training and validation, with both showing a decrease over epochs, suggesting improved accuracy in age prediction by the model.​

![MAE Graph for Age](https://github.com/vinay2132/CSCE_5218_DEEP_LEARNING_PROJECT/assets/63947925/a4a38d7f-d50d-4538-9936-61b43b0fb77d)

**Accuracy and MAE:** Gender prediction accuracy: 90%, MAE for age: 6.5, with a standard deviation of 4 for predicted age, indicating moderate accuracy.​

**Model Performance:​** The model consistently improves gender prediction accuracy and age prediction MAE over training epochs, indicating effective feature learning from facial images.​

**Feature Consideration:** Further optimization and exploring alternative approaches could enhance model performance.​


#How to run the project

First, go to GitHub and download the code. It'll come in a zip file along with the dataset. Before you run the code, make sure you have everything it needs, like specific software or frameworks. Then, you can run the code and see it in action.

`age_and_gender_preduction.ipynb`: This file contains the code for predicting age and gender.
`age_and_gender_preduction.pdf`: This is the code in PDF format along with the output files.
`5218_ppt.pptx`: This is a PowerPoint presentation with explanations.
`archive/UTKFace`: This folder contains all the images needed to train the model.



