# School Admission Automation – Setup Guide

## 1. Project Overview

This project automates school admission enquiries using n8n, Google Gemini AI, Supabase, Gmail and Telegram.

## 2. Prerequisites

Before setting up the project, make sure you have:

- n8n installed or hosted
- Google Gemini API access
- Supabase account and project
- Gmail account with n8n integration
- Telegram Bot for school notifications

## 3. Import n8n Workflow

1. Open your n8n instance.
2. Navigate to Workflows.
3. Select Import from File.
4. Upload the `workflow.json` file.
5. Review the workflow nodes and connections.

## 4. Configure Credentials

Configure the following credentials in n8n:

- Google Gemini API
- Supabase connection
- Gmail OAuth2
- Telegram Bot API

Never upload API keys, passwords or private tokens to GitHub.

## 5. Configure Supabase Database

1. Open your Supabase project.
2. Navigate to SQL Editor.
3. Refer to `database/schema.sql`.
4. Verify the table structure and configure the database connection in n8n.

## 6. Test the Workflow

1. Send a sample admission enquiry to the configured webhook.
2. Verify Gemini AI classification.
3. Check whether enquiry data is stored in Supabase.
4. Verify parent acknowledgement email.
5. Check Telegram school notification.
6. Review error handling and enquiry status.

## 7. Sample Input

Refer to `sample-data/sample-enquiry.json` for sample admission enquiry data.

## 8. Security

- Keep API credentials private.
- Use environment variables or n8n credential management.
- Use dummy student and parent information for testing.

## 9. Project Developer

**Anuj Singh**  
AI Automation Engineer

GitHub: https://github.com/anujsingh503

LinkedIn: https://www.linkedin.com/in/anujkumarsingh01
