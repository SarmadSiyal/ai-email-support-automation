## AI-Powered Smart Email Customer Support & Escalation System
## 📌 Overview

This project is a production-ready AI-driven email automation system designed to intelligently classify, route, and escalate customer emails using AI-based decision logic.

The system reduces manual workload while ensuring safety through confidence thresholds and human-in-the-loop fallback.

## 🚀 Key Features
- AI-based email classification (Refund, Complaint, Question, Spam)
- Sentiment & urgency detection
- Confidence-based routing logic
- Human review fallback
- SLA timer for urgent complaints
- Slack escalation notifications
- Structured audit logging
- Risk-controlled automation
  
## 🏗 Architecture

- Gmail → AI (Groq LLaMA) → JSON Parser → Router → Logging → Escalation / Auto Reply

## 🛠 Tech Stack

- **Automation Platform:** Make.com  
- **Email Service:** Gmail API  
- **LLM Model:** Groq (LLaMA 3)  
- **Logging System:** Google Sheets  
- **Notifications:** Slack  
- **Data Handling:** JSON Structured Parsing  
  
## 📊 Business Impact
- 70–80% reduction in manual email handling
- Immediate escalation of urgent cases
- Structured audit tracking
- Improved response speed
  
## 📸 Screenshots

### 🧩 Workflow Architecture

![Workflow Architecture](screenshots/workflow-architecture.png)

<br>

### 🔔 Slack Alert Example

![Slack Alert Example](screenshots/slack-alert.png)

<br>

### 📄 Logging System (Google Sheets)

![Logging Sheet](screenshots/logging-sheet.png)


## 📂 Workflow File

- The exported automation blueprint is available inside:

- workflow/AI-Powered Smart Email Customer Support & Escalation System.json

- To use:

1. Download JSON file
2. Follow Setup Instructions
   
## ⚙ Setup Instructions
1. Import workflow blueprint into Make.com
2. Add Gmail connection
3. Add Groq API key
4. Configure Slack webhook
5. Connect Google Sheets logging
6. Run scenario

