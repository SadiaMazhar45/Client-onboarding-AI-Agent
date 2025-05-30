# 🤖 Client Onboarding AI Agent – Automated Workflow (n8n)

This project is an intelligent and fully automated client onboarding system built using [n8n](https://n8n.io). It collects client data through a form, generates personalized emails using OpenAI and Gemini, summarizes the client information, and stores it in Google Sheets — all automatically.

---

## 🚀 Features

- **Form-Based Data Collection** – Captures essential client info via a simple form.
- **AI-Powered Email Generation** – Uses OpenAI and Gemini to create custom welcome emails.
- **Smart Client Summarization** – Summarizes client details into actionable insights.
- **Automated Email Sending** – Sends personalized emails via Gmail.
- **Google Sheets Logging** – Stores client name, email, and summary for records.

---

## 🔧 Tech Stack

- [n8n](https://n8n.io) (workflow automation)
- OpenAI GPT-4o (email & summary generation)
- Google Gemini 1.5 Flash (LLM support)
- Google Sheets API (data storage)
- Gmail API (email delivery)

---

## 🛠️ How It Works

1. Client fills out the onboarding form.
2. AI generates a welcome email using the input.
3. The email is sent automatically to the client.
4. AI also creates a client summary.
5. Summary + client info is stored in Google Sheets.

---

## 📂 Files

- `workflow.json` – n8n export file (masked)
- `README.md` – This file

---

## ✅ Use Cases

- Business client onboarding
- Lead capture automation
- Email marketing funnels
- CRM data enrichment

---

## 🔒 Setup Instructions

1. **Import** `workflow.json` into your n8n instance.
2. **Connect credentials**:
   - OpenAI API Key
   - Gemini API Key
   - Gmail OAuth2
   - Google Sheets OAuth2
3. **Customize form & prompts** as needed.
4. **Activate the workflow** and you're ready to go!

---

## 📄 License

MIT License – Free for personal and commercial use.

---

## 📬 Contact
saidamazharf23@nutech.edu.pk
malaikaakhtarf23@nutech.edu.pk
