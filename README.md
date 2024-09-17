# Melanoma Detection Using Convolutional Neural Networks
> This project focuses on developing a Convolutional Neural Network (CNN) model to accurately detect melanoma and other skin diseases from images. The goal is to assist dermatologists by automating the detection process and potentially improving early diagnosis of melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Background**: Melanoma is a severe form of skin cancer that can be deadly if not diagnosed early. Early detection is crucial for effective treatment and increasing survival rates.
- **Business Problem**: Dermatologists face the challenge of manually examining numerous images, which can be time-consuming and prone to human error. An automated model can significantly reduce manual effort and aid in early diagnosis.
- **Dataset**: The dataset includes images of skin lesions classified into nine categories:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion


## Conclusions
- **Initial Findings**: The first CNN model trained on the dataset showed potential but also indications of overfitting and underfitting. Evaluation metrics such as accuracy, loss, and validation performance were used to assess the model's effectiveness.
- **Data Augmentation Impact**: Implementing data augmentation strategies improved the model’s performance by addressing issues of overfitting and underfitting. The augmented model showed better generalization across unseen data.
- **Class Imbalance Handling**: Analysis revealed class imbalances, with some classes having significantly fewer samples. Techniques like oversampling and synthetic data generation were employed to address these imbalances, leading to improved model performance.
- **Final Model Performance**: After addressing class imbalances and further training, the final CNN model demonstrated improved accuracy and reduced overfitting a bit. The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.The Model can be further improved by tuning the hyperparameter.


## Technologies Used
- **TensorFlow** - 2.13.1
- **Keras** - 2.13.1
- **NumPy** 
- **Pandas** 
- **Matplotlib** 
- **Augmentor** - 0.2.12

## Acknowledgements
- This project was inspired by recent advancements in medical image analysis and the growing need for automated diagnostic tools.
- References to relevant research papers and tutorials were consulted for developing the CNN model and addressing class imbalances.
- This project was based on tutorials and best practices from [TensorFlow](https://www.tensorflow.org/).

## Contact
Created by @swatiguptajain - feel free to contact me!

