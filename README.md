# chatbot
Deep learning Chatbot
## Overview

The chatbot is trained to understand and respond to user input based on predefined intents stored in a JSON file. It uses the Lancaster Stemmer for word stemming and employs a neural network model built using tflearn and tensorflow for intent recognition.

## Setup

1. Install the required dependencies:

   ```bash
   pip install nltk tflearn tensorflow

2. To run
python chatbot.py

Usage:
Start a conversation with the chatbot by entering text when prompted.
Type "quit" to exit the chat.
chatbot.py: Main script containing the chatbot implementation.
intents.json: JSON file containing predefined intents for training the chatbot.
data.pickle: Pickle file storing preprocessed data for training the neural network.
model.h5: Trained neural network model saved in HDF5 format.
