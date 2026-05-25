# 🎙️ Jira AI Voice Assistant

An AI assistant built with n8n, MCP (Model Context Protocol), ElevenLabs voice AI, and workflow automation to execute Jira actions through natural language interactions. The project explores how Product Managers can orchestrate AI agents that interact with Jira and productivity tools using voice interfaces, memory, and connected workflows.

---

## 💡 Description & Goal

Product Managers spend significant time navigating Jira, retrieving project information, coordinating actions, and handling repetitive operational work.

The goal of this project was to explore how AI agents can evolve from simple chat interfaces into workflow assistants capable of understanding requests, planning actions, interacting with Jira tools, and executing tasks through natural conversation.

This case study demonstrates practical implementation of an AI-powered Jira assistant using MCP servers, AI agents, and workflow orchestration.

---

## 💡 Key Features

- AI agent connected to Jira via MCP
- ElevenLabs conversational voice interface
- Voice and webhook-triggered interactions
- Dynamic Jira tool discovery
- AI-driven action planning before execution
- Context-aware memory support
- Gmail integration for communication workflows
- Google Sheets contact retrieval
- Background workflow automation with n8n
- MCP-based tool execution
- Local and cloud deployment support

---

## 🛠 Tech Stack

- n8n Community Edition
- OpenAI GPT-4o-mini
- ElevenLabs Conversational AI
- MCP (Model Context Protocol)
- Jira MCP Server
- Google Sheets API
- Gmail API
- Webhooks
- Memory Buffer
- Elestio (cloud hosting)

---

## ⚙️ System Architecture (High-Level)

### 1. Infrastructure Layer

- Custom n8n deployment using Docker
- Community MCP node installation
- Cloud deployment via Elestio
- Support for Node.js and UV MCP servers

---

### 2. Voice Interface Layer

- ElevenLabs conversational AI receives user requests
- Custom tool integration triggers n8n webhook
- Voice requests initiate workflow execution

---

### 3. AI Agent Layer

- OpenAI model interprets user goals
- Agent plans actions before execution
- Memory tracks workflow context and progress

Prompt strategy:

1. Discover available Jira tools
2. Select relevant tool
3. Execute action
4. Avoid assumptions

---

### 4. Tool Layer

Connected systems:

- List Jira Tools
- Execute Jira Tools
- Contacts (Google Sheets)
- Gmail

MCP acts as an abstraction layer between AI agents and external tools.

---

### 5. Response Layer

- Workflow processes output
- Results returned through webhook
- Voice interface communicates results back to the user

---

## 🧠 Product Thinking

- Reduces repetitive Jira operations
- Demonstrates practical AI workflow orchestration
- Uses tool discovery instead of hardcoded assumptions
- Applies agent planning before execution
- Explores AI as an operational teammate rather than a chatbot
- Demonstrates practical AI applications for Product Managers

---

## 🔄 Example Workflow

User:

*"Show me high-priority Jira tickets and send an update email to stakeholders."*

Workflow:

1. User speaks through ElevenLabs voice interface
2. Voice request triggers n8n webhook
3. AI agent analyzes request
4. MCP retrieves available Jira tools
5. Agent executes Jira actions
6. Contacts are retrieved from Google Sheets
7. Gmail sends communication
8. Response returns to voice interface

---

## 📸 Screenshots

### Voice Agent + n8n Workflow
<img width="1908" height="998" alt="AI voice count issues" src="https://github.com/user-attachments/assets/bda1e2f6-a86b-4c83-8751-11fb16c4066d" />

### Voice Agent, n8n Workflow, Jira MCP, Gmail Integration Overview
<img width="1896" height="1016" alt="AI voice send email update" src="https://github.com/user-attachments/assets/dd9e0b0e-6067-4ffa-9366-cd2f33b681cf" />

---

## 📌 Notes

This project focuses on practical GenAI learning for Product Managers and explores AI orchestration, voice interfaces, MCP integrations, and agent-based workflow design rather than production-scale implementation.
