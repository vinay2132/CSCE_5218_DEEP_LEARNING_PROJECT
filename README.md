# CSCE_5218_DEEP_LEARNING_PROJECT: Deep Learning Approach for Gender and Age Prediction Using CNN

This is a deep learning project for predicting age and gender using convolutional neural networks (CNNs) in Python. The model architecture is based on a research paper by [Gil Levi and Tal Hassner](https://talhassner.github.io/home/publication/2015_CVPR), with slight modifications for improved performance on the [UTKFace dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new).

# Repository Structure

The code in age_and_gender_prediction.ipynb loads data from the archive/UTKFace folder and processes it to predict age and gender using specified models.


# Frameworks used

-   Tensorflow: Used for deep learning tasks. Install with &nbsp;&nbsp; `pip install tensorflow`
-   NumPy: Used for numerical computing. Install with &nbsp;&nbsp; `pip install numpy`
-   Keras: Used for building neural networks. Install with &nbsp;&nbsp; `pip install keras`
-   Seaborn: Used for statistical data visualization. &nbsp;&nbsp; `pip install seaborn`
-   tqdm: Used for creating progress bars. &nbsp;&nbsp; `pip install tqdm`

## Performance of model

Gender Accuracy Graph:​ The plot depicts training and validation accuracies for gender prediction over epochs, with the blue line indicating training accuracy and the red line representing validation accuracy, both showing steady improvement, affirming the model's gender prediction capability.​

![Gender Accuracy Graph](https://github.com/vinay2132/CSCE_5218_DEEP_LEARNING_PROJECT/assets/63947925/fde2bbfa-2c08-4e68-ac21-f7664e987f50)


