# 🧠 Multi-Agent AI System for Medical Data (From Scratch - No Framework)

This project implements a **Multi-Agent AI System built from scratch using Python**, designed to interact with **medical data** — capable of performing tasks like summarization, refinement, validation, and even generation of new insights. Inspired by the educational project: [Multi-Agents-System-from-Scratch](https://github.com/AIAnytime/Multi-Agents-System-from-Scratch) and based on the [YouTube tutorial](https://www.youtube.com/watch?v=f3KHI1dpc1Q) on building multi-agent systems using basic Python, this implementation shows the power of AI agents without relying on heavy frameworks like LangChain, CrewAI, or AutoGen.

---

## 🚀 Features

- 📋 **Summarization Agent** – Extracts key information from medical records and documents.
- 🧹 **Refiner Agent** – Cleans, formats, and structures unorganized data.
- ✅ **Validation Agent** – Ensures logical and medical accuracy by reviewing outputs from other agents.
- 📝 **Generation Agent** – Simulates new medical content (e.g., doctor notes, reports).
- ⚙️ **Agent Orchestration** – Handled manually using plain Python classes; **no frameworks** used.
- 🧾 **Logging System** – Track all agent interactions and outputs for traceability.
- 🔒 **OpenAI Integration** – Uses OpenAI's GPT capabilities with structured prompt control.

---

Agents communicate sequentially using shared memory and structured Python calls. Each task is validated before proceeding to ensure integrity.

---

## 🗂️ Project Structure

project/
├── agents/
│ ├── agent_base.py
│ ├── refiner_agent.py
│ ├── summarize_tool.py
│ ├── summary_validator_agent.py
│ ├── sanitize_data_tool.py
│ ├── sanitize_data_validator_agent.py
│ ├── write_article_tool.py
│ ├── write_article_validator_agent.py
│ └── validator_agent.py
├── utils/
│ ├── app.py
│ └── logger.py
├── logs/
├── .env
├── requirements.txt
└── README.md

