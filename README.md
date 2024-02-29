# chatbot
Deep learning Chatbot
# Chatbot Project

This project implements a simple chatbot using Natural Language Processing (NLP) techniques with the help of libraries such as nltk, tflearn, and tensorflow.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Files and Directories](#files-and-directories)
- [Dependencies](#dependencies)
- [License](#license)

## Overview

The chatbot is trained to understand and respond to user input based on predefined intents stored in a JSON file. It uses the Lancaster Stemmer for word stemming and employs a neural network model built using tflearn and tensorflow for intent recognition.

## Setup

1. **Install Dependencies:**

   ```bash
   pip install nltk tflearn tensorflow


2. **To run**
   ```bash
   python chatbot.py

## **Usage**

Start a conversation with the chatbot by entering text when prompted.
Type "quit" to exit the chat.

## **Files and Directories**

chatbot.py: Main script containing the chatbot implementation.

intents.json: JSON file containing predefined intents for training the chatbot.

data.pickle: Pickle file storing preprocessed data for training the neural network.

model.h5: Trained neural network model saved in HDF5 format.

## **Dependencies**
   
nltk: Natural Language Toolkit.
tflearn: Deep learning library.
tensorflow: Open-source machine learning library.

## **License**

This project is licensed under the MIT License.

