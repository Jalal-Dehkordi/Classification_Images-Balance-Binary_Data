# Classification_Images-Balance-Binary_Data
Categorizing dog and cat images of a Kegel dataset and applying tricks to improve the performance of the models

## Project: classification of images on balanced binary data downloaded from the kaggle site

### Design a custom model, model training without Regularization _ DropOut and Data Augmentation , and Regularization _ DropOut and Data Augmentation 
### Using the pre-trained AGG16 model, implementing tricks on this model

## The aim of this project is a teaching-research project that is useful for image classification problems.

### In this project, a dataset downloaded from the Kegel website is used.
www.kaggle.com/c/dogs-vs-cats/data 

## The project is carried out in two phases:
### Phase one: design and create a custom model :
* Model training (Overfitting occurred)
* Solution to Overfitting:
 Regularization _ DropOut and Data Augmentation
( model accuracy : 77%)

### Phase two: use of pre-trained models (model used by VGG-16)
 * Method one: just extract the characteristic (tmodel accuracy : 90%)
 * Method two: Feature extraction and use Regularization and Data Augmentation(model accuracy : 94%)
 * Method three: Fine-Tuning (model accuracy : 97%)

### First, a directory structure is prepared to organize and prepare a dataset of cat and dog images for the learning model
![image](https://github.com/Jalal-Dehkordi/Classification_Images-Balance-Binary_Data/assets/140386080/9ed0fc5b-9f4e-4aaf-953c-52f63349e132)

Problem is a balanced binary classification problem and the data is evenly distributed.
The data is extracted into the following number of images:
 * Train data 2000 images 
 * Validation data 1000 images 
 * Test data 1000 images

## prerequisites:
 * Familiarity with Python and machine learning and deep learning models
 * Familiarity with pre-trained models and ImageNet dataset
 * Familiarity with data augmentation techniques

# Project description:
### Phase one :
• Analysis and visualization of data
* Model design 
* Model configuration
* Pre-processing of data
* Model training
* Drawing and interpreting charts loss and accuracy
• Use of additive data in data processing
• Use of the dropout layer in the network
* Model training
* Drawing and interpreting charts loss and accuracy
### Phase two :
* Basic prototyping of the convolution from the VGG16 model
* Extracting features using only the pre-trained convolution base
* Define and teach the classifier of the dense connection and use the drop out layer in it
* Drawing and interpreting the results
* Extracting features using pre-trained convolutional base and Data Enhancement (convolutional base freezing)
* Model training and evaluation

### Author: Jalal OstadHadi Dehkordi

# Good luck 
