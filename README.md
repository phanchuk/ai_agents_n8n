# 🤖 AI Agents with n8n, OpenAI and Claude

A collection of hands-on AI workflow projects focused on exploring practical applications of GenAI, AI agents, MCP integrations, workflow orchestration, and automation from a Product Manager perspective.

This repository documents experiments with AI systems that move beyond prompting into connected tools, agent workflows, and operational automation.

The goal is not production-scale implementation, but developing intuition around emerging AI capabilities and understanding how Product Managers can leverage them to solve real workflow problems.

---

## 🎯 Learning Focus

Across these projects I explored:

- AI workflow orchestration using n8n
- Agentic design patterns
- MCP (Model Context Protocol) integrations
- Voice interfaces and conversational agents
- Human + AI collaboration patterns
- Automation of repetitive PM workflows
- Tradeoffs between autonomy, reliability, and control
- Practical GenAI applications beyond chat interfaces

---

# 📂 Projects

## 1. 🎙️ Jira AI Voice Assistant

An AI-powered voice assistant capable of interacting with Jira and productivity tools through natural language.

Built with n8n, MCP, ElevenLabs, OpenAI, Gmail integrations, and cloud deployment via Elestio.

Key areas explored:

- Conversational AI workflows
- Voice-triggered automation
- Jira MCP integrations
- AI agent planning + memory
- Tool orchestration through webhooks

**Tech stack:**  
n8n · OpenAI · ElevenLabs · MCP · Jira · Gmail · Google Sheets · Elestio

📁 [See project README for architecture and implementation details](.ai_voice_agent/README.md)

<img width="1896" height="1016" alt="AI voice send email update" src="https://github.com/user-attachments/assets/dd9e0b0e-6067-4ffa-9366-cd2f33b681cf" />

---

## 2. 🤖 AI Competitor Monitoring Agent

An agentic workflow designed to automate competitive intelligence and experiment with different levels of AI autonomy.

The system collects inputs, performs research, synthesizes findings, and generates automated reports.

Key areas explored:

- Autonomous research agents
- Multi-step AI workflows
- Report generation
- Signal prioritization
- Autonomy vs reliability tradeoffs

**Tech stack:**  
n8n · OpenAI · Perplexity API · Google Sheets · Gmail

📁 [See project README for workflow and architecture details](./competitor_research_agents/readme.md)

<img width="1858" height="933" alt="image" src="https://github.com/user-attachments/assets/79ca4f61-b894-4911-a8af-5f3bd50409dd" />

---

## 3. 🎨 AI-Powered Figma → Jira Automation with MCP

A workflow demonstrating how AI can transform Figma designs directly into Jira epics and stories.

Built around Claude Desktop and MCP integrations to automate design-to-delivery workflows.

Key areas explored:

- MCP integrations
- AI-assisted product operations
- Design → execution automation
- Prompt-driven workflows
- AI workflow augmentation

**Tech stack:**  
Claude Desktop · MCP · Jira Cloud · Figma

📁 [See project README for architecture and implementation details](./figma_jira_mcp_claude/readme.md)

<img width="1773" height="974" alt="2026-05-19_19h03_50 - 1" src="https://github.com/user-attachments/assets/5928be55-8eae-421f-8405-1051a37fefac" />

---

## 🧠 Product Perspective

These projects were built as practical exercises to strengthen AI Product Management capabilities:

- understanding AI system behavior
- designing workflows instead of isolated prompts
- experimenting with emerging tooling ecosystems
- learning agent architectures through implementation
- building stronger intuition around AI opportunities and limitations

---

## 📌 Notes

Most implementations are inspired by case studies and tutorials from Product Compass and adapted as hands-on exercises.

The focus is learning by building: understanding systems, experimenting with workflows, and developing practical AI product intuition.
