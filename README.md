# 🚀 AI Sales Agent & Lead Qualification System

An end-to-end AI-powered Sales Automation Workflow built with **n8n**, **Groq AI**, **Google Sheets**, **Gmail**, and **Google Calendar**.

This workflow automatically captures leads from a web form, analyzes them using AI, qualifies each lead, assigns a lead score, routes leads based on priority, stores data in Google Sheets, books meetings in Google Calendar, and sends automated emails to both customers and the sales team.

The goal of this project is to reduce manual work, improve response times, and help businesses convert more leads through intelligent automation.

---

# 📌 Workflow Overview

```text
Customer Form
      │
      ▼
Webhook
      │
      ▼
Prepare Lead Data
      │
      ▼
AI Sales Agent (Groq LLM)
      │
      ├──────────────► Customer Confirmation Email
      │
      ├──────────────► Google Sheets CRM
      │
      ▼
Lead Classification (Switch)

Hot Lead
      │
      ▼
Google Calendar Event
      │
      ▼
Admin Email Notification
      │
      ▼
Wait
      │
      ▼
Follow-up Email

Warm Lead
      │
      ▼
Wait
      │
      ▼
Follow-up Email

Cold Lead
      │
      ▼
Stored in CRM
```

---

# ✨ Features

- 🤖 AI-powered Lead Qualification
- 📊 Automatic Lead Scoring (0–100)
- 🔥 Hot / Warm / Cold Lead Classification
- ⚡ Intelligent Lead Routing
- 📧 Customer Confirmation Emails
- 📬 Admin Notification Emails
- 📅 Automatic Google Calendar Event Creation
- ⏳ Automated Follow-up Emails
- 📈 CRM Logging with Google Sheets
- 🧠 Structured JSON Output using AI
- 🌐 Webhook-Based Form Submission
- 🔄 End-to-End Workflow Automation

---

# 🛠 Tech Stack

- n8n
- Groq AI (Llama Model)
- Gmail API
- Google Sheets API
- Google Calendar API
- Webhooks
- JSON
- HTML Forms

---

# 📊 AI Processing

The AI Agent performs:

- Business Understanding
- Lead Qualification
- Lead Scoring
- Priority Assignment
- Lead Classification
- Professional Summary Generation
- Recommended Sales Action

Example Output:

```json
{
  "lead_score": 92,
  "lead_status": "Hot Lead",
  "priority": "High",
  "summary": "Qualified business interested in AI automation.",
  "recommended_action": "Schedule a demo within 24 hours."
}
```
<img width="667" height="301" alt="Screenshot 2026-07-14 031219" src="https://github.com/user-attachments/assets/0b656927-81f5-446b-b33e-6765cfa5fabe" />

---

# 📧 Automated Actions

## Customer

- Confirmation Email
- Follow-up Email

## Sales Team

- Instant Admin Notification
- AI Lead Summary
- Google Calendar Meeting

## CRM

- Save Lead
- Update Existing Lead
- Track Lead Status

---

# 📅 Google Calendar Automation

For qualified leads the workflow automatically:

- Creates a meeting
- Invites attendees
- Adds lead information
- Sends calendar invitation
- Supports Google Meet integration

---

# 📈 Business Benefits

- Save Manual Work
- Respond Faster
- Never Miss a Lead
- AI-Based Qualification
- Automated Follow-ups
- Centralized CRM
- Automatic Meeting Scheduling
- Higher Conversion Rate

---

# 🏢 Ideal Use Cases

This workflow is suitable for:

- SaaS Companies
- Marketing Agencies
- AI Automation Agencies
- Real Estate
- Clinics & Healthcare
- Education & Coaching
- Travel Agencies
- Consulting Firms
- E-commerce
- Customer Support Teams
- Sales Teams
- Small Businesses

---

# 🚀 Future Improvements

- WhatsApp API Integration
- Slack Notifications
- HubSpot CRM
- Salesforce CRM
- Airtable
- Twilio SMS
- OpenAI Support
- Multi-Agent Architecture
- RAG Knowledge Base
- Voice AI Integration

---

# 👨‍💻 Author

**Afaq Khan**

AI Agent Engineer | AI Automation Specialist

Building intelligent workflow automations using AI, n8n, and modern automation tools.
