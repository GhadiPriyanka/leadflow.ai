## Workflows

### 1. LeadFlow AI — Master Orchestrator
Main conversational AI entry point that receives salesperson requests through Telegram, processes them using an AI Agent, and returns the response through Telegram.

### 2. LeadFlow AI — Lead Data
Scheduled lead-processing workflow that reads leads from Google Sheets, sends them for AI analysis, updates lead scores and recommendations, and triggers follow-up notifications.

### 3. LeadFlow AI — Lead Analysis Agent
AI analysis workflow responsible for analyzing individual leads and generating lead score, priority, intent, buying stage, urgency, and recommended action.

### 4. LeadFlow AI — Salesperson Command
Telegram command workflow that allows salespeople to retrieve lead information using commands such as `/top3`, `/details`, and `/followup`.

> Credentials, API keys, Telegram bot tokens, and other secrets are not included.
