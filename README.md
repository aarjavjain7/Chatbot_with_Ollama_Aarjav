# 🧠 LocalMind AI — Your Private Local Chatbot

**LocalMind AI** is a lightweight conversational AI application that lets you interact with locally running Large Language Models (LLMs) through a browser-based interface. Built with Python, Streamlit, LangChain, and Ollama, it brings AI-powered conversations directly to your computer without requiring external LLM APIs.

## ✨ Features

- 💬 Interactive chat interface powered by Streamlit
- 🏠 Run open-source language models locally with Ollama
- 🔒 Keep prompts and inference local with a fully local setup
- ⚡ Generate responses without relying on paid LLM APIs
- 🔄 Experiment with different Ollama-compatible models
- 🎯 Beginner-friendly setup and modular architecture

## 🛠️ Technology Stack

- **Python** — Core application logic
- **Streamlit** — Web interface
- **LangChain** — Language model integration
- **Ollama** — Local LLM runtime
- **Gemma 2B** — Example model

## 📂 Project Structure

```text
LocalMind-AI/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Aarjav/LocalMind-AI.git
cd LocalMind-AI
```

*Make sure the repository exists under your GitHub account before using this command.*

### 2. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Install Ollama

Download Ollama from the official website:

https://ollama.com/download

### 5. Download a language model

For Gemma 2B, run:

```bash
ollama pull gemma:2b
```

You can use other supported models, such as `llama3`, `mistral`, or `phi3`, by updating the model configuration in your application accordingly.

### 6. Start the application

```bash
streamlit run app.py
```

Open the following address in your browser:

http://localhost:8501

## 🔍 How It Works

1. The user enters a question through the Streamlit interface.
2. LangChain handles the interaction with the configured language model.
3. Ollama runs the selected model locally and generates a response.
4. The response appears in the chatbot interface.

## 🧪 Planned Improvements

- [ ] Conversation memory
- [ ] Interactive model selection
- [ ] Persistent chat history
- [ ] Document question answering with RAG
- [ ] Voice input and output
- [ ] Configurable model parameters
- [ ] Docker support
- [ ] Deployment options

## 🤝 Contributing

Contributions and suggestions are welcome. Fork the repository, develop your improvements, and submit a pull request.

## 📄 License

Licensed under the MIT License, provided the repository includes the corresponding license file.

## 👨‍💻 Author

**Aarjav**

- GitHub: https://github.com/Aarjavjain7

---

*LocalMind AI — Your AI, your machine, your control.*
