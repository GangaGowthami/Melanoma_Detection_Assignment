# Melanoma Detection Assignment
### Problem statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


### Data Summary:

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Objective

To create a multiclass classification model using a custom convolutional neural network in tensorflow.


## General Information

1.What is the background of your project?

Ans. Upgrad AIML course assignment.

2. What is the business probem that your project is trying to solve?

Ans. Exploration of CNN architecture and data augmentation techniques using the ISIC dataset.

3. What is the dataset that is being used?

Ans. The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).


## steps Performed

Step 1: Reading and Understanding the Data

Step 2: Dataset Creation

Step 3: Dataset Creation

Step 4: Model Building & training 

Step 5: Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 

Step 6: Model Building & training on the augmented data 

Step 7: Class distribution

Step 8: Handling class imbalances

Step 9: Model Building & training on the rectified class imbalance data 

## Findings
### Finding on the first base model

- The model is overfitting because we can also see difference in loss functions in training & test around the 10th epoch.
- The training accuracy is 72 and the validation accuracy is 47. we can see the difference here the model is overfitting.Now we can say that model is not good.
- But again, it's too early to comment on the overfitting & underfitting debate.

### Finding on the second base model

- The Training accuracy and validation accuracy are almost same. This is a sign of good fit but the accuracy is still very low. The model requires more epochs to train with class imbalance handled.

## Conclusions

- Model is not overfitting.
- The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
- The training accuracy is 0.9284 and validation accuracy is 0.8812 . This is a sign of good fit.
- The training loss and validation loss are also good.
- The Validation accuracy is 0.88 which is good. The model is able to classify the images with 88% accuracy.
- The Model can be further improved by tuning the hyperparameter.


## Technologies Used

- Colab
- Tensorflow
- Keras
- Numpy
- Pandas
- PIL
- Matplotlib
- OS
- Pathlib

## Contact
Created by [@GangaGowthami] - feel free to contact me!




