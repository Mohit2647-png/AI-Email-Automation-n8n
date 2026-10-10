# AI-Email-Automation-n8n
No-code AI email automation using n8n, Gmail, and an AI Agent to read emails, summarize messages, and prepare email replies.
# AI Email Automation Using n8n

## Project Overview
This project uses n8n Cloud, Gmail, and an AI Agent to automate common email tasks without building a traditional application.

## Features
- Retrieve recent emails from Gmail.
- Read and summarize the latest five emails.
- Generate professional email replies using an AI model.
- Connect Gmail operations to an AI Agent as tools.
- Prepare email replies for review before sending.

## Workflow Architecture
![AI Email Automation Workflow](workflow-diagram.png)

**Workflow:** Gmail Trigger → AI Agent → Gmail tools

## Technologies Used
- n8n Cloud
- Gmail integration
- AI Agent
- OpenAI Chat Model
- No-code / low-code automation

## How It Works
1. The Gmail Trigger detects incoming email.
2. The AI Agent processes requests and can use the Gmail tools to retrieve messages.
3. The AI summarizes emails or generates a professional reply.
4. A Gmail draft operation can save the generated reply for review.

## Security
Credentials are configured inside n8n and should not be committed to GitHub. Review and sanitize exported workflow files before sharing them publicly.

## Future Improvements
- Add automatic email categorization.
- Generate daily email summaries.
- Add approval steps before sending replies.
- Add error handling and execution logging.

## Disclaimer
This is a learning and portfolio project. Review AI-generated responses before sending emails.
