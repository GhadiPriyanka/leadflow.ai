# 🚀 LeadFlow AI

AI-powered lead scoring, follow-up automation, and Telegram sales assistant built with n8n, Google Sheets, and LLMs.

## 📌 Project Overview

LeadFlow AI automates the lead management process for sales teams.

The system analyzes incoming leads using AI, assigns a lead score and priority, recommends the next action, updates Google Sheets, and sends Telegram alerts for leads requiring follow-up.

Salespeople can also interact with the system through Telegram commands.

## 🏗️ Architecture

Google Sheets
        ↓
n8n Scheduled Workflow
        ↓
AI Lead Analysis Agent
        ↓
Lead Score + Priority + Intent
        ↓
Google Sheets Update
        ↓
Telegram Follow-up Alert

Salesperson
        ↓
Telegram Commands
        ↓
n8n Salesperson Command Workflow
        ↓
Lead Information / Top Leads / Follow-up

## ✨ Key Features

- AI-powered lead scoring
- Lead priority classification
- Customer intent analysis
- Buying-stage identification
- Follow-up recommendation
- Automated Google Sheets updates
- Telegram notifications
- Top 3 priority lead identification
- Lead details lookup
- Follow-up lead management
- Scheduled lead processing

## 🤖 Telegram Commands

### `/top3`

Returns the top 3 highest-scoring leads.

### `/details L004`

Returns detailed information and AI recommendations for a specific lead.

### `/followup`

Returns leads requiring follow-up.

## 🛠️ Technologies Used

- n8n
- Google Sheets
- Telegram Bot
- Large Language Models (LLMs)
- AI Agents
- Workflow Automation
- JavaScript
- JSON

## 🔄 Workflow

1. Lead data is stored in Google Sheets.
2. n8n periodically reads the lead records.
3. AI analyzes each lead.
4. The system generates score, priority, intent, and recommendation.
5. Results are updated in Google Sheets.
6. Leads requiring follow-up trigger Telegram notifications.
7. Salespeople can query lead information through Telegram.

## 🎯 Business Value

LeadFlow AI helps sales teams:

- Identify high-priority leads faster
- Reduce manual lead analysis
- Avoid missed follow-ups
- Standardize lead qualification
- Improve salesperson productivity
- Automate repetitive sales operations

## 🔐 Security

This repository contains only sample/demo data.

API keys, Telegram tokens, Google credentials, and confidential customer information are not included.

## 👩‍💻 Author

Priyanka Ghadi
