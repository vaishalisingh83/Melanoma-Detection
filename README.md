# Melanoma-Detection
Melanoma Detection Case study
This project uses a custom CNN to detect melanoma in images of skin lesions among 10 classes. The Gradio library is used to create a web app for the model prediction. The model predicts with an 87% accuracy.

Table of Contents
Melanoma-Detection-using-using-custom-cnn
Table of Contents
General Information
Algorithms Used
Dataset Information
Steps Involved
Results
Baseline Model
Augmented Model
Final Model
Conclusion
Technologies Used
Contact
License
General Information
Algorithms Used
Convolutional Neural Network

Dataset Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
Steps Involved
Data Loading
Baseline Model Building
Training the Model and testing the model
Building an augmented model
Training the augmented model and testing the model
Countering Class Imbalance with augmentor
Building the final model
Training the final model and testing the model
Verifying the model
Results
Baseline Model
Accuracy and Loss charts for the baseline model Alt text

Augmented Model
Accuracy and Loss charts for the augmented model Alt text

Final Model
Accuracy and Loss charts for the final model Alt text

Conclusion
As the accuracy of the model increases, the loss decreases. The final model has an accuracy of 87% and a loss of 0.3. The model is able to predict the class of the lesion with a high accuracy. Augmenting the data and countering class imbalance helped in improving the accuracy of the model.

Technologies Used
Python
Tensorflow
Keras
Augmentor
Matplotlib
NumPy
