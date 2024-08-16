# Apple Disease Expert

The "Apple Disease Expert" project aims to automate the detection and classification of apple diseases using advanced deep learning models. This research enhances apple farming efficiency by providing early diagnosis capabilities that help in preventing significant crop losses.

**Technologies Used**: ResNet50 - Vgg16  

## Plant Disease Expert Dataset:

The Plant Disease Expert dataset, available on Kaggle, contains over 200,000 images spanning 58 plant classes for disease detection. This study focuses solely on apple crops, utilizing 18,600 images to represent three specific apple diseases and healthy apple leaves. Each class label, including the different apple leaf conditions, is illustrated below with representative images from the dataset.

![image](https://github.com/user-attachments/assets/ea4638ff-6d77-43e0-b358-785b4cb4e066)

The table below outlines the distribution of images across four categories of apple conditions: Cedar apple rust, healthy apples, Black rot, and Apple scab. The table lists the number of images for each class, highlighting the dataset's focus on specific apple diseases and healthy specimens.

<div align=center>
<img width="350" alt="Screenshot 2024-08-06 at 7 35 24 PM" src="https://github.com/user-attachments/assets/138f71e6-eefa-409e-957d-4b7f1d2a9892">
</div>

 The figure below provides a bar chart visualization of the image distribution described in the preceding table. This graphically represents the quantity of images per disease category.

 <div align=center>
   <img width="343" alt="Screenshot 2024-08-06 at 7 36 44 PM" src="https://github.com/user-attachments/assets/8f98412e-54a2-4f57-9f6f-3307daa37c1e">
 </div>

 ## Evaluation Metrics:

- Accuracy Metric: Monitored throughout training and testing, accuracy measures the ratio of correctly predicted instances to the total predictions, providing a direct indicator of model performance.

- Cost Function: Employed to minimize the error between predicted outputs and actual target values, aiding in regularization to prevent overfitting during the training process.

- Visualization of Training Dynamics: Utilized graphs to track training and validation accuracy over epochs, helping to diagnose behavior such as overfitting or underfitting.
  
<div align=center>
 <img width="317" alt="Screenshot 2024-08-06 at 7 40 36 PM" src="https://github.com/user-attachments/assets/aba4bd0b-033d-4209-b018-a9f55348f499">
</div>

A confusion matrix was also implemented as another visualization method. This tabular representation of the classification model's performance displays counts of true positives, true negatives, false positives, and false negatives. It facilitates the calculation of additional metrics such as Precision, Recall, and F1 Score.

<p align="center">
  <img height="250" width="300" alt="Screenshot 2024-08-06 at 7 45 17 PM" src="https://github.com/user-attachments/assets/b417ed92-7112-4b07-be4b-09e90b64a862">
  <img height="250" width="300" alt="Screenshot 2024-08-06 at 7 44 08 PM" src="https://github.com/user-attachments/assets/ae55c9a4-685e-4c94-9602-80b85cfc61fc">
</p>

## Results and Conclusion:

The table below shows the performance classification accuracy (%) of transfer learning (TL) with ResNet50, and VGG16, using k-fold cross validation, and hold-out cross validation.

<div align=center>
<img width="425" alt="Screenshot 2024-08-06 at 7 50 38 PM" src="https://github.com/user-attachments/assets/48550e33-d845-4d7b-9690-7b4a9a16403c">
</div>

The goal of the "Apple Disease Expert" project is to classify apple diseases using the ResNet50 and VGG16 deep learning algorithms. Performance was assessed through accuracy scores and confusion matrices. Despite limitations due to the augmented nature of the dataset, results were improved by employing various cross-validation methods and adjusting hyperparameters. It was found that ResNet50 outperformed VGG16, achieving an accuracy of 99.95%.
