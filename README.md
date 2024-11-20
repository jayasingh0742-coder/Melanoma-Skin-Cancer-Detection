# Project Name
> The goal is to develop a CNN model capable of detecting malenoma. It is a type of skin cancer which can be deadly if not detected early.
Early detection is crucial and a solution that can analyze images and notify dematologists about the presence of this cancer in patients.
The project requires to build a multiclass classification model using a custom convolutional neural network in Tensorflow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a multiclass classification model which can detect malenoma, a type os skin cancer.
- The project can help oncological department of hospitals for early detection of skin cancer among patients. This is a deadly disease which accounts for 75% of skin cancer deaths.
- An accurate and robust CNN model which can help in detecting malenoma. 
- The dataset used is from International Skin Imaging Collaboration (ISIC). All the images in the project were sorted according to classification taken from ISIC.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1 is nitial model built with no batch normalization , no learning rate optimization or any other technique. This model is midly overfitting and needs improvement.
- Model 2 handles overfitting by data augmentation technique, which has certainly helped without changing any other parameter.
- Model 3 with highest accuracy and least loss suggests that model has been learning effectively and is not overfitting. Class rebalance has definately helped the model to combat overfitting and making it more accurate.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy  - version 1.24.3
- Pandas - version 2.2.2
- Tensorflow - version 2.13.1
- PIL - version 11.0.0
- Keras - version

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad



## Contact
Created by [@jayasingh0742-coder] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->