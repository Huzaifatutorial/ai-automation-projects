# AI Automation Projects

A collection of AI agent automation workflows built using n8n, integrating LLMs (Groq, Gemini) with real-world channels like Gmail, WhatsApp, voice calls, and websites.

Built by Huzaifa Farooq — CS graduate specializing in AI agent automation.

## Projects

### 1. Gmail AI Reply Agent
File: My_gmail.json

Reads incoming Gmail messages and generates AI-drafted replies using LLM prompts (Groq + Gemini). Logs conversation data to Google Sheets for tracking and review.

Tech: n8n, Groq, Gemini, Gmail API, Google Sheets

### 2. WhatsApp Restaurant AI Agent
File: whatsapp_message.json

Takes customer orders and answers menu questions directly over WhatsApp. Automatically logs orders to Google Sheets, removing manual order-entry work.

Tech: n8n, Meta WhatsApp Cloud API, Google Sheets

### 3. Website AI Chatbot
File: Chatbot_Agent.json

A conversational AI widget embedded on a website to handle visitor queries in real time, connected to an n8n backend for dynamic, context-aware responses.

Tech: n8n, LLM APIs, HTML/CSS

### 4. Voice Calling AI Agent
File: Calling Agent.json

A phone-based conversational AI agent that handles inbound/outbound calls using ElevenLabs Conversational AI and Twilio.

Tech: n8n, ElevenLabs Conversational AI, Twilio

## How to Import a Workflow into n8n

1. Download any .json file from this repo
2. Open your n8n instance and click Create workflow
3. Click the three-dot menu (top-right) and select Import from File
4. Select the downloaded .json file
5. Reconnect your own credentials (API keys are not included for security)

## Notes

- All projects run on free-tier APIs
- Credentials and API keys are not included in these files for security
