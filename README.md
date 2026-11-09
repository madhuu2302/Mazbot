# 🧠 MAZBOT – Memory-Based AI Chatbot

### Think. Learn. Remember. Respond.

MAZBOT is an intelligent AI chatbot developed using Python, Streamlit, LangChain, and Ollama. It provides interactive conversations and remembers previous messages within the active chat session using LangChain's InMemoryChatMessageHistory.

## 🚀 Features

- **AI-Powered Conversations:** Provides intelligent responses using local Ollama models.
- **Conversation Memory:** Remembers previous messages and maintains conversation context.
- **Multiple AI Models:** Supports Gemma 3, Llama 3.2, and Qwen 2.5.
- **Interactive Interface:** User-friendly Streamlit interface with a dark purple theme.
- **Session Management:** Maintains separate conversation sessions.
- **Clear Conversation:** Allows users to reset chat history.
- **Suggested Questions:** Provides sample questions to help users get started.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Streamlit | User interface |
| LangChain | AI application framework |
| Ollama | Local AI model execution |
| InMemoryChatMessageHistory | Conversation memory |
| UUID | Session identification |

## 📂 Project Structure

```text
Mazbot/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd Mazbot
```

### 3. Install Ollama

Download Ollama from:

https://ollama.com/

### 4. Download an AI Model

```bash
ollama pull gemma3:1b
```

### 5. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
streamlit run app.py
```

The MAZBOT application will open in your browser.

## 🧠 How Conversation Memory Works

MAZBOT uses LangChain's `InMemoryChatMessageHistory` to store previous user and assistant messages.

**Example:**

User: My name is Madhu.

MAZBOT: Nice to meet you, Madhu!

User: What is my name?

MAZBOT: Your name is Madhu!

The chatbot uses previous conversation history to generate context-aware responses.

## 🔄 Application Workflow

1. User enters a question.
2. Streamlit receives the input.
3. LangChain retrieves the previous conversation history.
4. Ollama processes the input using the selected AI model.
5. The chatbot generates a response.
6. Conversation history is updated.
7. The response is displayed to the user.

## 🎯 Future Enhancements

- Persistent conversation storage.
- Multiple chat sessions.
- Voice-based interaction.
- Document-based question answering.
- Improved chatbot personalization.
- Cloud-based AI model integration.

## 👩‍💻 Developer

MADHUMITHA U



### MAZBOT – Your Intelligent Conversation Companion 🧠
