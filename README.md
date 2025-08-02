# Movie_Review_RNN

LIVE : 

## Objective

This project is an End-to-End Sentiment Analysis Pipeline built using PyTorch (Deep Learning) and deployed through Streamlit as an interactive web app. The model classifies movie reviews from the IMDB dataset into Positive or Negative sentiments.

📖 Table of Contents

    Overview
    
    Features
    
    Architecture
    
    Dataset
    
    Installation & Usage
    
    Demo
    
    Results
    
    Tech Stack
    
    Future Enhancements
    

## Overview

Movie reviews are an excellent benchmark for Natural Language Processing tasks.

This project:

    1. Preprocesses text data (cleaning, tokenization, encoding)
    
    2. Trains an LSTM neural network from scratch using PyTorch
    
    3. Deploys an interactive web application using Streamlit

The web app lets users input any movie review and instantly get:

    1. Sentiment classification (Positive/Negative)
    
    2. Confidence score displayed as stars

## Features

    🧠 Deep Learning Model: LSTM-based architecture
    
    🗃 Dataset: IMDB 50,000 labeled reviews
    
    🖥 Interactive Streamlit UI with:
    
        Text input for user reviews
        
        Result display with confidence scores
        
        Custom background and styled UI
        
    ⭐ Confidence visualization using star ratings
    
    🏆 Model accuracy achieved: ~87%

## Tech Stack

    1. Python 3.9+
    
    2. PyTorch for deep learning
    
    3. Streamlit for the interactive web app
    
    4. Pandas, NumPy, scikit-learn for data handling

## Architecture

Steps:

    1. Data Preprocessing
    
    2. Vocabulary Encoding
    
    3. Train/Test Split
    
    4. Model Training (LSTM)
    
    5. Save model (imdb_lstm_model.pth)
    
    6. Deploy on Streamlit

## Model Summary:

    1. Embedding Layer
    
    2. LSTM Layer
    
    3. Dropout (0.5)
    
    4. Fully Connected Layer
    
    5. Sigmoid Output

## Dataset

Dataset used:

IMDB 50K Movie Reviews

    1. 25,000 labeled reviews for training
    
    2. 25,000 labeled reviews for testing
    
    3. Balanced dataset (Positive & Negative reviews)
    

## Output

<img width="1907" height="904" alt="image" src="https://github.com/user-attachments/assets/8e87c41b-35ad-4175-9f19-4878887b5101" />


<img width="1844" height="882" alt="image" src="https://github.com/user-attachments/assets/c26365a3-ba59-4601-8392-c62708c86966" />

