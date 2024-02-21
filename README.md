# ChatBot_Project

<p> This project entails the development of an artificial intelligence application aimed at creating a conversational bot. The chatbot utilizes deep learning techniques to comprehend user queries and provide appropriate responses. The project showcases the creation of a text-based conversational agent capable of engaging in dialogue using technologies such as natural language processing (NLP) and artificial neural networks. The project analyzes user inputs to identify specific intents and generate suitable responses. For instance, when a user seeks information about a product or requests support for a service, the bot can produce relevant responses tailored to the user's query. Key components of this project include training deep learning models, word tokenization, intent recognition, and response generation. Additionally, the project provides examples on how to utilize the trained model effectively. </p>

## Project File Structure
- **Train_chatbot.py:** In this file, I build and train the deep learning model that can classify and identify what the user is asking to the bot.
- **Gui_Chatbot.py:** This file is where I build a graphical user interface to chat with our trained chatbot.
- **Intents.json:** The intents file has all the data that I use to train the model. It contains a collection of tags with their corresponding patterns and responses.
- **Chatbot_model.h5:** This is a hierarchical data format file in which I store the weights and the architecture of my trained model.
- **Classes.pkl:** The pickle file can be used to store all the tag names to classify when I predict the message.
- **Words.pkl:** The words.pkl pickle file contains all the unique words that are the vocabulary of my model.

## Getting Started
1. train_chatbot.ipynb: `Downloading libraries and loading data, Data Preprocessing, Creating Training and Test Data, Model Training `
2. Gui_Chatbot.py : `Creating chatbot GUI and running the chatbot`

## Screenshots
![Chatbot GUI](screenshots/gui.png)

## References
- [Deep Learning Models](https://example.com/deep-learning)
- [Natural Language Processing](https://example.com/nlp)
