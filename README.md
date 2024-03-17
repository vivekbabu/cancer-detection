# Cancer Detection

To build a CNN based model which can accurately detect melanoma. 

Melanoma is a type of cancer that can be deadly if not detected early. 

It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

# Data

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 

All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

# Project Pipeline

- **Data Reading** → Defined the path for train and test images
- **Dataset Creation** → Created train & validation dataset from the train directory with a batch size of 32. Made sure images are resized to 180*180
- **Dataset visualisation** → Created a code to visualize one instance of all the nine classes present in the dataset
- **Model Building & training** → 
   - Created a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
   - Chose an appropriate optimiser and loss function for model training
   - Trained the model for ~30 epochs
   - Wrote the findings after the model fit. Checked for overfitting and underfitting
- **Data Augmentation** → Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
- **Model Building & training on the augmented data** →
  - Created a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescaled images to normalize pixel values between (0,1).
  - Chose an appropriate optimiser and loss function for model training
  - Trained the model for ~30 epochs
  - Wrote the findings after the model fit, and commented whether the overfitting and underfitting is fixed or not
 
  - 
