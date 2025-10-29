## Chatbot Implementation
#  Chatbot using NLP and Streamlit

This project is a simple but functional chatbot built using Natural Language Processing (NLP) techniques and Logistic Regression. The chatbot classifies user input into predefined intents and responds accordingly. The entire chatbot interface is built using Streamlit, providing an interactive web application for real-time conversations.

##  Key Features

- Intent classification using LogisticRegression
- Training data defined via a structured Intents.json file
- Interactive Streamlit for chatting
- Conversation history saved to chat_log.csv
- Randomized responses per intent
- Fully local – no external API like OpenAI is required


## 📁 Project Structure
- Chatbot.py
- Intents.json
- README.md
- chat_log.csv
- implementation.ipynb

## 🛠 Requirements

- Python 3.8+
- Packages:
  - nltk
  - scikit-learn
  - streamlit
