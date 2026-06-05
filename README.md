# Hi, I'm Michelle 👋

### Google Workspace Automation & API Integration Specialist

I build automated business workflows using **Google Apps Script**, **REST APIs**, **webhooks**, and **Google Workspace tools** — replacing manual processes with reliable, scalable systems.

[![OnlineJobs.ph](https://img.shields.io/badge/OnlineJobs.ph-View%20Profile-FF6B35?style=flat)](https://onlinejobs.ph/jobseekers/yourprofile)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-00C47F?style=flat&logo=gmail&logoColor=white)](mailto:your@email.com)

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

| CRM Tracker & Dashboard (Sheets) | Auto-generated PDF Output |
|---|---|
<img width="1366" height="856" alt="2" src="https://github.com/user-attachments/assets/fab10ace-c659-4624-a181-9cef2f09713a" /> | <img width="1366" height="768" alt="3" src="https://github.com/user-attachments/assets/1ec987a5-3cb4-41c0-9b54-4807398515c7" /> |


**Stack:** `Google Forms` `Apps Script` `Google Sheets` `Google Docs` `Drive` `Gmail`

---

### 2. Facebook Ads & Google Ads Marketing Performance Dashboard

> *Connected multi-platform ad data into one live Looker Studio dashboard for real-time marketing visibility.*

**The problem:** Marketing performance data lived in separate platforms — Facebook Ads and Google Ads — with no unified view, making reporting slow and inconsistent.

**What I built:** A consolidated Looker Studio dashboard pulling from both platforms using native connectors (Google Ads) and Facebook token-based authentication (Facebook Ads). The dashboard auto-refreshes and gives the team a single source of truth for campaign performance.

**Workflow Diagram**

<img width="703" height="321" alt="Screenshot 2026-06-05 181628" src="https://github.com/user-attachments/assets/f3de0ce6-4dc6-4a78-beae-cc1b5ca2865d" />
<img width="709" height="303" alt="Screenshot 2026-06-05 181646" src="https://github.com/user-attachments/assets/a435a448-4d78-4dad-9722-13d082222a22" />


**Key features:**
- Facebook Ads connected via OAuth token + partner connector
- Google Ads and Google Analytics connected via native Looker Studio connectors
- Combined view: spend, ROAS, CTR, CPM, sessions, conversions
- Auto-refreshing — no manual exports needed

**Screenshots**

| Looker Studio Dashboard |
|---|---|
<img width="1366" height="920" alt="6" src="https://github.com/user-attachments/assets/65dbe30f-32ea-4be4-957a-9f55536f723e" />


**Stack:** `Facebook Ads API` `Google Ads` `Google Analytics` `Looker Studio` `Data Connectors` `Google Sheets`

---

### 3. Upcoming & Delayed Payments Tracker

> *Merged and cleaned payment data from multiple sources using Apps Script — powering a management-ready Looker Studio report.*

**The problem:** Payment data came in from multiple spreadsheets with inconsistent formatting. Identifying overdue and upcoming payments required hours of manual checking every week.

**What I built:** An Apps Script solution that pulls from multiple data sources, deduplicates records, standardizes formats, flags upcoming and overdue payments, and loads everything into a clean tracker. A Looker Studio report gives management real-time payment status without touching a spreadsheet.

**Workflow Design**

<img width="701" height="288" alt="Screenshot 2026-06-05 181529" src="https://github.com/user-attachments/assets/f3134eb7-8cb5-4074-b276-a5319836ccc4" />

**Key features:**
- Multi-source data merge using Apps Script
- Automated cleaning: remove duplicates, fix formatting
- Upcoming vs. delayed payment flags with date logic
- Looker Studio report with payment status, amounts, and timelines

**Screenshots**

| Looker Studio Report |
|---|---|
<img width="1366" height="831" alt="4" src="https://github.com/user-attachments/assets/df24c832-5bf9-4c93-9b2a-ba067e51aedb" />

**Stack:** `Google Apps Script` `Google Sheets` `Looker Studio`

---

## 📂 More Projects

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

**What it does:** Sales closers and setters submit end-of-day data via Airtable Form. An automated Zapier integration (set up by the team) transfers submissions to Google Sheets. My role: daily data monitoring, cleaning, structuring cash collected, payments, and commissions — then building and maintaining the Looker Studio performance report.

**My role:** Data cleaning · monitoring · reporting

**Workflow**

<img width="695" height="309" alt="Screenshot 2026-06-05 181511" src="https://github.com/user-attachments/assets/f92b02cc-fb98-43a5-a1a4-871134b88d65" />


**Screenshot**

![Report]<img width="1366" height="831" alt="4" src="https://github.com/user-attachments/assets/f53952b7-07e7-4a59-acb0-96fcd89e2d06" />

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
