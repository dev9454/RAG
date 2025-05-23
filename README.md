Here is the combined content of your project documentation and dependencies in **Markdown (`.md`)** format:

---

````md
# 🧠 Friendly Mental Health Chatbot

A lightweight, friendly, and caring mental health chatbot that responds with short, empathetic messages and uses external resources to improve support.

## 🔍 Features

- 💬 Conversational chatbot with emotional support focus  
- 🧠 Uses Ollama (`llama3`) as the LLM backend  
- 📚 Retrieves relevant mental health info from `mental_health_resources.txt` using embeddings  
- ⏱️ Tracks and plots response time per interaction  
- 🤖 Async-based fast interaction loop  

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-repo/chatbot.git
cd chatbot
````

### 2. Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Ensure Ollama is Running

Install [Ollama](https://ollama.com/) and run the LLM you want:

```bash
ollama run llama3
```

### 5. Prepare Knowledge Base

Place your `mental_health_resources.txt` in the root directory. This file should contain supportive mental health tips and resources.

---

## 🧠 Run the Chatbot

```bash
python chatbot.py
```

You’ll interact with the bot in the terminal. Type `exit` or `quit` to end the conversation and view response time analysis.

---

## 📊 Example Plot

When the chat ends, a plot of chatbot response time per interaction is displayed.

---

## 📁 File Structure

```
chatbot/
│
├── chatbot.py                  # Main chatbot script
├── mental_health_resources.txt # Your knowledge base
├── requirements.txt
└── README.md
```

---

## 📦 Dependencies (`requirements.txt`)

```txt
langchain
langchain-community
langchain-core
langchain-ollama
langchain-huggingface
huggingface_hub
sentence-transformers
chromadb
matplotlib
asyncio
```

---

## 🙏 Acknowledgements

* [LangChain](https://www.langchain.com/)
* [Ollama](https://ollama.com/)
* [HuggingFace Transformers](https://huggingface.co/)
* [ChromaDB](https://www.trychroma.com/)

---

## 💙 Disclaimer

This is not a replacement for professional mental health help. Always consult licensed professionals when needed.

```

---

You can save this into a file named `README.md` to serve as the documentation for your project. Let me know if you want badges (e.g. Python version, license), Docker support, or Hugging Face integration!
```
