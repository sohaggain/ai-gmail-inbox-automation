# AI Gmail Inbox Automation

An AI-powered Gmail automation workflow built with **n8n** and **OpenAI** to intelligently manage incoming emails.

## 🚀 Features

- 📥 Automatically monitors incoming Gmail messages
- 🤖 AI-powered email classification
- 🏷️ Applies Gmail labels automatically
- ✉️ Generates intelligent email replies
- 📝 Creates draft responses for personal emails
- 💼 Forwards sales-related emails
- ✅ Marks non-essential emails as read
- 🗂️ Keeps your inbox organized automatically

## Email Categories

- Promotions
- Social
- Personal
- Sales
- Miscellaneous

## Tech Stack

- n8n
- OpenAI GPT
- Gmail API
- AI Automation
- Workflow Automation

## Workflow Overview

```text
Gmail Trigger
      │
      ▼
OpenAI Email Classification
      │
      ▼
Switch Node
├── Promotions → Add Label → Mark Read
├── Social → Add Label → Mark Read
├── Personal → AI Reply → Create Draft
├── Sales → Forward Email
└── Misc → Add Label → Mark Read
```

## Use Cases

- Business inbox automation
- AI email assistant
- Lead management
- Customer support
- Personal email organization
- Productivity automation

## Benefits

- Save time on repetitive email tasks
- Improve response speed
- Automatically organize your inbox
- Reduce manual work
- Increase productivity with AI

## Requirements

- n8n
- Gmail Account
- OpenAI API Key

## Installation

1. Clone the repository.
2. Import the workflow into n8n.
3. Connect your Gmail credentials.
4. Configure your OpenAI API key.
5. Activate the workflow.

## License

MIT License

---

**Developed by Sohag Gain**
