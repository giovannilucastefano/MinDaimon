---
title: "Brain API Conversation: Agent-Powered Workflows"
created: 2025-06-12
modified: 2025-06-12
type: text
status: active
priority: high
eos_alignment:
  rocks:
    - Q3-Product-Development
  core_values:
    - Continuous-Innovation
    - Customer-Centric-Excellence
tags:
  - ai-agent
  - brain-api
  - automation
  - project
  - high-priority
---

# \n🚀 Brain API Conversation - Agent-Powered Flow

You want to build an AI-based workflow with the Brain API concept: it takes a prompt like:

""Create a client brief for a custom dashboard request.""

Let's break down what the diagram you shared means in practical terms:

## 1. Inputs (Left Column)
- Source of user input: Brain webapp, Telegram, Voice VIA VAPI, Mattermost, Email, etc.
- Send a question from user to Brain API.

## 2. Brain Logic Stack (Core Agent Architecture)

- **Learnings** - stores personalized insights.
If you ever answered or added a preference, this is where it sticks.

- **History** - records past interactions to keep context.
 ** Scoring Tool** - determines which tools are most relevant for a command or intent.

- **Retrieval Tools** - gets data from docs, APIs, chats, etc. (Eg., RAG-layer).
- **Action Tools** - calls STA, sends emails, creates docs, updates notes, leverages.

- **Answer** - the final response or confirmation.

## 3. Tool APIs (Right Column)
- Connected services: Notion, Trello, Trelloboard, LinkedIn, Email, GitHub issues, Schedulers.
- Pushes outputs to the defined destination using a mapper model: notes, tasks, emails.

- Can be modular and link-to-link to build a strategic graph of knowledge actions.

## 4. Real-World Agent Example
> You: "Send a follow-up email to the new lead from LinkedIn"

1- Input Via Brain Browser/Telegram -> transcribed
- Brain API creates context through "Hearings", "Scoring", "Actions", Issues..

- Gets lead info from LinkedIn agent.

- Calls email tool to draft.

- Confirms send action 🖂"

## Summary: What This Flow Enables
Now every tasking or ops team can have an AI assistant that understands context, makes decisions, and carres them out.
