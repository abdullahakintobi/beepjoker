# 🤖 BeepJokerBot — AI-Powered Joke Generator for Telegram

BeepJokerBot is a Telegram chatbot that uses LLMs to generate a **funny, emoji-filled joke** on any topic you provide! Built with Python, LangChain, and the GROQ API, it listens for mentions in Telegram chats and instantly responds with humor based on the specified topic.

---

## 🚀 Features

- 🤖 Built with **LangChain** and **GROQ’s Gemma2-9b-It** model
- 💬 Generates **one-liner jokes** with emojis on any user-specified topic
- 📱 Operates in Telegram groups or direct chats via mentions
- 🛠️ Uses environment variables and a clean, modular design

---

## 📸 Demo

> **Example Usage:**
> 
> Mention the bot in a chat like:
> 
> ```
> @BeepJokerBot technology
> ```
> 
> **Response:**
> 
> ```
> Why did the computer go to therapy? 🖥️💬 Because it had too many bytes of emotional baggage! 😅
> ```

---

## 🧠 How It Works

1. **User Interaction:** The user mentions the bot with a specific topic (e.g., `@BeepJokerBot cats`).
2. **Topic Extraction:** The bot extracts the specified topic from the message.
3. **Joke Generation:** The topic is fed through a LangChain pipeline that communicates with the GROQ LLM.
4. **Response:** The generated joke is returned and sent to the user in real-time.

---

## 🛠️ Tech Stack

- **Python**
- **Telegram Bot API** via `python-telegram-bot`
- **LangChain** for prompt engineering and chaining
- **GROQ API** using the `Gemma2-9b-It` LLM
- **dotenv** for environment variable management

---

## 🧪 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/abdullahakintobi/telegram-jokes-bot/
cd beep-joker-bot
