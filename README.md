# 📚 AI Infinite Knowledge Feed

An AI-powered application that generates an endless stream of fact cards from Wikipedia using **Retrieval-Augmented Generation (RAG)**. The application retrieves relevant information from a Wikipedia-based knowledge base and uses a Large Language Model (LLM) to generate concise, engaging, and accurate insights in real time.

## ✨ Features

- 📖 Fetches content from Wikipedia
- 🧠 Builds a knowledge base using text chunking
- 🔍 Retrieval-Augmented Generation (RAG)
- 🤖 AI-generated fact cards
- ♾️ Endless scrolling experience
- ⚡ Live card generation (no pre-generated content)
- 🎨 Interactive Gradio interface

---

## 🛠️ Tech Stack

- Python
- Gradio
- Wikipedia API
- LangChain
- FAISS
- Sentence Transformers
- Groq API (Llama 3.3 70B Versatile)

---

## 📂 Project Structure

```text
AI-Infinite-Knowledge-Feed/
│── mini_pro_kerala.ipynb
│── README.md
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/AI-Infinite-Knowledge-Feed.git
cd AI-Infinite-Knowledge-Feed
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Set your Groq API key

```python
import os

os.environ["GROQ_API_KEY"] = "your_api_key"
```

---

## 📖 How It Works

1. Select a topic.
2. Wikipedia pages are downloaded.
3. Text is cleaned and split into chunks.
4. Chunks are stored as the knowledge base.
5. Clicking **Next Card** retrieves a relevant chunk.
6. The LLM generates a unique 1–2 sentence fact card.
7. The process repeats indefinitely, creating an endless knowledge feed.

---

## 📸 Demo

## Login Page
(llm_kerala feed.png)

---

## 🌟 Future Enhancements

- Support multiple topics
- Improved semantic retrieval
- Save favorite fact cards
- Multi-language support
- Responsive mobile interface

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Anusha Antony**

B.Tech Computer Science & Engineering
