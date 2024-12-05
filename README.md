# 🤖 Python Chatbot Project
Welcome to the Python Chatbot project. This repository contains a feature-rich chatbot built using Python. The bot can handle basic user interactions, detect intent, perform sentiment analysis, set reminders, provide trivia and jokes, and even make recommendations.

## 📚 Features
- `Smart Intent Detection`: Recognizes user intents like greetings, help requests, feedback, complaints, and more.
- `Multi-functional`:
  - Weather updates 🌦️
  - Trivia & jokes 🤓😂
  - Reminders ⏰
  - Personalized recommendations for books, movies, and songs 🎵📖🎥
- `Sentiment Analysis`: Understands the tone of user input (positive, negative, neutral).
- `Multi-language Support`: Translate user input and bot responses with googletrans. 🌐
- `Custom Context`: Tailors responses using user context and session data.
- `Feedback Collection`: Prompts users for feedback at the end of the chat.

  
## 🚀 Getting Started

#### Prerequisites
- Python 3.8+
- Required Python libraries:
pip install random requests textblob transformers googletrans

#### Usage
1. Clone the repository:
git clone [[https://github.com/your-username/python-chatbot.git](https://github.com/priyankaa-roy/Python-Chatbot/tree/main)](https://github.com/priyankaa-roy/Python-Chatbot)

2. Navigate to the project directory:
cd python-chatbot

3. Run the chatbot:
python python_chatbot.py

## 💡 How It Works
1. `Intent Recognition`: Uses transformers to classify user input into predefined intents.
2. `Dynamic Response`: Selects random responses or generates data (like jokes, trivia, or recommendations).
3. `Reminder Feature`: Allows users to set time-based reminders.
4. `API Integration`: Fetches real-time weather updates using OpenWeatherMap.
5. `Logs Conversations`: Records user interactions for debugging and improvement.

   
## 🛠️ Tech Stack
- Language:  Python 🐍
- Libraries:
   - Random: For selecting responses
   - Transformers: For intent detection
   - TextBlob: For sentiment analysis
   - GoogleTrans: For translation
   - Logging: For maintaining activity logs
- APIs:
   - OpenWeatherMap for weather updates


## 🤝 Contribution
Feel free to fork this repository and submit pull requests. Contributions are always welcome!


## 📜 License
This project is licensed under the MIT License.


## 🌟 Show Your Support
Give this project a ⭐ if you found it interesting or helpful!


## 🖼️ Demo
Here's a quick interaction with the bot:

Chatbot: Hello! I am your support assistant. Type 'exit' to end the chat.  
You: Hi!  
Chatbot: Hello! How can I help you today?  
You: Can you tell me a joke?  
Chatbot: Why don’t skeletons fight each other? They don’t have the guts!  
You: Remind me in 10 minutes to check my email.  
Chatbot: Your reminder has been set for 14:20! I'll remind you then.  
You: Exit  
Chatbot: Thank you for your feedback! Goodbye! Have a great day!  
