# LeadForge AI 🚀

An AI-powered lead generation automation built using **n8n**, **Google Gemini**, **Apify**, **Gmail**, and **Google Sheets**.

LeadForge automatically discovers businesses, extracts contact information, analyzes companies using AI, generates personalized cold emails, qualifies leads, and creates Gmail drafts ready to send.

---

## Demo

> Workflow GIF

(Add GIF here)

---

## Features

- Business Discovery using Google Maps (Apify)
- Website Crawling
- AI-powered Information Extraction
- Business Analysis using Gemini
- Personalized Cold Email Generation
- Lead Qualification
- Gmail Draft Creation
- Google Sheets Integration
- Modular n8n Workflow
- Structured JSON Outputs

---

## Workflow

```text
Trigger

↓

Google Maps Search (Apify)

↓

Visit Business Website

↓

Extract Website Content

↓

AI Information Extraction

↓

Business Analysis

↓

Cold Email Generation

↓

Lead Qualification

↓

Google Sheets

↓

Gmail Draft
```

---

## Tech Stack

- n8n
- Google Gemini
- Apify
- Gmail API
- Google Sheets API
- JavaScript
- JSON

---

## Folder Structure

```text
workflow/
assets/
prompts/
docs/
screenshots/
```

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/yourusername/leadforge-ai-n8n.git
```

### Import Workflow

1. Open n8n
2. Import

```
workflow/LeadForge-AI.json
```

3. Configure Credentials

- Apify API
- Gemini API
- Gmail OAuth
- Google Sheets

---

## Environment

Required credentials:

```
Apify API

Gemini API

Google OAuth

Gmail OAuth

Google Sheets OAuth
```

---

## Output

The workflow automatically generates:

- Company Name
- Website
- Contact Email
- Personalized Subject Line
- Personalized Cold Email
- LinkedIn Message
- Cold Call Opening
- Lead Priority
- Gmail Draft

---

## Example Flow

```
Business

↓

Website Crawl

↓

AI Analysis

↓

Personalized Outreach

↓

Qualification

↓

Google Sheets

↓

Gmail Draft
```

---

## Screenshots

(Add screenshots here)

- Workflow
- Google Sheets
- Gmail Draft
- Generated Email

---

## Future Improvements

- CRM Integration (HubSpot)
- Multi-language Outreach
- LinkedIn Automation
- Follow-up Email Sequences
- Slack Notifications
- Automatic Email Sending
- Analytics Dashboard
- RAG-based Company Research

---

## Contributing

Feel free to fork this repository and improve the workflow.

---

## License

MIT License