# Automate Business Processes with Agentic AI Workflows

Build five working business automations in [n8n](https://n8n.io) — from a form-triggered workflow
to an AI agent behind a real website, a compliance-bound chatbot, a human-in-the-loop approval chain
and a RAG chatbot grounded in an organisation's own documents.

| Course detail | Information |
|---|---|
| Course code | `C209` |
| Programme | Non-WSQ commercial short course |
| Duration | 2 days · 15 instructional hours (9:30am – 5:30pm, 7.5 hours/day) |
| Registration | [View course details and register](https://www.tertiarycourses.com.sg/automate-business-processes-with-agentic-ai-workflows.html) |
| Conducted by | Tertiary Infotech Academy Pte Ltd (UEN 201200696W) |

## About the course

Agentic AI moves automation from rigid, hand-built rules to agents that can plan, call tools and
act — inside a workflow you still control. This course teaches the **workflow-first** approach:
the n8n workflow owns the path, and AI Agent nodes sit inside it with the tools, instructions,
memory and guardrails that keep them safe. Every concept is applied immediately in a hands-on lab,
and each lab keeps the agent while changing one thing — the front door, the tools, the oversight or
the knowledge.

## Learning outcomes

- **LO1** — Explain what n8n and AI agents are, and build automated workflows using triggers and actions.
- **LO2** — Implement AI agent applications that are triggered by webhooks and integrated with business systems.
- **LO3** — Design agentic chatbot workflows that operate safely within business and regulatory constraints.
- **LO4** — Apply human-in-the-loop approval so that sensitive actions are authorised by a person.
- **LO5** — Deploy Retrieval-Augmented Generation (RAG) to ground an agent in an organisation's own documents.

## Topics covered

| Topic | Content | Labs |
|---|---|---|
| 1 — Overview of n8n and AI Agents | A brief history of AI 2023–2026, generative vs agentic AI, workflow first vs agent first, AI-assisted workflow creation with n8n Assistant, AI security, n8n fundamentals (triggers, data-processing nodes, expressions, executions, credentials), AI agent building blocks (model, tools and MCP, instructions, memory, structured output) and webhooks | Lab 1, Lab 2 |
| 2 — Agentic Chatbot and Human in the Loop | Rule-based vs agentic workflows, designing a safe agentic chatbot, a Telegram HR chatbot demo, human in/on/out of the loop, approval gates and guardrails | Lab 3, Lab 4 |
| 3 — Retrieval-Augmented Generation (RAG) | Why retrieval, the RAG pipeline, chunking, tokenization and embeddings, vector stores, grounding against hallucination | Lab 5 |

## Labs

Each lab folder ships a ready-made n8n workflow (`.json`) to import and compare against, plus any
website and sample data the lab needs. The click-by-click steps are in the Learner Guide.

| # | Lab | Scenario | Folder |
|---|---|---|---|
| 1 | n8n Trigger and Action | Event flyer with a QR code — n8n Form → Gmail | [`labs/lab1-trigger-actions/`](labs/lab1-trigger-actions/) |
| 2 | Webhook and AI Agent | Marina Trust Bank onboarding — website → webhook → agent with tools | [`labs/lab2-webhook-agent/`](labs/lab2-webhook-agent/) |
| 3 | Chatbot Webhook | Investment advisor — an agentic chatbot that refuses to give advice (plus the Telegram HR chatbot demo) | [`labs/lab3-chatbot-webhook/`](labs/lab3-chatbot-webhook/) |
| 4 | Human in the Loop | Meridian Asset Management — the agent drafts, a relationship manager approves | [`labs/lab4-human-in-the-loop/`](labs/lab4-human-in-the-loop/) |
| 5 | RAG Customer Care Chatbot | Cook & Bake Academy — 20 brochures ingested into a vector store | [`labs/lab5-rag/`](labs/lab5-rag/) |

## Schedule

Each day runs 9:30am – 5:30pm: 7.5 instructional hours, with a 30-minute lunch break excluded
from instructional time.

| Day | Content |
|---|---|
| 1 | Topic 1 — why agentic AI, n8n fundamentals · Lab 1 · AI agent building blocks and webhooks · Lab 2 |
| 2 | Topic 2 — agentic chatbots · Lab 3 · human in the loop and guardrails · Lab 4 · Topic 3 — RAG · Lab 5 · course recap |

## Courseware

Current version **v2.5** — all artifacts live in [`courseware/`](courseware/).

| Artifact | Files |
|---|---|
| Slide deck | [PPTX](<courseware/Automate Business Processes with Agentic AI Workflows (C209)-v2.5.pptx>) · [PDF](<courseware/Automate Business Processes with Agentic AI Workflows (C209)-v2.5.pdf>) |
| Lesson Plan | [DOCX](<courseware/LP-Automate Business Processes with Agentic AI Workflows (C209).docx>) · [PDF](<courseware/LP-Automate Business Processes with Agentic AI Workflows (C209).pdf>) |
| Learner Guide | [DOCX](<courseware/LG-Automate Business Processes with Agentic AI Workflows (C209).docx>) · [PDF](<courseware/LG-Automate Business Processes with Agentic AI Workflows (C209).pdf>) · [Markdown](<LG-Automate Business Processes with Agentic AI Workflows (C209).md>) |

## Repository layout

```
courseware/          the current build — deck, Lesson Plan, Learner Guide (+ PDFs)
courseware/assets/   slide diagrams, n8n canvas screenshots and lab application screenshots
labs/                the five hands-on labs — n8n workflow JSON, websites and sample data
```

Only the current courseware version is published here. Superseded versions are kept out of the
repository.

---

© 2026 Tertiary Infotech Academy Pte Ltd. All rights reserved. · [www.tertiarycourses.com.sg](https://www.tertiarycourses.com.sg)
