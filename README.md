
---

## ✅ `README.md` for the **Backend (Flask + Ollama)**

# ⚙️ AI Chatbot Backend — Flask + Ollama

This is the **backend API** for my AI chatbot project.  
It acts as a bridge between the **React frontend** (deployed on Netlify) and the **Ollama local LLM engine**.


### ✨ Features

- Accepts messages from a frontend client (React)
- Communicates with Ollama running locally to generate responses
- Sends back the AI-generated reply to the frontend
- Lightweight and easily extendable


### 🔗 Frontend

➡️ [React Frontend Repo](https://github.com/your-username/your-frontend-repo)  
🔗 [Live App on Netlify](https://chatbot-react25.netlify.app/)



### 🛠️ Local Installation

#### 1. Prerequisites

- Python 3.10+
- [Ollama](https://ollama.com/) installed and running locally
- A downloaded model like `llama3` or `phi3`
- A running frontend (optional but recommended)

#### 2. Clone & Run

```bash
git clone https://github.com/Ayoub-ben-hamada/chatbot-backend.git
cd backend-folder
pip install -r requirements.txt
ollama run llama3  # or use `phi3` for a lighter model
python app.py
```
