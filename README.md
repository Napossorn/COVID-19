# Classification of COVID-19, and Viral Pneumonia Chest X-ray Images.


## Introduction
Coronavirus disease (COVID-19) is a pandemic disease, which has already caused thousands of causalities and infected several millions of people worldwide. Furthermore, common symptoms of COVID-19 include fever, cough, shortness of breath, fatigue, body aches, sore throat, loss of taste or smell, headache, and in severe cases, difficulty breathing or pneumonia. X-ray imaging is an easily accessible tool that can be an excellent alternative in the COVID-19 diagnosis. 
In the other side, Viral pneumonia is a type of pneumonia that is caused by a viral infection rather than a bacterial infection. In addition, viral pneumonia is an infection that inflames the air sacs in one or both lungs, causing them to fill with fluid or pus. The symptoms of viral pneumonia can vary but often include fever, cough, shortness of breath, rapid breathing, chest pain, fatigue, and muscle aches. Diagnosis of viral pneumonia typically involves a combination of clinical evaluation, chest X-rays or CT scans, and laboratory tests.


## Dataset
The dataset used in this project will consist of chest X-ray images of patients diagnosed with viral pneumonia, and COVID-19. The data will be obtained from publicly available sources such as Kaggle databases. Moreover, the dataset was split into training, validation, and testing sets, and a transfer learning technique was used with image augmentation to train and validate pre-trained deep Convolutional Neural Networks (CNNs) for automatic detection of COVID-19 pneumonia. 


## Methods
The method involves using transfer learning techniques with pre-trained deep Convolutional Neural Networks (CNNs) to train and validate the CNNs for the classification of the images into two categories: COVID-19 and viral pneumonia. Likewise, The dataset was split into training, validation, and testing sets, and the performance of the CNNs was evaluated based on classification accuracy, precision, sensitivity, and specificity.


## Results
The metrics that are used in this project provided are the precision, recall, F1-score, and support for each class in a classification task. 

1.) Precision: It measures the accuracy of the positive predictions. For class 0, the precision is 0.95, which means that 95% of the samples predicted as class 0 are correct. For class 1, the precision is 1.0, indicating that all the samples predicted as class 1 are correct.

2.) Recall: It measures the proportion of actual positives that are correctly identified. For class 0, the recall is 1.0, indicating that all the actual class 0 samples are correctly identified. For class 1, the recall is 0.98, meaning that 98% of the actual class 1 samples are correctly identified.

3.) F1-score: It is the harmonic mean of precision and recall, providing a single metric that balances both precision and recall. The F1-score for class 0 is 0.98, and for class 1, it is 0.99.

4.) Support: It represents the number of samples in each class. For class 0, the support is 127, and for class 1, it is 370.

5.) Accuracy: It is the overall accuracy of the model, which is the proportion of correct predictions out of all the samples. In your case, the accuracy is 0.99, indicating that the model predicts correctly for 99% of the samples.













