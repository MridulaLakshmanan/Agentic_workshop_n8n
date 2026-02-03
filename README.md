
# 🤖 Agentic AI Workflow Automation using n8n

An end-to-end collection of **Agentic AI workflows built using n8n**, demonstrating how **Large Language Models (LLMs)** can be orchestrated to perform real-world automation tasks such as **resume screening, accounting analysis, and RAG-based chatbots**.

This project focuses on **agent-based reasoning**, **workflow orchestration**, and **secure AI automation**, going beyond simple prompt-based AI demos.

---

## 📌 Project Highlights

- Agent-based AI workflows using n8n
- Integration with OpenAI and Groq LLMs
- Retrieval-Augmented Generation (RAG)
- Resume screening capstone project
- Structured outputs (JSON / Excel)
- Security-first design (credentials excluded)

---

## 📁 Project Structure
Agentic_workshop_n8n/
│
├── 1_basic_openai_agent.json
├── 2_Basic_Groq_Agent.json
├── 4_Accounting_agent.json
├── 5_RAG_Chatbot.json
├── 6_Capstone_Resume_screening.json
├── Agentic_RAG.json
├── My workflow.json
├── result_file.xlsx

---

## 🚀 Workflows Included

### 🔹 Basic OpenAI Agent
- Demonstrates a simple LLM-powered agent
- Handles prompt → reasoning → response flow

### 🔹 Basic Groq Agent
- Uses Groq LLM for fast inference
- Shows multi-provider flexibility

### 🔹 Accounting Agent
- AI assistant for accounting-related analysis
- Applies reasoning to domain-specific inputs

### 🔹 RAG Chatbot
- Implements retrieval-augmented generation
- Produces context-grounded responses

### 🔹 Agentic RAG Workflow
- Advanced RAG with agent-style decision logic
- Separates retrieval and reasoning steps

### 🔹 Capstone: Resume Screening Agent
- End-to-end resume evaluation system
- Generates structured screening results
- Sample output included (`result_file.xlsx`)

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation platform  
- **OpenAI / Groq** – Large Language Models  
- **Agentic AI** – Decision-driven AI flows  
- **RAG** – Retrieval-Augmented Generation  
- **Excel / JSON** – Structured outputs  

---

## 🔐 Credentials & Security

⚠️ **Credentials are not included**

- n8n does not export credentials with workflows
- API keys and secrets must be configured locally
- Environment variables are recommended
- Never commit credential files or `.n8n` directories

---

## 🎯 Why This Project Matters

This project demonstrates the ability to:
- Design **end-to-end AI automation systems**
- Orchestrate multi-step LLM workflows
- Apply AI to real-world business problems
- Follow security and best practices
- Build scalable, extensible AI pipelines

---

## 🧾 Resume-Ready Description

> **Agentic AI Workflow Automation using n8n**  
> Built multiple agent-based AI workflows using n8n, integrating OpenAI and Groq LLMs to automate resume screening, accounting analysis, and RAG-based chatbots. Designed end-to-end AI pipelines with structured outputs, secure credential handling, and decision-driven workflows.

---

## 🔄 How This Project Works (Workflow Explanation)

1. **Trigger**
   - Workflow starts via manual trigger or webhook

2. **Input Processing**
   - User input, documents, or data are received
   - Inputs are cleaned and structured inside n8n

3. **LLM Agent Execution**
   - An AI agent (OpenAI or Groq) processes the input
   - Agent performs reasoning and decides next actions

4. **Optional RAG Pipeline**
   - Relevant documents or context are retrieved
   - Retrieved data is injected into the LLM prompt

5. **Business Logic Handling**
   - Resume evaluation, accounting reasoning, or chatbot logic
   - Decisions are made based on agent output

6. **Output Generation**
   - Results are generated as text, JSON, or Excel files
   - Outputs can be stored, displayed, or forwarded

7. **End of Workflow**
   - Workflow completes with structured, actionable results

📌 This workflow-driven approach enables **scalable, reusable, and explainable AI automation**.

---

⭐ If you find this project useful, feel free to star the repository!
