# Classifying-X-rays-with-Machine-Learning

As a Researcher in a hospital lab, we are given the task of developing a learning model that supports the doctors in diagnosing illnesses that affect patient's lungs. We have a set of lung X-ray scans with examples of patients who had either Pneumonia, COVID-19, or no disease. Using the Keras module, we created a classification model that outputs a diagnosis based on the patient’s X-ray scan. This model can help doctors with the challenge of deciphering X-ray scans and open a dialogue between our research team and the medical staff to create learning models that are as effective and interpretable as possible.

The file directory is split into train and test folders. This is helpful for us during preprocessing, as images have already been allocated and prepared for a learning model.

All the X-ray scans are in grayscale. This is something to keep in mind when we dive into data preprocessing.

Finally, when we look into the train or test folder, we see that there are three different folders:
-Covid
-Normal
-Viral Pneumonia

Our learning model can output these different classes, indicating a multi-class classification problem rather than binary classification.

## Output:

### Classification Report:
![ALT TEXT](https://github.com/SaifurRR/Classification-Kaggle-Covid-19-Image-Dataset-/blob/main/classification_report.jpeg)

### Model Accuracy:
![ALT TEXT](https://github.com/SaifurRR/Classification-Kaggle-Covid-19-Image-Dataset-/blob/main/model_accuracy.jpeg)

