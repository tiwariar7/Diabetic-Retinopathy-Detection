# Diabetes Retinopathy Detector

### Abstract

The healthcare industry generates a massive amount of data that is often underutilized. Predictive analysis can enhance the use of these datasets, aiding in the early detection and treatment of diseases like cancer, diabetes, or brain tumors. Diabetic Retinopathy (DR) is a severe eye condition caused by diabetes mellitus and is a leading cause of blindness globally. Diabetes can damage the blood vessels in the eyes, leading to complete vision loss. Early diagnosis and continuous monitoring are essential for effective treatment. Manual diagnosis of retinal images is slow and resource-intensive, necessitating the development of efficient machine learning techniques for classifying DR severity levels from retinal scans.

### Objective

- Study current DR prediction trends and data collection.
- Implement various technical indicators.
- Pre-process datasets to enhance DR detection features.
- Build predictive models using different machine learning algorithms.
- Identify significant features using machine learning techniques.
- Compare and analyze model efficiencies.
- Assist in early DR detection for patients and doctors.

### Motivation

This project leverages engineering knowledge to improve healthcare through machine learning. The vast data generated by the healthcare industry is often underutilized. By developing a machine learning-based healthcare project for DR, the project aims to improve early detection and treatment, ultimately enhancing patient outcomes.

### Background

Diabetic Retinopathy (DR) is a prevalent eye disease among diabetic patients, leading to visual impairment. It progresses through stages: mild, moderate, severe non-proliferative DR, and proliferative DR, each causing varying degrees of retinal damage. Manual DR screening methods are inconsistent, highlighting the need for automated DR detection systems.

### Project Description and Goals

This project uses the APTOS 2019 Blindness Detection dataset from Kaggle to develop a machine learning system for DR detection. The system aims to automate DR diagnosis by classifying retinal images into severity levels using convolutional neural networks (CNN) and DenseNet for enhanced accuracy.

#### Data Collection

The dataset consists of 3662 training images and 1928 test images, with corresponding severity levels labeled from 0 to 4.

#### Data Pre-Processing

Steps include reducing lighting effects, cropping images, resizing, and noise reduction to standardize and enhance image features for better analysis.

#### Data Splitting

The dataset is split into training and validation sets (3112:550 ratio) for model training and performance evaluation.

#### Building Models

Two models were developed using CNN and DenseNet architectures. Model 1 uses DenseNet121 with ReLU activation and categorical cross-entropy loss, while Model 2 uses predefined DenseNet121 weights with sigmoid activation and binary cross-entropy loss.

#### Evaluation Measures

Models are evaluated using accuracy, loss, and Quadratic Kappa Score, with adjustments made to improve efficiency.

### Functional Requirements

- The system runs in Python Jupyter with a user-friendly GUI.
- It predicts DR severity levels from 0 to 4.
- Initial training is required for predictions.
- Output includes performance graphs and CSV files with predictions.

### Product Features

The system employs two machine learning models for DR detection, enabling users to compare predictions.

### User Characteristics

The system is beneficial for patients, doctors, hospitals, and health ministries for monitoring DR severity.

### Assumptions and Dependencies

Users must meet hardware and software requirements and provide clear eye images for accurate analysis.

### Domain Requirements

The project uses Python with libraries like Pandas, Numpy, TensorFlow, Keras, OpenCV, Scikit-learn, and Matplotlib.

### System Architecture

![System Architecture](https://user-images.githubusercontent.com/45623734/122232959-4a050480-ced9-11eb-8126-78043ccbb0c9.png)

### System Use Case Diagram

![System Use Case Diagram](https://user-images.githubusercontent.com/45623734/122233019-55f0c680-ced9-11eb-9101-9374bd6837f7.png)

### Conclusion

The project develops an ML-based system for DR detection, aiming to provide timely medical assistance and improve patient outcomes. The DenseNet-based deep neural network enhances DR severity prediction, aiding in early-stage treatment and preventing blindness.

Would you like to make any additional adjustments or keep it as is?
