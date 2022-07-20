# NeuNet-CNN-Melanoma-Detection:
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Conclusions

First model was built on basic CNN where just batch normalization was used and had huge overfitting.
Second model was built on basic CNN with Data Augemntation, Dropouts, getting rid of bath normalization. The overfiiting issue was recolved how ever the training accuracy and validation accuracy was very low due to class imbalance.
Third Model was built after Augumentor was used to add 500 images to handle class imbalance and the model was built again with a new dataframe derived from the class imbalance fix. The model also has Droputs as hyperparameter tuning. The model performed well with high accuracy on both train & valadiation ds and also the overfit problem was eliminated.


## Technologies Used
- Python Pandas Libraries
- Python Numpy Libraries
- Python Matplotlib Libraries
- Python Plotly
- Python Keras
- Python Tensorflow
- Python Pathlib & OS
- Python Augmentor

## Acknowledgements
- UpGrad for all the academic knowledge session
- UpGrad Daily Doubt Resoulution Team
- UpGrad Support Group Industry Leaders as mentors

## Contact
- Created by [@hippietrippycoder] - feel free to contact me.

