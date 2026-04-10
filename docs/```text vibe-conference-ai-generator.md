# Conference Talk Abstract Generator

A RAG-powered AI application that generates high-quality conference talk proposals by combining historical data with real-time research.

---

## 🚀 Features

- 🔍 Vector search over past conference talks (Couchbase)
- 🌐 Real-time research using agent-based pipeline
- 🧠 LLM synthesis using Nebius API
- ⚡ Streamlit UI for quick interaction
- 🧩 Multi-stage RAG pipeline

---

## 🧠 Architecture

This system follows a multi-stage pipeline:

1. **User Input**
2. **Vector Search (Historical Talks)**
3. **Real-Time Research Agent**
4. **Context Fusion**
5. **LLM Generation**

---

## ⚙️ Setup

### 1. Clone Repo

```bash
git clone https://github.com/Arindam200/awesome-ai-apps.git
cd advance_ai_agents/conference_talk_abstract_generator
2. Install Dependencies
pip install -r requirements.txt
3. Setup Environment
cp .env.example .env

Add your Nebius credentials:

NEBIUS_API_KEY=your_key_here
NEBIUS_API_BASE=https://api.studio.nebius.ai/v1
▶️ Run
python main.py
💡 Usage
Enter your conference idea
System retrieves similar talks
Research agent gathers latest trends
AI generates a polished proposal
🧩 Tech Stack
LLM Provider: Nebius
Model: mistral / e5-mistral embeddings
Framework: OpenAI SDK (compatible mode)
Frontend: Streamlit
Vector DB: Couchbase
Agents: ADK-style research agent
📌 Example Output
Title
Abstract
Key Takeaways
⚠️ Notes
Requires Nebius API key
Couchbase connection can be extended for real data
ADK agent is simplified placeholder
📄 License
MIT

