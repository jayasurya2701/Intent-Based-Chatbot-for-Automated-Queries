# Vendor Communication Chatbot with Machine Learning  

## Overview  
This project showcases the development of vendor communication chatbot capable of recognizing user intents and delivering accurate responses using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The chatbot leverages a **Support Vector Machine (SVM)** classifier, trained on a dataset of labeled intents, to classify input queries and generate dynamic responses.

## Features  
- **Intent Classification:** Identifies user intent using a trained SVM model.  
- **Text Preprocessing:** Utilizes tokenization, lemmatization, and TF-IDF vectorization for efficient NLP processing.  
- **Interactive Responses:** Responds to user queries with relevant and context-aware answers.  
- **Model Optimization:** Includes hyperparameter tuning with GridSearchCV for improved accuracy.  
- **User-Friendly Interface:** Provides an interactive environment for real-time communication.  

## Technologies Used  
- **Programming Language:** Python  
- **Libraries:** `json`, `numpy`, `nltk`, `scikit-learn`  
- **Machine Learning Algorithm:** Support Vector Machine (SVM)  
- **NLP Techniques:** Tokenization, Lemmatization, TF-IDF  

## How It Works  
1. **Dataset Loading:** The chatbot uses a labeled dataset (`intents.json`) containing patterns and corresponding intents.  
2. **Data Preprocessing:** Input text is tokenized, lemmatized, and vectorized using the TF-IDF method.  
3. **Model Training:** An SVM classifier is trained on the preprocessed data, with hyperparameters tuned using GridSearchCV.  
4. **Real-Time Interaction:** User input is classified into intents, and the bot selects a suitable response from the dataset.

## Applications  
- Virtual assistants for customer support.  
- FAQ bots for websites.  
- Educational and productivity tools.  
