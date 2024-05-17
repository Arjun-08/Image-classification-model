# COVID-19 Chest X-ray Classification

This repository contains code for a deep learning project aimed at classifying chest X-ray images into normal and abnormal categories, with a focus on detecting COVID-19 and pneumonia cases. The project utilizes convolutional neural networks (CNNs) and transfer learning techniques to achieve accurate classification results.

## Dataset

The dataset used in this project consists of chest X-ray images collected from various sources, including publicly available repositories and medical institutions. The dataset is organized into training, validation, and test sets, with a balanced distribution of normal and abnormal cases.

## Models Implemented

Two main models have been implemented and compared for this classification task:

1. **Custom CNN Model**: A custom CNN architecture is designed and trained from scratch using TensorFlow/Keras. The model comprises multiple convolutional and pooling layers followed by fully connected layers for classification.  This model will  classify the chest X-ray images for detecting normal or abnormal health conditions.
   ![image](https://github.com/Arjun-08/Image-classification-model-that-can-classify-the-images-into-the-3-classes-/assets/88790572/9ffcc46c-d5ea-4e87-9002-a6983ac8a42f)


2. **VGG16 Transfer Learning Model**: Transfer learning is applied using the VGG16 pre-trained model, which has been fine-tuned on the chest X-ray dataset. The final layers of VGG16 are replaced with custom fully connected layers for binary classification. This model will in classify the chest X-ray images for detecting COVID-19 and pneumonia.
![image](https://github.com/Arjun-08/Image-classification-model-that-can-classify-the-images-into-the-3-classes-/assets/88790572/1b01244d-352c-4496-aae6-2a2d72280dd6)

## Training and Evaluation

Both models are trained on the training dataset and evaluated on the validation and test datasets. Training metrics such as loss and accuracy are monitored during the training process, and evaluation metrics including precision, recall, and F1-score are calculated to assess model performance.

## Results

The performance of both models is evaluated using standard classification metrics. Additionally, confusion matrices and classification reports are provided to analyze the model's performance in detail, including its ability to distinguish between COVID-19 and pneumonia cases.

Model 1: 

![image](https://github.com/Arjun-08/Image-classification-model-that-can-classify-the-images-into-the-3-classes-/assets/88790572/18d934d6-1dd8-45b3-a8fa-ee56965e441c)

Model 2:

![image](https://github.com/Arjun-08/Image-classification-model-that-can-classify-the-images-into-the-3-classes-/assets/88790572/b4a3a963-5727-42a7-857f-6450792ebd72)


## Conclusion

This project demonstrates the effectiveness of deep learning models in classifying chest X-ray images for detecting COVID-19 and pneumonia. By leveraging CNN architectures and transfer learning, accurate classification results can be obtained, which can aid healthcare professionals in diagnosing respiratory diseases.


## Contact

If you have any questions or suggestions, please feel free to reach out to me at [nvarjunmani07@gmail.com](mailto:nvarjunmani07@gmail.com).
