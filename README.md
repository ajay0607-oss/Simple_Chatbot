##🤖 Basic Rule-Based Chatbot
##📌 Overview

This is a simple rule-based chatbot built in Python.
It responds to user inputs like greetings, small talk, and exit commands using a predefined dictionary of responses.

The chatbot uses:

Dictionary lookup for responses

Random choice from multiple possible replies

Partial matching so that "hello there" still matches "hello"

Loop to keep the conversation going until the user says "bye"
----
##🛠️ Features

✅ Handles basic greetings like hello

✅ Responds to small talk (how are you, what is your name?)

✅ Supports multiple random responses for variety

✅ Works with partial input matching (e.g., hello buddy → hello)

✅ Exits gracefully when user says bye with a random goodbye message
----
## 🚀 How to Run

Make sure you have Python 3.x installed.

Save the script as chatbot.py.

Open a terminal in the same directory.

--
Run the chatbot:

python chatbot.py
--

Start chatting with the bot. Type bye to exit.
----
##💡 Example Interaction
You: hello
Bot: Hola Amigo!
You: how are you doing today?
Bot: I am surviving, how about you?
You: what is your name?
Bot: Ore wa Tenjin des.
You: bye
Bot: Sayonara!
-----
##📖 Key Concepts Used

if-elif conditions (with dictionary lookup)

Functions (chatbot() function for execution)

Loops (while True for continuous chatting)

Input/Output (user messages and bot replies)

Random Module (to pick random replies)
----
