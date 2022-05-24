# CNN_Project
By Kristof Vandewynckel

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

# Step 0: Installation of required software.

Code Used:

Python

Libraries Used:

Pandas
Numpy
Tensorflow
Sklearn
Flask
Deployment through Heroku and Git.
