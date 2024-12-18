# Melanoma-Detection-Assignment

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

 
## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]

  
## General Information

  - This project is multiclass classification model using a custom convolutional neural network in TensorFlow.
  - To build a CNN based model which can accurately detect melanoma.
  - A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed 
    in diagnosis.
 
  - The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
  The data set contains the following diseases:

   * Actinic keratosis
   * Basal cell carcinoma
   * Dermatofibroma
   * Melanoma
   * Nevus
   * Pigmented benign keratosis
   * Seborrheic keratosis
   * Squamous cell carcinoma
   * Vascular lesion

## Conclusions
  Model overfits as the there is a huge gap between training and validation accuracy is the first model without augmented data and with class rebalance 
  After image augmentation the overfit is resolved as the gap between training and validation loss decreased, but the accuracy is still low 
  Model performs much better after class imbalance treatment 


## Technologies Used
- Matplotlib
- Numpy
- tensorflow-intel- 2.18.0
- Augmentor 0.2.12
  

## Acknowledgements

This project was inspired by AI ML C65 batch.


## Contact
Created by [@sakshilocal] - feel free to contact me!


