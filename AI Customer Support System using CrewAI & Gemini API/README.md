# 🤖 AI Customer Support System using CrewAI & Gemini API

An **LLM-powered multi-agent customer support system** built with [CrewAI](https://docs.crewai.com/), [Google Gemini API](https://ai.google.dev/), and integrated web tools.  
This project simulates a **real-world AI-driven customer support workflow**, where multiple specialized AI agents collaborate to **classify, research, and respond** to customer queries.

---

## 🚀 Project Overview

This application creates a **multi-agent AI crew** to handle customer support requests end-to-end:

1. **Classifies** the query type, urgency, and required expertise  
2. **Researches & solves** the technical issue using a knowledge base + web search  
3. **Generates** a friendly, empathetic, and professional customer-ready response  

Agents are **role-specialized** and work **sequentially** to ensure accuracy, relevance, and empathy in responses.

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **[CrewAI](https://pypi.org/project/crewai/)** – Multi-agent orchestration
- **[Google Gemini API](https://ai.google.dev/)** – LLM reasoning and content generation
- **[Serper API](https://serper.dev/)** – Search tool for live information retrieval
- **[CrewAI Tools](https://github.com/joaomdmoura/crewai-tools)** – Web scraping, search integration
- **LangChain** – Model and tool wrappers
- **OpenCV / Diagrams** (optional) – For future expansion in visual troubleshooting

---

## 🎯 Key Features

- **Multi-Agent System**:  
  - *Support Query Classifier* – Categorizes query type & urgency  
  - *Technical Support Specialist* – Provides accurate troubleshooting steps  
  - *Customer Relations Manager* – Crafts a customer-friendly, empathetic response  

- **Prompt Engineering & LLM Orchestration**:  
  - Role-specific prompts for optimal performance  
  - Sequential task execution for reliability

- **Web Tools Integration**:  
  - `SerperDevTool` for web search  
  - `ScrapeWebsiteTool` for knowledge base extraction

- **Customizable for any product**:  
  Just update the `product_name` and `knowledge_base_url`

---



