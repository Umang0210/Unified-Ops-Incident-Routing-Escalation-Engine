# Unified Ops Incident Routing & Escalation Engine

An event-driven workflow automation system built using **n8n** to detect, classify, and escalate operational incidents such as payment anomalies, SLA breaches, address issues, and fraud indicators.

This project demonstrates how low-code orchestration can be used to build scalable incident management pipelines with structured state handling and automated escalation logic.

---

## 🚀 Key Capabilities

- Event-driven ingestion of operational signals via webhooks  
- Rule-based incident classification and severity assignment  
- Centralized incident state tracking (status, priority, ownership)  
- Time-based SLA monitoring and automated escalation  
- Multi-channel alerting using Slack and Email  
- Fully automated resolution handling for closed incidents  

---

## 🧠 System Overview

The workflow processes incoming events and performs the following steps:

1. **Event Ingestion**  
   Receives operational events through webhooks (payment issues, SLA risks, address quality signals, fraud indicators).

2. **Incident Classification**  
   Applies rule-based logic to determine severity, category, and routing path.

3. **State Management**  
   Maintains incident lifecycle states including open, in-progress, escalated, and resolved.

4. **Escalation & Notification**  
   Triggers time-based checks and escalates unresolved incidents using Slack and Email alerts.

5. **Resolution Handling**  
   Automatically closes resolved cases and updates tracking records.

---

## 🧩 Tech Stack

- **n8n**
- **JavaScript**
- **Webhooks**
- **Cron Jobs**
- **Google Sheets**
- **Slack API**
- **Email APIs**

---

## 📂 Repository Structure

