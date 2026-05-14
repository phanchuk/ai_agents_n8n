# 🤖 Study Project — AI Competitor Monitoring Agent

An agentic AI workflow designed to automate competitor intelligence and explore different levels of AI autonomy using n8n and LLMs.

The project focuses on building an end-to-end workflow: from collecting competitor inputs and external signals to AI-powered research, synthesis, and automated report generation.

---

## 💡 Description & Goal

Competitive research is often repetitive, fragmented, and difficult to scale.

The goal of this project was to design a reusable AI system that:

- reduces manual research effort
- automates competitor monitoring
- summarizes market changes and signals
- explores single-agent and autonomous agent patterns
- evaluates tradeoffs between control, cost, and autonomy

---

## 💡 Key Features

- Dynamic competitor source via Google Sheets
- Automated web research using Perplexity API
- GPT-powered report generation
- Context compression for token optimization
- Markdown → HTML transformation
- Email delivery automation
- Experimentation with multiple autonomy levels:
  - Manual LLM workflow
  - Agentic workflow
  - Autonomous research agent

---

## 🛠 Tech Stack

- n8n (workflow orchestration)
- OpenAI GPT-5 (reasoning + synthesis)
- Perplexity API (search & retrieval)
- Google Sheets (competitor source)
- Gmail API (report delivery)
- JSON / Markdown processing

---

## ⚙️ System Architecture (High-Level)

### 1. Data Collection
- Competitor list maintained in Google Sheets
- Triggered manually or via scheduler

### 2. Research Pipeline
- AI retrieves recent information using Perplexity
- Responses parsed and compressed

### 3. Report Generation
- Context aggregation
- GPT synthesis
- Markdown → HTML conversion
- Automated email delivery

---

## 🧠 Product Thinking

- Focus on **signal over noise** by prioritizing meaningful updates
- Designed around **autonomy vs reliability** tradeoffs
- Optimized for **token efficiency** using compression and aggregation
- Uses a **human-in-the-loop approach** where AI supports rather than replaces decisions

---

## 📸 Screenshots

### Manual LLM Workflow
<img width="1441" height="608" alt="image" src="https://github.com/user-attachments/assets/c620e122-218e-4173-90b9-f79f3a9b607c" />


### Agentic Workflow
<img width="1878" height="850" alt="image" src="https://github.com/user-attachments/assets/31e99a42-b4a5-4953-b56a-36435eec0f42" />


### Autonomous Workflow
<img width="1858" height="933" alt="image" src="https://github.com/user-attachments/assets/79ca4f61-b894-4911-a8af-5f3bd50409dd" />


---

## 📌 Notes

This project focuses on practical implementation of AI agents and workflow orchestration from a Product Manager perspective. The emphasis is on workflow design, operational tradeoffs, and experimentation with different levels of AI autonomy rather than production-scale implementation.
