# internship-project1
spam mail and facial recognition
A self-contained Machine Learning project built using Python to identify and filter out unwanted spam text messages/emails from legitimate communications (ham). The project trains, optimizes, and evaluates multiple classic textual classification algorithms on the Kaggle/UCI SMS Spam Collection Dataset using Term Frequency-Inverse Document Frequency (TF-IDF) feature vectorization.

Key Project Features
Production-Grade NLP Pipeline: Cleans unformatted, raw text by processing character case, filtering out digit/punctuation noise, tokenizing, and stripping standard English stop words.
Offline-Ready Execution: Engineered to run safely without structural internet dependencies or dynamic dataset resource downloads.
Multi-Algorithm Assessment: Evaluates and compares three benchmark models: Multinomial Naive Bayes, Logistic Regression, and Support Vector Machine (SVM).
High-Precision Deployment Configuration: Optimized to achieve 100% Precision using a linear-kernel SVM configuration to guarantee zero False Positives (legitimate messages mistakenly flagged as spam).
output
End-to-End Workflow & Architecture
The system treats textual analysis as a sequential pipeline, converting unstructured strings into deterministic binary outcomes:

Text Preprocessing: Case mapping 
→
 Regex pattern purification 
→
 Token splitting 
→
 Stopword removal.
Feature Extraction (TF-IDF):Transforms text tokens into a statistical numerical feature matrix representing the top 3,000 highest-signal words.
Data Partitioning: Uses an 80/20 train/test split utilizing target stratification to handle severe category imbalances (86.6% Ham vs. 13.4% Spam).
Supervised Training & Evaluation: Fits multiple statistical classifiers and returns exact comparative matrices.
Face Recognition Attendance System

An AI-based attendance system that uses face recognition to automatically detect and mark attendance in real-time using a webcam.

Features

Real-time face detection and recognition -Deep learning-based face embeddings (FaceNet) -Automatic attendance logging (CSV file) -Fast and contactless system -Simple and easy-to-use interface
