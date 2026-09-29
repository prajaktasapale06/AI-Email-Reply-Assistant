
# AI Email Reply Assistant

An AI-powered email assistant built using n8n and Google Gemini.

## Features

- Automatically detects incoming Gmail messages
- Generates an AI-based reply using Google Gemini
- Identifies the sender's name
- Sends the generated draft to a separate approval email
- Allows the user to edit the AI-generated reply
- Sends the final edited reply to the original sender
- Uses Gmail for receiving and sending emails

## Workflow

Gmail Trigger
→ AI Agent
→ Gemini Chat Model
→ Structured Output Parser
→ Send Draft for Approval
→ User Edits Reply
→ Gmail Reply to Original Sender

## Technologies Used

- n8n
- Google Gemini
- Gmail API
- AI Agent
- Structured Output Parser

## How It Works

1. A new email arrives in Gmail.
2. n8n detects the incoming email.
3. Google Gemini analyzes the email and creates a reply.
4. The draft is sent to a separate approval email.
5. The user can edit the generated response.
6. After submission, n8n sends the final response to the original sender.

## Setup

1. Install or access n8n.
2. Import the workflow JSON.
3. Connect your Gmail account.
4. Add your Gemini API credentials.
5. Configure the approval email address.
6. Activate the workflow.

## Security

API keys, Gmail credentials and other secrets should never be committed to GitHub.

## Author

Prajakta Sapale
