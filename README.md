# Personal AI Agent & Lab Exercises 🤖  

Welcome! This repo documents my journey into **Agentic AI** — from foundations to building my first **deployed personal AI Agent** on Hugging Face Spaces.  

The project not only serves as a **professional representative AI** (answering questions based on my résumé, LinkedIn, and portfolio while capturing leads and notifying me in real time), but also as a **learning lab** where I experiment with frameworks, tools, and techniques for building autonomous agents.  

---

## 📂 Repository Structure  

├── 1_foundations/ # Core concepts & first lab notebooks

├── 2_openai/ # Experiments with OpenAI function calling

├── 3_tools/ # Custom tools (lead capture, logging, etc.)

├── 4_notifications/ # Pushover integration

├── app.py # Main Gradio app

├── requirements.txt # Python dependencies

├── setup/ # Setup instructions for different OS

├── assets/ # Images & supporting files

├── guides/ # Notes & learnings from labs

└── README.md # You are here


---

## 🚀 Features  

- **Interactive Web Interface** → [Gradio + Hugging Face Spaces](https://huggingface.co/spaces)  
- **Context Ingestion** → Résumé, LinkedIn, and portfolio for grounded Q&A  
- **Custom Tools**  
  - `record_user_details` → captures names, emails, and notes  
  - `record_unknown_question` → logs unanswered queries for follow-up  
- **Real-Time Notifications** → Pushover API for instant alerts  
- **Agentic System Design** → Goes beyond chat, acts as a professional representative & lead capture assistant  

---

## 🛠️ Tech Stack  

- [Gradio](https://gradio.app/) — Web UI  
- [Hugging Face Spaces](https://huggingface.co/spaces) — Hosting  
- [OpenAI API](https://platform.openai.com/) — LLM + function calling  
- [Pushover](https://pushover.net/) — Push notifications  
- Python — Core glue + tools  

---

## ⚙️ Setup & Installation  

Clone the repo:  
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


📚 Lab Exercises

This repo also tracks my hands-on labs as I learn agentic frameworks:

Lab 1: Foundations → Context ingestion, basic Q&A agent

Lab 2: OpenAI Function Calling → Connecting LLM to tools

Lab 3: Custom Tools → Lead capture + unanswered question logging

Lab 4: Notifications → Real-time push alerts with Pushover

(More labs will be added as I continue my learning journey 🚀)

🙏 Acknowledgements

Special thanks to Ed Donner for guidance on agentic frameworks and tools.

Inspired by the Agentic AI community for pushing boundaries on what’s possible.

🌟 Demo

👉 Live Agent: [(https://lnkd.in/eg3Vn9-x)]
