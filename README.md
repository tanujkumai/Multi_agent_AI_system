# 🔬 ResearchMind — Multi-Agent AI Research System

**Tools Used:** Python · LangChain · Streamlit · OpenAI · Tavily API · BeautifulSoup  
**Skills Demonstrated:** Multi-Agent Systems · LLM Orchestration · Tool Integration · Web Scraping · AI Pipelines  

---

## 📌 Overview

ResearchMind is an **AI-powered research assistant** that uses a **multi-agent architecture** to autonomously gather information, analyze sources, generate structured reports, and critique its own output.

Instead of relying on a single LLM call, this system demonstrates how to build **agentic AI workflows**, where multiple specialized components collaborate to solve complex tasks.

This project is part of my **Generative AI learning journey**, where I am moving from basic LLM usage to building **real-world AI systems and agents**.

---

## 🧠 Core Concept

The system is designed around multiple AI agents working together in a pipeline:

Search → Reader → Writer → Critic  

Each component performs a specific role and passes information forward, creating a structured and intelligent workflow.

---

## ⚙️ Pipeline Breakdown

### 🔍 Search Agent

- Uses Tavily API for real-time web search  
- Retrieves relevant and up-to-date information  
- Outputs summaries along with source links  

---

### 📄 Reader Agent

- Selects the most relevant sources  
- Extracts content using web scraping  
- Produces detailed and focused insights  

---

### ✍️ Writer Chain

- Combines all collected information  
- Generates a structured and readable report  
- Outputs results in Markdown format  

---

### 🧐 Critic Chain

- Reviews the generated report  
- Evaluates:
  - Clarity  
  - Depth  
  - Accuracy  
  - Structure  

---

## 🤖 System Workflow

1. User provides a research query  
2. Search agent gathers relevant information  
3. Reader agent extracts key insights  
4. Writer generates a structured report  
5. Critic evaluates and provides feedback  
6. Final output is presented to the user  

---

## 🚀 Features

- Multi-agent AI workflow  
- Real-time web search and scraping  
- Structured report generation  
- Automated critique and feedback  
- Interactive interface using Streamlit  

---

## 🛠️ Tech Stack

- **LangChain (LCEL)** → Agent orchestration  
- **OpenAI / LLMs** → Reasoning and generation  
- **Tavily API** → Web search  
- **BeautifulSoup** → Content extraction  
- **Streamlit** → User interface  

---

## 📈 Observations

- Multi-agent systems improve output quality compared to single LLM calls  
- Tool integration enables real-world data access  
- Separating tasks into agents makes the system modular and scalable  
- Critic feedback helps improve reliability of generated content  

---

## 💡 Key Learnings

- How to design and build **multi-agent AI systems**  
- Using **LangChain Expression Language (LCEL)** for pipelines  
- Integrating external tools like search and scraping  
- Managing information flow across multiple agents  
- Building structured and production-like AI workflows  

---

## 🚀 Why This Project Matters

This project helped me:
- Move beyond prompt-based systems to **agent-based architectures**  
- Understand how real-world AI assistants are built  
- Gain practical experience in combining multiple AI components  

It represents a step toward building **autonomous AI systems capable of complex reasoning and execution**.

---

## 🙏 Acknowledgment

Special thanks to **Akarsh Vyas (Sheryians AI School)** for providing a clear and practical foundation for building multi-agent AI systems.

---

## 📬 Contact

Let’s connect and build AI systems together 🚀

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/tanujkumai)  
✉️ **Email:** tanujkumai21@gmail.com