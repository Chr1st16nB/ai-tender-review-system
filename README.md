# 🚀 AI Tender Review System (V1)

## 🧠 Overview

An AI-powered **multi-agent system** that analyzes tender documents and delivers a **Go / Review / No-Go decision** with a professional PDF report — in under 5 minutes.

This system is designed for **companies that bid on tenders** and need fast, data-driven decision-making.

---

## ⚡ Key Features

* 📄 Upload tender documents (PDF)
* 🤖 Multi-agent AI analysis:

  * Compliance
  * Technical Fit
  * Financial Evaluation
  * Risk Assessment
  * Opportunity Analysis
* 📊 Weighted scoring system
* 🧠 Intelligent decision engine:

  * ✅ GO
  * ⚠️ REVIEW
  * ❌ NO-GO
* 📧 Automated email delivery
* 🧾 Executive PDF report generation

---

## 🏗️ System Architecture

This system is built using **n8n** and follows a multi-agent architecture:

1. Document ingestion (PDF)
2. Data extraction & parsing
3. AI agents evaluation
4. Scoring engine
5. Decision engine
6. Report generation (HTML → PDF)
7. Email delivery

---

## 📊 Example Output

* **Final Score:** 72.5 / 100
* **Decision:** ❌ NO-GO
* **Key Insight:** High risk level overrides acceptable scoring

👉 See full report: `docs/sample-report.pdf`

---

## 🧠 Decision Logic (V1)

```text
- Compliance < 70 → NO-GO
- Risk ≥ 80 → NO-GO
- Score ≥ 75 → GO
- Score 60–74 → REVIEW
- Score < 60 → NO-GO
```

---

## 📁 Project Structure

```
ai-tender-review-system/
│
├── workflow/
│   └── tender-review-v1.json
│
├── docs/
│   ├── sample-report.pdf
│   └── screenshots/
│       ├── full-workflow.png
│       └── email-sent.png
│
├── README.md
└── LICENSE
```

---

## 🛠️ Tech Stack

* **n8n** – Workflow automation
* **LLM APIs (OpenAI / Claude)** – AI agents
* **PDF.co** – PDF generation
* **Gmail / SMTP** – Email delivery
* **Google Sheets** (optional) – Logging & tracking

---

## 💼 Use Cases

* Construction & Engineering firms
* IT & Consulting companies
* Procurement teams
* SMEs bidding on tenders

---

## 🚀 Roadmap

### 🔹 V2 (Next)

* Learning from past tenders
* Confidence scoring improvement
* Dashboard (Google Sheets / Notion)

### 🔹 V3

* Company-specific AI agents
* Predictive bid success analysis
* SaaS platform

---

## 💰 Commercial Potential

This system replaces **manual tender analysis**, saving hours of work and enabling faster, smarter decisions.

---

## 👤 Author

**Christian Mangala**
AI Automation | Cloud | Project Management

---

## ⭐ Support

If you find this project useful:
👉 Star the repository
👉 Share it
👉 Reach out for collaboration
