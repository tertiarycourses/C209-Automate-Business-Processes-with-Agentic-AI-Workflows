# Automate Business Processes with Agentic AI Workflows

**Course Code:** C209
**Duration:** 2 days · 15 instructional hours (9:30am–5:30pm, 7.5 hours/day)
**Conducted by:** Tertiary Infotech Academy Pte Ltd (UEN 201200696W)

**Register:** [tertiarycourses.com.sg](https://www.tertiarycourses.com.sg/automate-business-processes-with-agentic-ai-workflows.html)

Learners build five working automations in [n8n](https://n8n.io): a form-triggered workflow, a
webhook-triggered AI agent behind a real website, an agentic chatbot bound by compliance rules, a
human-in-the-loop approval chain, and a Retrieval-Augmented Generation chatbot grounded in an
organisation's own documents.

## Learning outcomes

- **LO1** — Explain what n8n and AI agents are, and build automated workflows using triggers and actions.
- **LO2** — Implement AI agent applications that are triggered by webhooks and integrated with business systems.
- **LO3** — Design agentic chatbot workflows that operate safely within business and regulatory constraints.
- **LO4** — Apply human-in-the-loop approval so that sensitive actions are authorised by a person.
- **LO5** — Deploy Retrieval-Augmented Generation (RAG) to ground an agent in an organisation's own documents.

## Course structure

| Topic | Content | Labs |
|---|---|---|
| 1 — Overview of n8n and AI Agents | What n8n is, triggers and actions, what an AI agent is, webhooks | Lab 1, Lab 2 |
| 2 — Agentic Chatbot and Human in the Loop | Agentic workflows, safe chatbot design, approval gates, accountability | Lab 3, Lab 4 |
| 3 — Retrieval-Augmented Generation (RAG) | Tokenization, embeddings, vector stores, chunking, grounding | Lab 5 |

## Labs

| # | Lab | Scenario | Folder |
|---|---|---|---|
| 1 | n8n Trigger and Action | Event flyer with a QR code — Form Trigger → Gmail | [`labs/lab1-trigger-actions/`](labs/lab1-trigger-actions/) |
| 2 | Webhook and AI Agent | Marina Trust Bank onboarding — website → webhook → agent with tools | [`labs/lab2-webhook-agent/`](labs/lab2-webhook-agent/) |
| 3 | Chatbot Webhook | Investment advisor — an agentic chatbot that refuses to give advice | [`labs/lab3-chatbot-webhook/`](labs/lab3-chatbot-webhook/) |
| 4 | Human in the Loop | Meridian Asset Management — the agent drafts, a human approves | [`labs/lab4-human-in-the-loop/`](labs/lab4-human-in-the-loop/) |
| 5 | RAG Customer Care Chatbot | Cook & Bake Academy — 20 brochures in a vector store | [`labs/lab5-rag/`](labs/lab5-rag/) |

## Schedule

Each day runs 9:30am – 5:30pm: 7.5 instructional hours, with a 30-minute lunch break excluded
from instructional time.

| Day | Content |
|---|---|
| 1 | Foundation · Topic 1 (n8n, AI agents, webhooks) · Lab 1 · Lab 2 |
| 2 | Topic 2 (agentic chatbots, human in the loop) · Lab 3 · Lab 4 · Topic 3 (RAG) · Lab 5 |

## Courseware

Current version **v2.0** — all artifacts live in [`courseware/`](courseware/).

| Artifact | File |
|---|---|
| Trainer slide deck | `courseware/Automate Business Processes with Agentic AI Workflows (C209)-v2.0.pptx` (+ `.pdf`) |
| Lesson Plan | `courseware/LP-Automate Business Processes with Agentic AI Workflows (C209).docx` (+ `.pdf`) |
| Learner Guide | `courseware/LG-Automate Business Processes with Agentic AI Workflows (C209).docx` (+ `.pdf`) |
| Learner Guide (Markdown mirror) | `LG-Automate Business Processes with Agentic AI Workflows (C209).md` |

## What goes on a slide, and what goes in the Learner Guide

The deck follows the house reference format: a kicker, a bold title, a one-line intro, then **one**
visual structure — a chevron flow strip, outlined concept cards, a two-panel comparison, or a data
table — closed by a takeaway band.

**The click-by-click lab steps are deliberately not on the slides.** Each lab gets a single visual
slide (workflow chevron + a screenshot of the real n8n canvas + a LAB band); the full steps live only
in the Learner Guide. Keep it that way when editing — a step-by-step slide belongs in the LG.

## Repository layout

```
courseware/          the current build — deck, LP, LG (+ PDFs)
courseware/assets/   slide diagrams, n8n UI screenshots, and the rendered canvas-lab*.png
labs/                the five hands-on labs — workflow JSON, websites and sample data
```

---

© 2026 Tertiary Infotech Academy Pte Ltd. All rights reserved. · [www.tertiarycourses.com.sg](https://www.tertiarycourses.com.sg)
