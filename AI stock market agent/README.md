# 📈 AI Stock Market Analysis Agent using CrewAI & Gemini API

An **LLM-powered multi-agent financial analysis system** built with [CrewAI](https://docs.crewai.com/) and [Google Gemini API](https://ai.google.dev/).  
This project simulates a **real-world investment research assistant** that analyzes both **individual stock performance** and **broader market trends** to provide actionable investment insights.

---

## 🚀 Project Overview

This application creates a **multi-agent crew** to perform:
1. **Stock-specific performance analysis** – fundamentals, trends, risks
2. **Broader market & sector trend analysis** – macroeconomic factors, competition, catalysts

Agents work **sequentially** to ensure that the final output combines **micro-level stock insights** with **macro-level market context**.

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **[CrewAI](https://pypi.org/project/crewai/)** – Multi-agent orchestration
- **[Google Gemini API](https://ai.google.dev/)** – LLM reasoning & text generation
- **[Serper API](https://serper.dev/)** – Live market news & data search
- **LangChain** – Model & tool integrations

---

## 🎯 Key Features

- **Two Specialized AI Agents**:
  - *Financial Analyst* – Focused on stock-specific metrics and performance  
  - *Market Trend Analyst* – Examines sector trends, macroeconomics, and competition

- **Prompt-Driven Role Specialization**:
  - Each agent is designed with a unique **goal** and **backstory** to improve LLM performance

- **Live Data Integration**:
  - Uses Serper API to fetch and integrate recent market information

- **Actionable Insights**:
  - Produces investment-oriented recommendations, not just raw analysis

---
