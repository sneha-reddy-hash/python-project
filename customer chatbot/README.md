# 🤖 DathBot – Rule-Based Customer Support Chatbot

## 📌 Project Overview

**DathBot** is a Python-based Rule-Based Customer Support Chatbot designed to answer common customer queries automatically. It uses predefined keywords and rules to identify user questions and generate appropriate responses.

The chatbot provides information about business hours, products, pricing, delivery, returns, refunds, and customer support.

It also supports greeting detection, goodbye messages, and a help command to improve the user experience.

## 🎯 Objectives

- Automate basic customer support.
- Provide instant responses to frequently asked questions.
- Identify user queries using keyword matching.
- Reduce manual customer support work.
- Maintain a simple and interactive conversation.

## ✨ Features

- **Greeting Detection:** Responds to greetings such as Hi, Hello, and Hey.
- **Business Hours:** Provides business opening and closing timings.
- **Product Information:** Answers questions about available products and services.
- **Pricing Information:** Responds to product price-related queries.
- **Delivery Information:** Provides delivery and tracking guidance.
- **Return and Refund Support:** Gives information about returns and exchanges.
- **Contact Support:** Guides customers to the official contact page.
- **Help Command:** Displays available chatbot topics.
- **Goodbye Detection:** Ends the conversation properly.
- **JSON Data Storage:** Saves and loads FAQ information using a JSON file.
- **Error Handling:** Handles unexpected errors without immediately terminating the chatbot.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| re | Regular expression and keyword matching |
| JSON | FAQ data storage |
| datetime | Time-based greetings |
| VS Code | Development environment |

## 📂 Project Structure

```text
DathBot/
│
├── chatbot.py
├── faq_dataset.json
└── README.md
```

**File Description:**

- `chatbot.py` – Contains the complete chatbot implementation.
- `faq_dataset.json` – Stores frequently asked questions and responses.
- `README.md` – Contains project documentation and instructions.

*Note: The JSON file is automatically created when it does not already exist.*

## ⚙️ How to Run the Project

### Step 1: Install Python

Download and install Python from:

https://www.python.org/downloads/

### Step 2: Open VS Code

Open Visual Studio Code and create a folder named `DathBot`.

### Step 3: Create Python File

Create a file named:

`chatbot.py`

Copy and paste the chatbot source code into this file.

### Step 4: Open Terminal

In VS Code, select:

Terminal → New Terminal

### Step 5: Run the Program

Execute the following command:

```bash
python chatbot.py
```

### Step 6: Start Chatting

Enter your questions and receive automatic responses from DathBot.

## 💬 Sample Output

```text
=======================================================
Welcome to DathBot!
Your Rule-Based Customer Support Assistant
=======================================================
Type 'help' to see available topics.
Type 'bye', 'exit', or 'quit' to end the chat.

You: Hello

Bot: Good afternoon! I'm DathBot,
your customer support assistant.

You: What are your business hours?

Bot: Our business hours are Monday to Saturday,
9:00 AM to 6:00 PM.

You: What products are available?

Bot: We offer a range of products and services.
Please specify the product you are interested in.

You: Thank you

Bot: You're welcome! I'm happy to help.

You: bye

Bot: Thank you for chatting with me. Goodbye!
```

## 🧠 Python Concepts Used

1. **Functions:** Divides the program into reusable functions.
2. **Dictionaries:** Stores FAQ questions, keywords, and responses.
3. **Lists:** Maintains keywords and identified intents.
4. **Conditional Statements:** Selects appropriate responses.
5. **Loops:** Maintains continuous chatbot interaction.
6. **Regular Expressions:** Identifies keywords and greetings.
7. **Exception Handling:** Handles errors using try-except.
8. **File Handling:** Reads and writes JSON files.
9. **String Manipulation:** Normalizes user input.
10. **Date and Time:** Generates time-based greetings.

## 🚀 Future Enhancements

- Add a graphical user interface (GUI).
- Integrate a database to store customer conversations.
- Add voice-based interaction.
- Support multiple languages.
- Integrate AI and Natural Language Processing (NLP).
- Develop a web-based customer support chatbot.

## 🎓 Learning Outcomes

Through this project, I learned how to:

- Develop a rule-based chatbot using Python.
- Implement keyword-based intent recognition.
- Work with JSON files for data storage.
- Handle user input and generate responses.
- Apply exception handling and modular programming.

## 👨‍💻 Author

**Sneha Reddy Madduri**

## 📄 License

This project is created for educational and learning purposes.

---

⭐ If you find this project useful, feel free to star the repository!
