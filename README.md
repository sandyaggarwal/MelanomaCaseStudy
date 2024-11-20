# Melanoma-Detection
> Custom convolutional neural network  for a multiclass classification model using TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Melanoma** is a life-threatening type of cancer if not detected early, contributing to **75% of skin cancer-related deaths**. Developing a solution to analyze images and notify dermatologists of potential melanoma cases can significantly reduce the manual effort required for diagnosis.

- This project focuses on **classifying various skin diseases** and detecting melanoma using AI, specifically through **Convolutional Neural Networks (CNNs)**.

- The primary objective is to create a **CNN-based model** capable of accurately identifying **melanoma skin cancer**.

- The dataset includes **2,357 images** of malignant and benign skin conditions, sourced from the **International Skin Imaging Collaboration (ISIC)**. The images are categorized based on ISIC classifications, with an even distribution across most subsets, except for melanomas and moles, which have a slightly higher representation.

### The dataset covers the following conditions:
- Actinic keratosis  
- Basal cell carcinoma  
- Dermatofibroma  
- Melanoma  
- Nevus  
- Pigmented benign keratosis
- Seborrheic keratosis  
- Squamous cell carcinoma  
- Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Selecting an **appropriate optimizer** and **loss function** is crucial for effective model training. 
- **Overfitting** in a model can be mitigated by incorporating **Dropout layers**.
- Implementing a well-designed **augmentation strategy** can help address class imbalances in the dataset.
- An **underfitted model** can be improved by increasing its complexity.  
  


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Tensorflow - version 2.18.0
- Keras - version 3.6.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is an assignment given by UPGRAD's AI/ML Course.


## Contact
Created by [sandyaggarwal] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->