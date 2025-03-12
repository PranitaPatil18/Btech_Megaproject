**Machine Learning-Based Intrusion Detection System for Modbus Networks**
Project Overview
In industrial environments such as power plants, water treatment facilities, and manufacturing, Modbus is a widely used communication protocol for exchanging data between devices. However, it lacks built-in security features, making it vulnerable to cyberattacks such as unauthorized access, data manipulation, and replay attacks. Traditional Intrusion Detection Systems (IDS) often struggle to detect these threats due to complex attack patterns and limited labeled training data, leading to either false alerts or failure to detect advanced attacks.

To address this issue, our project focuses on developing a Machine Learning (ML)-Based Intrusion Detection System (IDS) for Modbus-enabled industrial networks. The system can automatically distinguish between normal and malicious network activity, enhancing security and preventing cyber threats.

Key Features and Approach
Utilizes ensemble learning (stacking approach) to improve detection accuracy.
Combines multiple ML models, including SVM, Random Forest (RF), K-Nearest Neighbors (KNN), and AdaBoost, with a meta-classifier for final prediction.
Uses CIC-IDS 2023 dataset as a foundational resource for model training and evaluation.
System Architecture
Data Collection – Extracting network traffic data from CIC-IDS 2023, containing both benign and malicious activity.
Preprocessing – Cleaning and normalizing data for feature extraction.
Feature Extraction – Identifying key characteristics to improve model performance.
Model Training – Using ML models to classify network traffic.
Attack Classification & Evaluation – Measuring accuracy, precision, recall, and overall system effectiveness.
