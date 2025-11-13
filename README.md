<h1 align="center"><img width="1041" height="470" alt="image" src="https://github.com/user-attachments/assets/537daea4-1840-40aa-bfdc-77189882b4a3" />


<h1 align="center">Clinibot 🏥🤖</h1>
<h3 align="center">AI-powered WhatsApp Concierge for Clinics</h3>

<p align="center">
  Built by <strong>Trend AI</strong> — automation-first, AI-driven systems.<br>
  Clinibot runs in <strong>70+ clinics</strong> improving patient flow, reducing no-shows, and automating the full appointment lifecycle.
</p>

---

# Overview

**Clinibot** is an AI-powered WhatsApp automation system designed specifically for clinics, medical centers and healthcare operations.

It handles the complete patient communication flow:

- Appointment scheduling  
- Reminders & confirmations  
- Intelligent follow-ups  
- Post-consultation instructions  
- Re-engagement  
- Feedback collection  
- Admin workflow automation  

Clinibot eliminates human bottlenecks and ensures consistent, reliable and compliant communication.

---

# Key Results

- 📉 **43% reduction in no-shows**  
- 🔁 **38% increase in returning patients**  
- 📈 Significant improvement in clinic efficiency  
- 💬 24/7 automated patient communication  
- ⏳ Saves 40–70 hours/month for reception teams  

---

# Features

### 📅 Smart Scheduling
- Multi-branch / multi-professional scheduling  
- Calendar integration  
- Automated double-confirmation logic  
- Schedule conflict prevention  

### 🔔 Automated Reminders
- Pre-consultation  
- Day-before  
- Hour-before  
- Custom sequences  

### 🧠 AI Assistant Layer
- Pre-diagnosis intake questions  
- FAQ  
- Basic guidance  
- Polite refusal for unethical requests  
- Defensive communication  

### 📝 Post-Consultation Automation
- Medication instructions  
- Care guidelines  
- Exam preparation  
- Follow-up reminders  

### ❤️ Patient Retention
- Re-engagement flows  
- “We haven't seen you in a while” automation  
- Intelligent segmentation  

### 📊 Reporting & Insights
- Attendance rate  
- Conversion rate  
- Peak hours  
- Drop-off points  

---

# Tech Stack

### AI & Reasoning  
- GPT-4/4o  
- Prompt guardrails for medical compliance  
- Smart intent routing  

### WhatsApp Automation  
- WhatsApp Cloud API  
- n8n orchestration  
- Webhooks + retries  
- Fail-safe queue execution  

### Backend  
- Supabase (Postgres + RLS + edge functions)  
- Logging & message tracking  
- Appointment metadata tables  

### Integrations  
- Google Calendar  
- CRM / HIS systems  
- Payment links  
- Internal APIs  

---

# Architecture

    Patient (WhatsApp)
            ↓
    WhatsApp Cloud API
            ↓
    n8n Orchestration Layer
            ↓
    Intent Classifier
            ↓
    Scheduling / Reminders / AI Layer
            ↓
    Supabase (data store)
            ↓
    Response back to patient

---

# Typical Use Cases

- 📅 Fully automated clinic scheduling  
- 🔔 High-precision appointment reminders  
- ❤️ Retention & re-engagement  
- 🧠 AI triage & FAQ  
- 📝 Post-consultation care guidance  
- 📊 Attendance optimization  
- 👥 Multi-professional / multi-unit operations  

---

# Integration Pattern

1. Patient message arrives via WhatsApp  
2. Engine identifies intent  
3. Routing logic chooses: scheduling, FAQ, instructions or retention  
4. Automated response generated  
5. Data stored in Supabase  
6. Follow-up flows triggered automatically  

---

# Contact

Built by **Trend AI**  
🌐 Website: trendai.com.br

📧 trendaisac@gmail.com

---

<h4 align="center">Douglas | Automation Engineer & Workflow Architect</h4>
