# 🤖 Conversational Q&A Chatbot with LangChain & Streamlit

[![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red?logo=streamlit)](https://streamlit.io/)
[![LangChain](https://img.shields.io/badge/LangChain-0.3.26-blue)](https://www.langchain.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green?logo=openai)](https://platform.openai.com/)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An interactive chatbot built using **LangChain**, **OpenAI GPT**, and **Streamlit**. It allows users to ask questions and receive intelligent, contextual responses in real time.

---

## 🧩 Features

- ✅ Conversational UI built with Streamlit
- 🤖 Integrated with OpenAI's GPT models using LangChain
- 💬 Maintains context using LangChain message schema
- 🔐 Secure API key handling with `.env` file

---

## 📁 Project Structure

```
.
├── chatbot.py                 # Streamlit chatbot app
├── requirements.txt          # Project dependencies
├── .env                      # Contains OpenAI API key (not committed)
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-sivarajes/LLM_Chatbot/tree/main
cd conversational-chatbot
```

### 2. (Optional) Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate         # On Windows
source venv/bin/activate      # On macOS/Linux
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Add Your OpenAI API Key

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_key_here
```

---

## ▶️ Run the App

```bash
streamlit run chatbot.py
```

Visit: [http://localhost:8501](http://localhost:8501)

---

## 💬 Example Interaction

> **You:** What is the capital of Russia?  
> **Bot:** Moscow

---

## 📦 Dependencies

```text
langchain
openai
huggingface_hub
streamlit
python-dotenv
```

---

## 🛠 Tech Stack

- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [Streamlit](https://streamlit.io/)
- [Python Dotenv](https://pypi.org/project/python-dotenv/)

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙌 Contributions

Contributions are welcome! Please open an issue or pull request to get started.  
If you find this project useful, please ⭐️ star it on GitHub!
