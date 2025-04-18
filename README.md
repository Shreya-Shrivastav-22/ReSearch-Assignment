# ReSearch Framework

A project implementation of the ReSearch framework, integrating search and reasoning with reinforcement learning for large language models.

# ReSearch: Integrating Search and Reasoning with Reinforcement Learning

ReSearch is a framework designed to integrate external search capabilities with reasoning mechanisms to enhance the performance of large language models. This project implements a basic simulation of the ReSearch paper:  
**"ReSearch: Integrating Search and Reasoning with Reinforcement Learning for Large Language Models."**

---

## 🚀 Overview

ReSearch operates by connecting a search agent (responsible for retrieving relevant documents) and a reasoning agent (that interprets those documents to answer queries). Reinforcement learning guides the agent in selecting effective actions over time.

---

## 📌 Architecture

Below is the high-level architecture of the ReSearch framework:

![ReSearch Architecture](./report/research_diagram.png)

**Components:**
- **Main**: Entry point of the framework.
- **Search Module**: Simulates document retrieval based on a query.
- **Reasoning Module**: Synthesizes retrieved documents into a final answer.
- **Search Results**: Stores the intermediate retrieved data.
- **Final Answer**: The system’s response after reasoning.

---

## 📁 Repository Structure

```bash
ReSearch/
├── report/                 # PDF technical report
│   └── ReSearch_Report.pdf
├── presentation/           # PPT slides
│   └── ReSearch_Presentation.pptx
├── code/                   # Main codebase
│   ├── main.py
│   ├── search_module.py
│   ├── reasoning_module.py
│   └── utils.py
├── requirements.txt        # Required libraries
└── README.md               # This file


