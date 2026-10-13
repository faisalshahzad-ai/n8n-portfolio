# n8n Automation Portfolio

Sample n8n workflows by **Faisal Shahzad Naeem**. Each project is a ready-to-import JSON file. Download it, import it into n8n, connect your own accounts and customize it for your business.

> All projects here are **sample / demo projects**.

## Projects

| No. | Project | What it does | Tools | File |
|---|---|---|---|---|
| 03 | AI-Powered Task Priority & Deadline Reminder Automation | Watches a Google Sheet for new tasks and emails the right reminder based on task priority and deadline | n8n, Google Sheets, Gmail | [03-task-priority-reminder.json](03-task-priority-reminder.json) |
| 04 | Employee Email Notification & Batch Processing Automation | Reads employees from Google Sheets and sends personalised emails in small batches with a wait step to avoid sending limits | n8n, Google Sheets, Gmail | [04-employee-email-batch-processing.json](04-employee-email-batch-processing.json) |
| 05 | Automated Price Validation & Update Notification Workflow | Cleans raw price data, validates it, saves it to Google Sheets, emails the update and sends a completion confirmation | n8n, Google Sheets, Gmail, JavaScript | [05-price-validation-update-notification.json](05-price-validation-update-notification.json) |
| 06 | Contract Signing & Automated Client Onboarding Workflow | Receives a contract-signed event by webhook, emails the client, updates Google Sheets and alerts the team on Slack | n8n, Webhook, Gmail, Google Sheets, Slack | [06-contract-signing-client-onboarding.json](06-contract-signing-client-onboarding.json) |
| 07 | AI-Powered Task Priority & Deadline Notification Automation | Watches a Google Sheet for new tasks and sends a deadline email based on priority: high, medium or low | n8n, Google Sheets, Gmail | [07-task-priority-deadline-notification.json](07-task-priority-deadline-notification.json) |
| 08 | AI-Powered Weather Intelligence & Business Alert Automation | Fetches live weather data, logs it to Google Sheets, sends alerts for rain, heat, cold, wind, UV and humidity, then uses an AI agent to write a business recommendation report | n8n, WeatherAPI, Groq AI Agent, Gmail, Google Sheets | [08-ai-weather-intelligence-business-alerts.json](08-ai-weather-intelligence-business-alerts.json) |
| 09 | Employee Email Batch Notification & Processing Automation | Reads employees from Google Sheets, sends personalised emails in small batches with a wait step, then summarizes the run and sends a completion report | n8n, Google Sheets, Gmail | [09-employee-email-batch-summary-report.json](09-employee-email-batch-summary-report.json) |
| 10 | AI-Powered Multi-Gmail Email Response Automation | Reads incoming emails from multiple Gmail accounts, uses an AI agent to write a professional reply and sends it back to the sender automatically | n8n, Gmail, Groq AI Agent | [10-ai-multi-gmail-email-auto-reply.json](10-ai-multi-gmail-email-auto-reply.json) |
| 11 | AI-Powered Email Classification & Automated Response System | Reads new Gmail emails, uses an AI text classifier to sort them into categories such as orders, jobs, complaints, payments, refunds and support, sends an automatic reply, marks the email as read and adds a label | n8n, Gmail, Groq AI, Text Classifier | [11-ai-email-classification-auto-response.json](11-ai-email-classification-auto-response.json) |
| 12 | AI-Powered Multi-Gmail Email Auto-Reply & Management Automation | Monitors three Gmail accounts at once, uses an AI agent to write a professional reply to each new email, marks the message as read and adds a label to keep every inbox organised | n8n, Gmail, Groq AI Agent | [12-ai-multi-gmail-auto-reply-management.json](12-ai-multi-gmail-auto-reply-management.json) |
| 13 | AI-Powered Intelligent Email Triage & Auto-Reply Automation | Reads each new Gmail email, uses an AI agent to detect job or personally important messages, and sends a professional automatic reply only to the rest | n8n, Gmail, Groq AI Agent | [13-ai-intelligent-email-triage-auto-reply.json](13-ai-intelligent-email-triage-auto-reply.json) |
| 14 | Google Maps Business Lead Data Automation | Fetches a Google Maps search results page for a business type and city, removes duplicates, limits the batch, and saves the collected data into Google Sheets | n8n, HTTP Request, JavaScript, Google Sheets | [14-google-maps-business-lead-data-automation.json](14-google-maps-business-lead-data-automation.json) |
| 15 | AI Lead Qualification & Routing System | Receives leads through a webhook, validates them, syncs contacts and deals in HubSpot, scores leads with an AI chain, alerts the sales team on Slack, emails leads, logs them to Google Sheets, and sends a daily lead report | n8n, HubSpot, OpenAI, Slack, Gmail, Google Sheets | [15-ai-lead-qualification-routing-system.json](15-ai-lead-qualification-routing-system.json) |
| 16 | AI Email Triage & Auto-Reply System | Watches incoming Gmail messages, skips newsletters and no-reply senders, classifies each email with AI, creates HubSpot contacts, drafts sales and support replies in Gmail, forwards billing emails, alerts the team on Slack, logs everything to Google Sheets, and sends a daily summary | n8n, Gmail, OpenAI, HubSpot, Slack, Google Sheets | [16-ai-email-triage-auto-reply-system.json](16-ai-email-triage-auto-reply-system.json) |

## Workflow Screenshots

### 03 - Task Priority & Deadline Reminder

<img width="1280" height="769" alt="Task priority workflow" src="https://github.com/user-attachments/assets/a690233c-a989-41b5-bd15-cfbfa8ca0949" />

### 04 - Employee Email Batch Processing

<img width="1280" height="769" alt="Employee email batch processing workflow" src="https://github.com/user-attachments/assets/d3cdeb23-c99b-4ee4-9750-5401f4e3f656" />

### 05 - Price Validation & Update Notification

<img width="1280" height="769" alt="Price validation workflow" src="https://github.com/user-attachments/assets/aa8ffa41-993b-4d48-a785-fe507e866d50" />

### 06 - Contract Signing & Client Onboarding

<img width="1280" height="769" alt="Contract signing workflow" src="https://github.com/user-attachments/assets/61683df2-dfc2-419f-8e60-54cd2606c521" />

### 07 - Task Priority & Deadline Notification

<img width="1280" height="769" alt="Task priority deadline notification workflow" src="https://github.com/user-attachments/assets/9b03d2af-0e3c-4a5a-aee5-701dba5ed0a0" />

### 08 - AI Weather Intelligence & Business Alerts

<img width="1280" height="769" alt="AI weather intelligence workflow" src="https://github.com/user-attachments/assets/eefbcaeb-6767-4693-9ef4-6500928920e6" />

### 09 - Employee Email Batch Summary Report

<img width="1280" height="769" alt="Employee email batch summary report workflow" src="https://github.com/user-attachments/assets/d8ffb57e-32ba-43ee-8b76-c1e31b5d991f" />

### 10 - AI Multi-Gmail Email Auto Reply

<img width="1280" height="769" alt="AI multi Gmail email auto reply workflow" src="https://github.com/user-attachments/assets/10f8df00-577d-44dc-89df-02d75b15588a" />

### 11 - AI Email Classification & Auto Response
<img width="1280" height="769" alt="Untitled design (8)" src="https://github.com/user-attachments/assets/4b75ec5e-02de-429d-93ac-6f362dff56e9" />
### 12 - AI Multi-Gmail Auto Reply & Management
<img width="1280" height="769" alt="Untitled design (9)" src="https://github.com/user-attachments/assets/542e14ae-f376-4cc5-9674-e38fbf0eaa48" />
### 13 - AI Intelligent Email Triage & Auto Reply
<img width="1280" height="769" alt="Untitled design (10)" src="https://github.com/user-attachments/assets/9ced59b4-30f5-477e-b83b-7d7293e368c6" />
### 14 - Google Maps Business Lead Data Automation
<img width="1280" height="769" alt="Untitled design (11)" src="https://github.com/user-attachments/assets/9fe23a15-6c20-483e-9186-6dd30378d52b" />
### 15 - AI Lead Qualification & Routing System
<img width="1280" height="769" alt="Untitled design (12)" src="https://github.com/user-attachments/assets/43a08e9a-79b2-4472-83ee-b570b0549b9c" />
### 16 - AI Email Triage & Auto-Reply System
<img width="1280" height="769" alt="Untitled design (13)" src="https://github.com/user-attachments/assets/fe41fce0-68bd-47a0-bc60-0edac891558b" />

![AI email classification and auto response workflow](11-ai-email-classification-auto-response.png)

## How to use a workflow

1. Download the `.json` file.
2. In n8n, click the **⋯** menu, then **Import from file**.
3. Connect your own Google Sheets and Gmail credentials.
4. Replace `YOUR_SHEET_ID` with the ID of your own Google Sheet.
5. For the weather and AI email workflows, add your own WeatherAPI key and Groq API key.
6. For workflow 11, replace `YOUR_LABEL_ID` with the ID of your own Gmail label.
7. Test the email auto-reply workflows (10 and 11) with a test Gmail account before connecting a real inbox.
8. Test it, then activate.

## Contact

Available for n8n and AI automation work on Fiverr, Upwork, Freelancer, Guru and PeoplePerHour.
