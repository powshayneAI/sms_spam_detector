# sms_spam_detector

## Overview
This project implements a machine learning-based SMS spam detection system using Linear Support Vector Classification (SVC). The application is deployed through a Gradio interface, allowing users to input text messages and receive immediate feedback on whether the message is classified as spam or legitimate (ham).

## Features

- Text message classification using Linear SVC
- Interactive web interface built with Gradio
- Real-time prediction feedback
- Pre-trained model using SMS spam collection dataset

## Technologies Used

- Python
- Scikit-learn
- Pandas
- Gradio
- Natural Language Processing (NLP) techniques

## Model Details
The spam detection system uses:

- Linear Support Vector Classification
- TF-IDF vectorization for text feature extraction
- 67%/33% train-test split
- Pipeline architecture for streamlined preprocessing and prediction

## Sample Test Messages
You can test the application with these example messages:
1. You are a lucky winner of $5000!
2. You won 2 free tickets to the Super Bowl.
3. You won 2 free tickets to the Super Bowl. Text us to claim your prize.
4. Thanks for registering. Text 4343 to receive free updates on medicare.
