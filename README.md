# 🔴 Financial Fraud Detection — Live Intelligence Dashboard

> **AI-powered end-to-end fraud detection system built with n8n automation, Google Sheets and Power BI**

---

## 🎯 Project Overview

Every day, hundreds of financial transactions happen — and hidden inside them are fraudsters. This project builds a fully automated fraud intelligence system that:

- ✅ Automatically scores every transaction against 12 fraud detection rules
- ✅ Flags HIGH, MEDIUM, LOW RISK transactions instantly
- ✅ Sends Gmail alerts for dangerous transactions
- ✅ Displays live results on an executive Power BI dashboard
- ✅ Updates in real time when new data enters Google Sheets

---

## 🏗️ System Architecture

Google Sheets (Transaction Data)
↓
n8n Automated Workflow
↓
12 Fraud Detection Rules Applied
↓
Risk Score + Fraud Status Updated
↓
Gmail Alerts Sent (HIGH RISK)
↓
Power BI Live Dashboard Refreshed

---

## 🛠️ Tools Used

| Tool | Role |
|---|---|
| Google Sheets | Live transaction database (55+ rows) |
| n8n | Automated fraud detection workflow |
| Power BI | Executive live dashboard (4 pages) |
| Gmail | Automated risk alerts |

---

## 📊 Dashboard Pages

### Page 1 — Executive Command Center
![Executive Command Center](Executive%20Command%20center.png)
> Leadership snapshot — KPI cards, fraud distribution donut chart, risk by location and merchant category

---

### Page 2 — Fraud Deep Dive
![Fraud Deep Dive](Fraud%20deep%20dive.png)
> Who are the suspects? Customer risk rankings, full transaction table with live slicer filtering

---

### Page 3 — Rule Engine & Automation
![Rule Engine](rule%20engine%20%26%20automation.png)
> How did AI catch them? Rules triggered frequency, risk score analysis, scatter plot of amount vs risk

---

### Page 4 — Live Automation Proof
![Live Automation](Live%20automation%20proof.png)
> n8n live monitoring — all HIGH RISK transactions, Gmail alerts triggered, real-time risk scores

---

## 🤖 n8n Workflow

![n8n Workflow](n8n.png)
> Automated workflow processes every transaction, applies 12 fraud detection rules and updates Google Sheets in real time

---

## 📧 Gmail Alerts

### High Risk Alert
![Gmail High Risk](Gmail%20alert%20high%20risk.png)

### Medium Risk Alert
![Gmail Medium Risk](Gmail%20alert%20medium%20risk.png)

---

## 📋 Google Sheet Data

![Google Sheet](Google%20sheet.png)
> Live transaction database — automatically updated by n8n with Risk_Score, Fraud_Status and Rules_Triggered columns

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Transactions | 55 |
| HIGH RISK Flagged | 14 |
| MEDIUM RISK | 15 |
| LOW RISK | 11 |
| Total Amount Analyzed | ₹17,82,105 |
| HIGH RISK Exposure | ₹10,33,500 |
| Average Risk Score | 4.86 |
| Most Triggered Rule | R1: High Value |

---

## 🚨 Fraud Detection Rules

| Rule | Description |
|---|---|
| R1: HighValue | Transaction amount exceeds threshold |
| R2: RoundAmount | Suspiciously round number amounts |
| R4: VelocityBreach | Too many transactions in short time |
| R5: MulePattern | Mule account behavior detected |
| R6: OffHours | Transaction at unusual hours |
| R7: DormantSpike | Sudden activity on dormant account |
| R8: FirstHighVal | First transaction is very high value |
| R9: ForeignLoc | Foreign location transaction |
| R11: UPIAbuse | UPI payment abuse pattern |
| R12: CrossBorder | Cross border transaction flag |

---

## 🔄 How Live Refresh Works

1. Person 1 adds new transactions to Google Sheets
2. Person 2 runs n8n workflow
3. n8n scores transactions and updates sheet
4. Power BI → Home → Refresh
5. Dashboard updates instantly across all 4 pages

---

## Author

Khushi Lathwal
**Chitkara University — MBA Applied Finance**


---

## 📁 Repository Files

| File | Description |
|---|---|
| fraud_detection_dashboard.pbix | Power BI dashboard file |
| Executive Command center.png | Dashboard Page 1 screenshot |
| Fraud deep dive.png | Dashboard Page 2 screenshot |
| rule engine & automation.png | Dashboard Page 3 screenshot |
| Live automation proof.png | Dashboard Page 4 screenshot |
| n8n.png | n8n workflow screenshot |
| Gmail alert high risk.png | High risk Gmail alert |
| Gmail alert medium risk.png | Medium risk Gmail alert |
