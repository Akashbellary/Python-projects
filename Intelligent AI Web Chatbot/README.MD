# Intelligent AI Web Chatbot

This project is done by Akash BR.
Want to know more about Me. LinkedIn: https://www.linkedin.com/in/akash-br-b86a94219/

# About the project

The aim of this project was to impliment Natural Language Process (NLP) into a practicle project.We have used NLTK and Tensorflow, two of the most famous AI and ML Libraries. This project guides you through creating, training, and integrating a chatbot into a web application.

## Features

- Train a chatbot from scratch (no pre-trained large language models)
- Implement intents and patterns for a variety of queries
- Integrate the trained chatbot into a Flask web application
- Interact with the chatbot through a web interface

## Project Structure

### Model Training

- Train the model based on an intents file
- Lemmatize, tokenize, and create a bag of words for training
- Use TensorFlow to build and train the neural network

### Backend (Flask)

- Set up the Flask application
- Integrate the trained model to perform inference

### Frontend (HTML, CSS, JavaScript)

- Create a simple chat interface
- Use JavaScript to interact with the Flask backend

## Getting Started

### Prerequisites

- Python
- TensorFlow
- Flask
- NLTK
- Numpy

### Installation

1. **Install the required packages**:

   ```bash
   pip install numpy tensorflow flask nltk
   ```

2. **Download NLTK data**:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```
