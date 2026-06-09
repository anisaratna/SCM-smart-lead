# 🛡️ AI Smart Lead Architect: Autonomous Lead Management System

## 📌 Project Overview
This project is an advanced AI-powered automation system designed to optimize the inbound lead management process. Built using **n8n**, the system acts as an "Autonomous Business Concierge" that triages incoming inquiries, performs sentiment analysis, and orchestrates cross-functional actions (Sales & Support) with a **Human-in-the-loop** approval mechanism.

## 🎯 Business Problem
Multinational companies often face "Information Latency" where sales opportunities are missed due to slow manual response times. This system reduces response time from hours to seconds while maintaining high-quality, personalized engagement.

## 🛠️ Tech Stack & Integrations
* **Orchestration:** n8n (Advanced Workflow Automation)
* **AI Brain:** Llama 3.3 70B (via Groq API)
* **Ingestion:** Google Forms & Google Sheets
* **Project Management:** Trello API (Automated Ticketing)
* **Communication:** Telegram Bot API (Approval Interface)
* **Output:** Gmail API (OAuth2)

## 🚀 The Intelligent Workflow
1. **Trigger:** Captures real-time data from Google Form submissions.
2. **AI Classification:** Uses LLM to analyze intent, calculate priority (0-100), and detect language/slang.
3. **Smart Routing:** 
   - **TECHNICAL:** Automatically creates a Trello card for the IT team and sends an instant confirmation email.
   - **SALES_HOT:** Triggers a high-priority alert to the Manager via Telegram with an AI-generated email draft and interactive "Approve/Reject" buttons.
   - **SALES_COLD:** Archives data to Google Sheets for future nurturing.
4. **Approval Loop:** Gmail responses are only sent for High-Priority leads after manual verification via Telegram.

## 📊 Impact
* **Efficiency:** 98% reduction in manual triage time.
* **Accuracy:** High-precision intent detection using Few-shot prompting.
* **Reliability:** Implemented OAuth2 for secure enterprise-grade authentication.

## 🎥 Visual Demo
[INSERT SCREENSHOT OR LINK TO VIDEO DEMO HERE]
