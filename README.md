# Advanced-Agentic-AI_Multi-Agent-Workflow_CrewAI_seper_Gemini-LLM-Orchestrator
# 🤖 Multi-Agent AI Learning System (CrewAI + Gemini + Gradio)

This project is a **Multi-Agent AI System** where multiple intelligent agents collaborate to understand, explain, and simplify any topic.

It uses **CrewAI for orchestration**, **Google Gemini as the LLM**, and **Gradio for the user interface**.

---

## 🚀 Features

- 🤖 Multi-agent collaboration (Teacher, Researcher, Simplifier, Student, Examiner)
- 🧠 Powered by Google Gemini (LLM)
- 🌐 Real-time web search using Serper API
- 💬 Interactive Gradio UI
- 📚 Generates explanations, notes, and questions automatically

---

## 🧠 How It Works

The system uses 5 AI agents:

- **Teacher** → Explains the topic step-by-step  
- **Researcher** → Finds latest and relevant information  
- **Simplifier** → Converts complex concepts into simple language  
- **Student** → Writes short notes  
- **Examiner** → Generates questions  

All agents work together using CrewAI to produce structured output.

---

## 🛠️ Tech Stack

- Python  
- CrewAI  
- Google Gemini (via LangChain)  
- Serper API (Search Tool)  
- Gradio (Frontend UI)  

---

## 📦 Installation

```bash
pip install crewai crewai-tools gradio langchain-google-genai python-dotenv
