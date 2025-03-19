# PySpark
Predicting Credit Card Fraud using PySpark and Machine Learning Project completed for DSCI 632 (Applied Cloud Computing) course at Drexel University

Title: Predicting Credit Card Fraud using PySpark and Machine Learning

Created By: Shawn Oyer, Leland Ly and Ahmad Javed on 8/22/2024

Abstract: Credit card fraud detection is a critical concern for ecommerce platforms and financial institutions, given the rise of fraudulent transactions posing as substantial financial and security risks. This project utilizes PySpark and machine learning techniques to develop models for predicting fraudulent transactions in an e-commerce setting. A synthetic dataset was acquired from kaggle containing a variety of features commonly found in transactional data, with additional attributes specifically engineered to support the development and testing of fraud detection algorithms. We employed both traditional and deep learning models, including Logistic Regression (LR) and a Recurrent Neural Network (RNN) model called Gated Recurrent Units (GRU), to address the challenge of class imbalance  inherent in fraud detection tasks. Initially, both models achieved high accuracy but struggled with fraud detection due to class imbalance. Predicting fraud detection improved when optimizing strategies were implemented, to include class weighting. The results underscore the importance of model tuning and feature engineering in enhancing the predictive performance of fraud detection systems and the need for continuous refinement in fraud detection methodologies.  

Data:
(a) Data Type: .CSV
(b) Number of Transactions in Version 1: 1,472,952
(c) Number of Transactions in Version 2: 23, 634
(d) Features: 16 (Transaction ID, Customer ID, Transaction Amount, Transaction Date, Payment Method, Product Category, Quantity, Customer Age, Customer Location, Device Used, IP Address, Shipping Address, Billing Address, Is Fraudulent, Account Age Days, and Transaction
Hour)
(e) Fraudulent Transactions: 5

Contents: The contents of the .ipynb file are separated into the following sections:

Processing, EDA, Model Building and Testing, Logistic Regression Model, Logistic Regression Model using hyperparameters, Gated Recurrent Unit (GRU) Model, Gated Recurrent Unit Model optimized to address class imbalance

Stakeholders: Used by financial institutions, consumers, marketing & sales teams, Data Science Teams

Using the Script: The extension of the script is .ipynb so it can be accessed and run within jupyter notebook and exported as a .py to export into any Python IDE

Contributors and Contact List: Shawn Oyer - Drexel University Gradate Student, sbo33@drexel.edu, Leland Ly and Ahmad Javed

License Information: MIT license

Sources:

[1] Bandyopadhyay, Samir Kumar. “(PDF) Detection of Fraud Transactions Using Recurrent Neural Network during COVID-19.” ResearchGate, 2020, Retrieved from url Accessed 16 August 2024.
[2] Hala, Alenzi, and Aljehane Nojood. “Fraud Detection in Credit Cards using Logistic Regression.” The Science and Information (SAI) Organization, 2020. Retrieved from url Accessed 22 August 2024.
[3] Hassan, Najadat. “(PDF) Credit Card Fraud Detection Based on Machine and Deep Learning.” ResearchGate, 26 May 2020. Retrieved from url Accessed 16 August 2024. 
[4] Imane, Sadgali, et al. “Bidirectional gated recurrent unit for improving classification in credit card fraud detection.” Indonesian Journal of Electrical Engineering and Computer Science, vol. 21, no. 3, 2021, pp. 1704-1712. Indonesian Journal of Electrical Engineering and Computer Science. Retrieved from url Accessed 16 August 2024.
[5] Jagtap, Shriyash. “Fraudulent E-Commerce Transactions.” Kaggle, 2024. Retrieved from url Accessed 21 August 2024 
[6] Xurui, Li, et al. “Paper Title (use style: paper title).” arXiv, 2018. Retrieved from url Accessed 16 August 2024 
[7] Zargar, Sakib A. “Introduction to Sequence Learning Models: RNN, LSTM, GRU Sakib Ashraf Zargar Department of Mechanical and Aerospace Engineering.” ResearchGate, 2021. Retrieved from url Accessed 16 August 2024.
