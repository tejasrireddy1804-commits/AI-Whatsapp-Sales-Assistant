# AI-Whatsapp-Sales-Assistant
An AI-driven WhatsApp automation workflow built on n8n to help businesses instantly respond to customer queries, dynamically share product catalogs, track leads, and manage automated follow-ups.Using a low-code/node-based backend engine allows this system to scale messaging webhooks instantly, reliably parse unstructured text with LLMs.


**#MVP Scope & Features**
Dynamic Catalog Dispatch: Instantly intercepts product or pricing queries on WhatsApp and replies with relevant catalog links or media assets.
AI-Powered Inquiry Tracker: Uses an advanced LLM node to extract intent, customer name, contact details, and product interest from raw WhatsApp messages.
Suggested Replies Dashboard: Filters ambiguous customer chats into a review queue, generating AI-suggested drafts for human agents to approve or edit.
Automated Follow-up Reminders: Uses n8n wait/cron nodes to trigger follow-up alerts if a lead has been inactive for a specified timeframe.
Lead Status Pipeline: Synchronizes captured lead data with a lightweight CRM or database backend (e.g., Airtable, PostgreSQL, Supabase) to manage pipeline stages.Tech Stack

**Workflow Orchestration: **
n8n (Self-hosted via Docker / n8n Cloud)
AI & NLP: OpenAI Node (gpt-4o or gpt-4o-mini) / Anthropic Node/google chat model/groq chat model
WhatsApp Gateway: WhatsApp Business Cloud API / Twilio / Vonage Node/wander
Database / CRM: Supabase, Airtable, or PostgreSQL/Redis
