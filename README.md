# Smart Conversational Agent for Mental Health Support

## Project Overview

This project focuses on developing a Smart Conversational Agent to provide mental health support. The agent is designed to engage users in natural and empathetic conversations, leveraging various techniques including rule-based methods, retrieval-based approaches, and generative models. The primary objective is to offer accessible and supportive interactions for individuals seeking mental health assistance.

## Features

### 1. Rule-Based Methods
- **CountVector and TF-IDF**: Utilized for initial response generation, these methods help in identifying relevant responses based on keyword matching and frequency.
- **Similarity Matrices**: Implemented to enhance the accuracy of responses by considering semantic similarity between user input and pre-defined responses.

### 2. Retrieval-Based Techniques
- **Convolutional Neural Networks (CNNs)**: Used to identify patterns and features in the text data.
- **Recurrent Neural Networks (RNNs)**: Employed for their ability to capture sequential information, crucial for understanding the context of conversations.
- **Long Short-Term Memory Networks (LSTM) and Gated Recurrent Units (GRU)**: Applied to manage long-term dependencies and improve the context retention in conversations.
- **Bidirectional LSTM (BiLSTM)**: Enhanced the model's ability to understand the context from both past and future data points.

### 3. Generative Models
- **GPT-2 and GPT-3.5 Turbo**: Utilized for generating human-like responses, ensuring that conversations feel natural and empathetic.
- **Cohere, MistralAi, and Ai21 Studio**: Additional generative models incorporated to diversify response styles and improve the quality of interactions.

## Project Structure

- **data/**: Contains datasets used for training and evaluation.
- **notebooks/**: Jupyter notebooks for data preprocessing, model training, and evaluation.
- **models/**: Pre-trained and fine-tuned model files.
- **scripts/**: Python scripts for data preprocessing, training, and deployment.
- **docker/**: Dockerfiles and related configuration for containerization.
- **kubernetes/**: Kubernetes deployment files for scaling and managing the application.
