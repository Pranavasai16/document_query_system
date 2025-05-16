# 📄 Document Query System 💁

Welcome to **Document Query System**, your smart assistant to interact with Word documents! 🚀  
Just upload `.docx` files and ask questions — our AI will dig out accurate answers from your content using Google Generative AI and LangChain. 💬📚

---

## ✨ Features

- 🔐 **User Registration & Login** – Secure authentication with hashed passwords.
- 📂 **Upload Word Docs** – Accepts multiple `.docx` files.
- 🧠 **AI-Powered QA** – Uses Gemini Pro to answer user queries based on document context.
- 🧩 **Text Chunking** – Efficient splitting of large documents for accurate embedding.
- 💾 **Vector Database** – FAISS-powered local vector store for similarity-based search.
- 🌐 **Built with Streamlit** – Clean, fast, and interactive UI.

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.8 or higher
- Google Generative AI API key

### 📦 Installation

**Clone the repository**
   ```bash
   git clone https://github.com/Pranavasai16/document_query_system.git
   cd document_query_system
   ```
**Install dependencies**
```bash
pip install -r requirements.txt
```
**Add your Google API key to .env**
```bash
GOOGLE_API_KEY=your_api_key_here
```
**Run the app**
```bash
streamlit run main.py
```

🗂️ Project Structure
```bash
document_query_system
├── main.py              # Main Streamlit application
├── requirements.txt     # Required Python libraries
├── users.db             # SQLite DB for login credentials
├── embeddings.db        # Local FAISS vector storage
└── .env                 # Environment config with API key
```
🙌 Contributions
Contributions are welcome and appreciated! 💖


If you'd like to improve this project:

🍴 Fork the repository
🛠️ Create your feature branch (git checkout -b feature-name)
✅ Commit your changes (git commit -m 'Add feature')
📤 Push to the branch (git push origin feature-name)
🔃 Open a Pull Request


Let’s build something amazing together! 💫
