# AI-Powered Email Triage Workflow (n8n)

An automated n8n workflow that fetches unread emails, classifies them using Gemini AI, routes notifications, and manages inbox actions.

## 🛠️ Tech Stack & Integration
- **Workflow Automation:** n8n
- **AI Model:** Google Gemini AI
- **Triggers & Actions:** Gmail API
- **Notifications:** Discord Webhooks & Telegram Bot API

## 📋 Features
- **Gmail Integration:** Fetches incoming unread emails automatically.
- **AI Classification:** Analyzes email content using Gemini to classify emails as `IMPORTANT` or `NOT_IMPORTANT`.
- **Alert System:** 
  - Routes `IMPORTANT` emails to Telegram and Discord channels.
  - Automatically moves `NOT_IMPORTANT` emails to Trash and logs notifications.
