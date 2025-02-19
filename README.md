# Melanoma Detection using CNN
> A deep learning-based approach to classify skin lesions into nine categories using Convolutional Neural Networks (CNN).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project aims to develop a CNN model to accurately classify images of skin lesions into nine different classes.
- Skin cancer is one of the most prevalent forms of cancer, and early detection is crucial for effective treatment.
- The model is trained using a dataset containing labeled images of different types of skin lesions, including melanoma.
- The dataset is preprocessed by normalizing, resizing images to 180x180 pixels, and applying data augmentation techniques.
- Class imbalance is addressed using the Augmentor library to improve model performance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initial training showed signs of overfitting, which was mitigated using data augmentation and dropout layers.
- After handling class imbalance, validation accuracy improved significantly.
- Loss and accuracy plots indicate better generalization after augmentation and balancing the dataset.
- The final model achieved a substantial improvement in classification accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - Version 3.x
- TensorFlow/Keras - Deep Learning Framework
- OpenCV - Image Processing
- Matplotlib & Seaborn - Data Visualization
- Pandas & NumPy - Data Manipulation
- Augmentor - Data Augmentation

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by medical image analysis for skin lesion classification.
- References:
  - [TensorFlow Documentation](https://www.tensorflow.org/)
  - [Augmentor Library](https://augmentor.readthedocs.io/en/master/)
- Special thanks to open-source datasets that made this work possible.