# AI-Powered School Admission Enquiry Automation System

An intelligent school admission enquiry management system built using n8n, Google Gemini AI, Supabase, Gmail and Telegram. It automates admission enquiry processing, AI-based classification, parent acknowledgement emails and school notifications.

## 🚀 Project Overview

This project automates the school admission enquiry process by receiving enquiries, analyzing them using Google Gemini AI, storing enquiry records in Supabase and sending automated notifications to parents and school staff.

It helps schools reduce manual work, improve enquiry management and respond to parents more efficiently.

## ✨ Key Features

- Automated admission enquiry processing using n8n Webhooks.
- AI-powered enquiry classification using Google Gemini.
- Automatic enquiry data storage in Supabase.
- Parent acknowledgement emails through Gmail.
- Instant school notifications through Telegram.
- Missing email handling.
- Enquiry status management.
- API error logging and workflow error handling.

## 🛠️ Technology Stack

- **Workflow Automation:** n8n
- **AI Model:** Google Gemini AI
- **Database:** Supabase
- **Email Automation:** Gmail
- **Notifications:** Telegram Bot
- **Integration:** REST APIs, Webhooks
- **Data Processing:** JavaScript

## ⚙️ Workflow Architecture

1. Receive admission enquiry through webhook.
2. Process enquiry details.
3. Analyze and classify enquiry using Gemini AI.
4. Store enquiry information in Supabase.
5. Send acknowledgement email to parents.
6. Notify school staff through Telegram.
7. Handle missing email addresses.
8. Log API errors for monitoring and troubleshooting.

## 📂 Project Structure

```text
ai-powered-school-admission-automation/
│
├── README.md
├── workflow.json
├── .gitignore
│
├── screenshots/
│
├── database/
│   └── schema.sql
│
├── sample-data/
│   └── sample-enquiry.json
│
└── docs/
    └── setup-guide.md
```

## 📸 Screenshots

Project workflow screenshots and execution results are available in the `screenshots` folder.

## 🔧 Setup & Installation

1. Install and configure n8n.
2. Import the `workflow.json` file into n8n.
3. Configure Google Gemini API credentials.
4. Connect Supabase database.
5. Configure Gmail credentials.
6. Configure Telegram Bot credentials.
7. Activate the workflow and test with sample admission enquiries.

## 🔐 Security

- Never upload API keys, passwords or private credentials.
- Use n8n credentials for secure integrations.
- Use sample data instead of real student or parent information.

## 🎯 Project Objective

To simplify school admission enquiry management through AI-powered workflow automation, faster communication and centralized enquiry records.

## 👨‍💻 Developer

**Anuj Singh**  
AI Automation Engineer

- LinkedIn: https://www.linkedin.com/in/anujkumarsingh01
- GitHub: https://github.com/anujsingh503

## 📄 License

This project is available for educational and portfolio demonstration purposes.
