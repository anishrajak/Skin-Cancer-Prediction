# Skin-Cancer-Prediction

Skin cancer is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopy analysis, a biopsy and histopathological examination The purpose of this project is to create a tool that considering the image of a mole, can calculate the probability that a mole can be Malignant or Benign.

The dataset is taken from Kaggle. It consists of 1800 pictures of benign moles and 1497 pictures of malignant classified moles. The pictures have all been resized to low resolution (224x224x3) RGB. The task of this kernel is to create a model, which can classify a mole visually into benign and malignant. Development process and Data The idea of this project is to construct a CNN model that can predict the probability that a specific mole can be Malignant or Benign.

Data :

kaggle-https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign

As the dataset is pretty balanced, the model will be tested on the accuracy score, thus (TP + TN)/(ALL). It has 2 different classes of skin cancer which are listed below :

• Benign

• Malignant
