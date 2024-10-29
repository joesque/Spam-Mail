# Spam Mail Classifier

This project aims to build a machine learning model to classify emails as "spam" or "ham" (non-spam). :shipit: It includes the following steps:

**Data Loading and Preprocessing:**
- Load labeled data (spam and ham messages) and clean it by handling missing values.
- Convert labels to binary (0 for spam, 1 for ham) for easier model processing.

**Feature Engineering:**
- Transform email content into numerical features using TF-IDF vectorization, which captures word importance across messages.

**Model Training:**
- Train a Logistic Regression model to classify emails, using the TF-IDF features to distinguish between spam and ham messages.

**Model Evaluation:**
- Assess model accuracy on both training and testing data to ensure robust performance, achieving ~96% accuracy.

**Prediction System:**
- Build a prediction function to classify new email messages, making it easy to determine whether an email is spam.

Dataset: [Google Drive link](https://drive.google.com/drive/folders/1bRuM2RJ3CGD5_PtnIr7jVbC5kOJW5o6x)
