# 🤖 Simple GMail Assistant (n8n Workflow)

This project is a smart AI-powered chat agent built using **n8n**. It integrates with **Google Gemini (PaLM)**, **Gmail**, and **window buffer memory** to create an interactive chat experience.

## ✨ Features

- 🔗 Integrated with **Gemini (Google PaLM)** for natural language understanding
- 📩 Fetches the **last 10 Gmail messages** on command
- 🧠 Context awareness with **window buffer memory (last 10 interactions)**
- 🧠 Built using **n8n Langchain Agent**, no-code workflow automation

## 🚀 How It Works

1. User sends a chat message (e.g., "Get my last 10 mails").
2. n8n receives the message via webhook trigger.
3. Gemini processes the intent and routes it to Gmail.
4. Emails are fetched and returned through the agent.

## 🛠️ Technologies

- [n8n](https://n8n.io/) – Workflow automation platform
- [Langchain](https://www.langchain.com/) – AI agents and tool integration
- Google Gemini (PaLM API)
- Gmail API

## 📁 Workflow File

The file `Simple Chatbox AI.json` contains the full n8n workflow. You can import this into your local or hosted n8n instance.

## 🧪 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR-USERNAME/simple-chatbox-ai.git
2. Open your n8n instance and import the workflow file Simple Chatbox AI.json.

3. Set up the required credentials:

    Google Gemini (PaLM API)

    Gmail OAuth2

4. Run the workflow and trigger the webhook (or connect it to a frontend/chat system).

