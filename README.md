# 🧠 Groq API Assignment – Conversation Management & Summarization

## 📌 Overview
This project implements **two core tasks** using **Groq APIs (with OpenAI SDK compatibility)**:

1. **Conversation History Management with Summarization**
   - Maintains a running conversation between user and assistant.
   - Applies summarization periodically to keep the history concise.
   - Supports truncation by number of turns and character length.

2. **Summarization with Groq LLM**
   - Uses Groq's `llama-3.1-8b-instant` model for fast and efficient summarization.
   - Demonstrates conversation compression after every `k` turns.

The assignment is implemented in **Google Colab** and uploaded to GitHub for evaluation.

---

## 🚀 Features
- 📜 Maintain full conversation history.
- ✂️ Truncate history by:
  - Number of turns (last *n* messages).
  - Character/word count.
- 🔁 Automatic summarization after every *k* messages.
- ⚡ Powered by Groq LLMs for fast inference.
- 📊 Clear demonstration with sample user–assistant chats.

---

## 🛠️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/archashikamal/groq-api-assignment.git
cd groq-api-assignment
2. Install Dependencies

The project uses Python ≥3.10.
Install required packages:pip install groq openai
3. Get API Key

Sign up at Groq Console
🧩 How It Works

ConversationManager Class

Handles appending messages, truncating history, and applying summaries.

Summarization

After every k user/assistant messages, the history is summarized.

Old history is replaced with a summary + the most recent messages.

Demo

Sample conversations are fed into the system.

Output shows when summaries are applied and how truncation works.
