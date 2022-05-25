# CNN_Project
By [Kristof Vandewynckel](https://www.linkedin.com/in/kristof-vandewynckel/)

# Project Description
A small project where we use the Kaggle Skin Cancer MNIST: HAM10000 dataset to create a Neural Network. The user can upload a picture of a skin lesion and get an estimate back on whether it requires medical attention or not. This project was assigned to us as part of the BeCode education program. The students are three and a half months into the education to become data scientists/ AI Operators and have just finished their Image Processing content. This is a first hands-on project to try and better grasp the essence of Convolutional Neural Networks (CNN from this point on) .

# Explanation

The data for this project comes from Kaggle's [Skin Cancer MNIST HAM 10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) dataset. We focus on the two folders containing the images and the metadata.csv. The Pixel data will not be used in this project.

As mentioned before, the CNN will take an uploaded picture of a skin lesion and give an estimate classification between the following possible results:

1. Actinic keratoses and intraepithelial carcinoma / Bowen's diseas (akiec)
2. Basal cell carcinoma (bcc)
3. Benign keratosis-like lesions (bkl)
4. Dermatofibroma (df)
5. Melanoma (mel)
6. Melanocytic nevi (nv)
7. Vascular lesions (vasc)

# Installation of required software.

Code Used:

Python

Libraries Used:

Pandas
Numpy
Tensorflow
Sklearn
Flask
Deployment through Heroku and Git.

# File overview

In our [Jupyter Notebook](https://github.com/KristofVandewynckel/CNN_Project/blob/main/Notebook_creating_the_model.ipynb) we can see how we trained our model by the various parameters we used. 
Our [app.py](https://github.com/KristofVandewynckel/CNN_Project/blob/main/app.py) will launch our app making it possible for users to upload pictures and get a classification. This also uses the templates, static and uploads folder to create the aesthetic and buttons. (under construction)
[procfile](https://github.com/KristofVandewynckel/CNN_Project/blob/main/Procfile) and [requirements.txt](https://github.com/KristofVandewynckel/CNN_Project/blob/main/requirements.txt) are used to deploy on Heroku.


# If you want to use the app

To use the app go to https://mole-detection-app.herokuapp.com/ and upload your picture of the mole to get a classification (under construction).

# If you want to improve the model

You can use the Jupyter notebook to change the model and preprocessing to train your own versions. Save this model and apply it in the app.py. Feel free to improve on this classification. 
