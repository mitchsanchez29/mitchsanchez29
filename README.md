# Hi, I'm Michelle 👋

### Google Workspace Automation & API Integration Specialist

I build automated business workflows using **Google Apps Script**, **REST APIs**, **webhooks**, and **Google Workspace tools** — replacing manual processes with reliable, scalable systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Site-6366F1?style=flat&logo=github&logoColor=white)](https://mitchsanchez29.github.io/automation-portfolio/)
[![OnlineJobs.ph](https://img.shields.io/badge/OnlineJobs.ph-View%20Profile-FF6B35?style=flat)](https://v2.onlinejobs.ph/jobseekers/info/1257742)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-00C47F?style=flat&logo=gmail&logoColor=white)](mailto:sanchezmitch77@gmail.com)

---


## 📌 Featured Projects

### 1. Automated Quotation & CRM System

> *End-to-end document and client tracking automation — from form submission to PDF delivery.*

**The problem:** Quotes were created manually, tracked in disconnected spreadsheets, and sent individually — slow, error-prone, and hard to follow up on.

**What I built:** A fully automated pipeline triggered by a Google Form submission. Apps Script generates a unique quote number, populates a Google Docs template, converts it to PDF, stores it in Drive, and sends it to the client via Gmail — all without manual input.

**Workflow Diagram**

<img width="692" height="258" alt="Screenshot 2026-06-05 181724" src="https://github.com/user-attachments/assets/6e47ecc1-7553-4847-84cb-87bd3fb6ab26" />


**Key features:**
- Auto-generated sequential quote numbers
- Status tracking dashboard in Google Sheets
- PDF stored and organized automatically in Google Drive
- Client email sent with quote attached — zero manual steps

**Screenshots**

| **Lead Tracker (Sheets)** | **Dashboard Summary** |
|---|---|
| <img width="600" alt="Lead Tracker" src="https://github.com/user-attachments/assets/f4f73371-54c9-4d2f-841e-1372d42445fc" /> | <img width="600" alt="Dashboard Summary" src="https://github.com/user-attachments/assets/d1705835-5754-47bb-9624-3eac80989d28" /> |

**Auto-generated Response & Google Drive Storage**

<img width="800" alt="Auto-generated Response and Drive Storage" src="https://github.com/user-attachments/assets/1ec987a5-3cb4-41c0-9b54-4807398515c7" />

**Stack:** `Google Forms` `Apps Script` `Google Sheets` `Google Docs` `Drive` `Gmail` `PDF`

### 2. Facebook Ads Performance Dashboard

> *Connected Facebook Ads data into a live Looker Studio dashboard for real-time campaign visibility.*

**The problem:** Facebook Ads performance data had no centralized view — reporting was manual, slow, and inconsistent.

**What I built:** A Looker Studio dashboard connected to Facebook Ads via OAuth token and a partner connector. The dashboard auto-refreshes and gives the team a live view of campaign spend, reach, and results.

**Workflow Diagram**

<img width="709" height="303" alt="Screenshot 2026-06-05 181646" src="https://github.com/user-attachments/assets/dd44518e-1bd5-4ebf-8dce-9a3e7b4609b5" />

**Key features:**
- Facebook Ads connected via OAuth token + partner connector
- Live campaign metrics: spend, reach, CPM, CTR, results
- Auto-refreshing — no manual exports needed
- Single source of truth for the marketing team

**Screenshots**

| **Facebook Ads Manager** | **Looker Studio Dashboard** |
|---|---|
| <img width="807" height="357" alt="Screenshot 2026-06-09 154016" src="https://github.com/user-attachments/assets/35822623-7d5b-4010-a347-08dd520b7cc1" /> | <img width="525" height="527" alt="Screenshot 2026-06-09 153941" src="https://github.com/user-attachments/assets/8d8ecee4-b2bc-4daf-be1a-a9cf82c9818a" />|

**Stack:** `Facebook Ads API` `OAuth Token` `Partner Connector` `Looker Studio`

---

### 3. Google Ads & Analytics Performance Report

> *Multi-page Looker Studio report with Week-over-Week, Month-over-Month, and Year-to-Date views.*

**The problem:** Google Ads and Analytics data had no structured reporting — no way to quickly compare performance across different time periods.

**What I built:** A multi-page Looker Studio dashboard connected to Google Analytics, providing clear and consistent performance reporting across WoW, MoM, and YTD views — all in one shareable PDF-ready report.

**Workflow Diagram**

<img width="703" height="321" alt="Screenshot 2026-06-05 181628" src="https://github.com/user-attachments/assets/a11d83b5-828b-4423-80bd-9316abd687f9" />

**Key features:**
- Connected to Google Analytics via native Looker Studio connector
- Week-over-Week, Month-over-Month, Year-to-Date performance pages
- Multi-page report layout — one page per reporting view
- Shareable as PDF for client or management reporting

**Screenshots**

| **Page 1 — WoW Report** | **Page 2 — MoM Report** | **Page 3 — YTD Report** |
|---|---|---|
| <img width="527" height="587" alt="Screenshot 2026-06-09 154351" src="https://github.com/user-attachments/assets/60da1bf2-7ea7-4235-a6d8-ff5e79d98ffe" /> | <img width="526" height="592" alt="Screenshot 2026-06-09 154425" src="https://github.com/user-attachments/assets/a9cc0be9-a82c-44bf-81ad-52e3cce59f26" /> | <img width="496" height="691" alt="Screenshot 2026-06-09 154455" src="https://github.com/user-attachments/assets/d2e7419a-6a73-4d81-97f4-518ae45c145f" /> |

**Stack:** `Google Ads` `Google Analytics` `Looker Studio` `Native Connector` `PDF Report`


### 3. Upcoming & Delayed Payments Tracker

> *Automated payment aging system — splits clients into Upcoming and Delayed sheets, triggers Slack follow-ups, and powers two live Looker Studio dashboards.*

**The problem:** Payment data came in from multiple spreadsheets with inconsistent formatting. Identifying overdue and upcoming payments required hours of manual checking every week — and follow-ups were done manually.

**What I built:** An Apps Script solution that reads from a master **Installment Tracker** sheet, calculates each client's payment aging, and automatically sorts them:

- **0–90 days to due date** → moved to **Upcoming Payments** sheet
- **1+ days overdue** → moved to **Delayed Payments** sheet + **Slack notification** sent to follow up
- Once a payment is marked as **paid**, it is automatically **removed** from the Delayed tracker
- Two separate **Looker Studio dashboards** — one per sheet — for management reporting

**Workflow Diagram**

<img width="572" height="426" alt="Screenshot 2026-06-09 155745" src="https://github.com/user-attachments/assets/f3905c72-b6cd-4622-bf3e-b0f4de6dfee8" />

**Key features:**
- Reads from master Installment Tracker as single source of truth
- Aging logic: calculates days remaining or days overdue per client
- Auto-splits data into Upcoming vs. Delayed sheets
- Paid entries auto-removed from Delayed tracker — always clean
- Slack webhook notification for overdue follow-ups
- Two Looker Studio dashboards — Upcoming and Delayed — updated automatically

**Screenshots**

| **Upcoming Payments Sheet** | **Delayed Payments Sheet** |
|---|---|
| <img width="801" height="436" alt="Upcoming Payments" src="https://github.com/user-attachments/assets/ee2972a4-4b4d-4f31-8de7-c9c11a3fcfad" /> | <img width="1037" height="524" alt="Screenshot 2026-06-09 012519" src="https://github.com/user-attachments/assets/c97f5689-aac0-40b8-a854-0ef184d39bf3" /> |

| **Looker Studio — Upcoming Dashboard** | **Looker Studio — Delayed Dashboard** |
|---|---|
| <img width="596" height="527" alt="Screenshot 2026-06-09 022557" src="https://github.com/user-attachments/assets/6ad35d81-8779-4a62-9d5f-a7af7d290e02" /> | <img width="600" height="535" alt="Screenshot 2026-06-09 022721" src="https://github.com/user-attachments/assets/a312a9e3-63ef-4c36-91e0-fa8337d37b90" /> |

**Stack:** `Google Apps Script` `Google Sheets` `Slack Webhooks` `Looker Studio`

## 📂 More Projects

<details>
<summary><strong>Payment Performance Dashboard</strong> · Looker Studio</summary>

**Goal:** Provide clear visibility of payment performance and status.

**What I built:** A Looker Studio dashboard using a Google Sheets payment tracker as the data source. Visualizes key payment metrics — total payments, collected amounts, pending balances, and payment status — in a centralized, real-time view.

**Impact:** Improved reporting visibility and made it easier to monitor payment performance without manually checking spreadsheets.

**Financial Dashboard - LookerStudio Screenshot**

<img width="597" height="527" alt="Screenshot 2026-06-09 022906" src="https://github.com/user-attachments/assets/2ca587ef-4035-4071-8596-2afd19bfab63" />

**Stack:** `Looker Studio` `Google Sheets` `Data Visualization` `Financial Reporting`

</details>

---

<details>
<summary><strong>Financial Dashboard & Profit/Loss Reporting</strong> · Google Sheets</summary>

**Goal:** Build a clear view of business financial performance using payment and expense data.

**What I built:** A Google Sheets dashboard that consolidates income, expenses, net cash collected, and profit/loss — with monthly and quarterly performance tracking, automated calculations, and structured reporting.

**Impact:** Improved financial visibility and made it easier to track business performance, profitability, and cash flow in one centralized dashboard.

**Financial Dashboard - Google sheets Screenshot**

<img width="597" height="527" alt="Screenshot 2026-06-09 022906" src="https://github.com/user-attachments/assets/2ca587ef-4035-4071-8596-2afd19bfab63" />

**Stack:** `Google Sheets` `Financial Reporting` `Data Management` `Dashboard` `Data Visualization`

</details>

---

<details>
<summary><strong>YouTube Analytics Reporting Pipeline</strong></summary>

**What it does:** A daily time-based trigger in Apps Script pulls data from the YouTube Analytics API, stores it in a Google Sheets data warehouse, and populates a Looker Studio dashboard for channel performance tracking.

**Workflow**

<img width="695" height="280" alt="Screenshot 2026-06-05 181706" src="https://github.com/user-attachments/assets/865afe3c-22ba-4a90-8a53-c5bbeef1a12b" />


**Dashboard Screenshot**

<img width="1366" height="768" alt="5" src="https://github.com/user-attachments/assets/cfbce0c0-d918-44aa-adfa-a2b20b824374" />


**Stack:** `YouTube Analytics API` `Apps Script` `UrlFetchApp` `Google Sheets` `Looker Studio`

</details>

---

<details>
<summary><strong>Closer & Setter EOD Data Pipeline</strong> <em>(Team Project)</em></summary>

**What it does:** Sales closers and setters submit end-of-day data via Airtable Form. An automated Zapier integration (set up by the team) transfers submissions to Google Sheets. 

**My role:** Daily data monitoring, cleaning, structuring cash collected, payments, and commissions — then building and maintaining the Looker Studio performance report.

**Workflow**

<img width="695" height="309" alt="Screenshot 2026-06-05 181511" src="https://github.com/user-attachments/assets/f92b02cc-fb98-43a5-a1a4-871134b88d65" />


**Screenshot**

<img width="572" height="526" alt="Phone setter" src="https://github.com/user-attachments/assets/7657ecba-08f5-4186-8455-ea9ecd9180fc" />
<img width="623" height="462" alt="Screenshot 2026-06-09 161007" src="https://github.com/user-attachments/assets/5b1a732d-2bb6-435b-adb8-ac3127fb9196" />


**Stack:** `Airtable` `Zapier` `Google Sheets` `Looker Studio`

</details>

---

<details>
<summary><strong>Slack Webhook & Notification Automation</strong></summary>

**What it does:** Apps Script listens for trigger events (form submissions, sheet edits) and sends real-time notifications to a Slack channel via Incoming Webhooks — eliminating manual status update messages.

**Workflow**

<img width="697" height="267" alt="Screenshot 2026-06-05 181556" src="https://github.com/user-attachments/assets/2dcf9943-c06b-4aba-80a0-c86fdc0be2cb" />

**Stack:** `Google Apps Script` `UrlFetchApp` `Slack Incoming Webhooks` `REST API` `JSON`

</details>

---

<details>
<summary><strong>ChatGPT API Email Automation</strong> <em>(In Development)</em></summary>

**What it does:** Integrates the ChatGPT API with Google Apps Script to generate context-aware email drafts automatically. The script reads data from Sheets, builds a prompt, calls the OpenAI API, and creates a Gmail draft — ready for human review before sending.


**Stack:** `ChatGPT API` `Google Apps Script` `Gmail` `OpenAI API`

</details>

---

## 📊 How I Work

```
Understand the manual process
        ↓
Map the workflow end-to-end
        ↓
Identify automation trigger points
        ↓
Build → Test → Deploy
        ↓
Document + hand off clean
```

I don't just automate — I make sure the output is clean, the data is reliable, and the reports tell the right story.

---

## 📬 Available For

- Freelance automation projects
- VA roles with a technical / data focus
- Google Apps Script development
- Looker Studio dashboard builds
- API integration work
- Data cleaning and reporting systems

**Based in the Philippines · Remote-ready worldwide**

---

*Last updated: 2025 · Built with Google Apps Script, APIs, and a lot of UrlFetchApp calls.*
