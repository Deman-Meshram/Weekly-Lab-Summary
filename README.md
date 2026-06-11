# Weekly Lab Summary — Automated Inventory Report

> Automated weekly lab inventory summary with stock levels and expiry tracking delivered via Gmail every week.



![Status](https://img.shields.io/badge/Status-Complete-brightgreen)



---

## The Problem

Lab managers need a complete picture of inventory status every week — not just alerts when things go wrong. Without a weekly overview, it's hard to plan ahead, budget for supplies, catch slow-declining stock, or track expiring reagents before it becomes a problem.

Manual weekly inventory checks take 30-60 minutes and are often skipped.

---

## The Solution

Weekly Lab Summary automatically pulls all inventory data from Airtable every week and delivers a complete, color-coded HTML report to Gmail — covering both stock levels and expiry status — so lab managers always have a full picture without any manual effort.

- Full inventory overview — every item, every week
- Summary counts — Total / Critical / Low / Healthy / Expired / Expiring Soon
- Stock Status + Expiry Status per item
- Zero manual effort — fully automated weekly delivery

---

## Time & Effort Saved

| Task | Manual | This Automation |
|---|---|---|
| Weekly inventory check | 30-60 mins/week | Zero — fully automatic |
| Checking expiry dates | Manual date checking | Auto-detected instantly |
| Creating status report | Manual spreadsheet | Auto-generated HTML |
| Sending to team | Manual email | Auto-delivered to Gmail |
| Tracking trends | Memory/notes | Weekly email history |

---

## Final Output

- ✅ Inventory Summary — Total / Critical / Low / Healthy / Expired / Expiring Soon
- ✅ Complete color-coded table — Stock Status + Expiry Status per item
- ✅ RED for CRITICAL/EXPIRED, ORANGE for LOW/EXPIRING SOON, GREEN for GOOD/VALID
- ✅ Expiry Alerts section — expired and expiring soon items with dates
- ✅ Professional dark header HTML Gmail report
- ✅ Delivered automatically every week

---

## What It Does

Automatically generates a complete weekly lab inventory summary from Airtable and delivers a formatted HTML report via Gmail every week.

- **Weekly automated report** — runs every week automatically
- **Inventory Summary** — Total / Critical / Low / Healthy / Expired / Expiring Soon
- **Full inventory overview** — all items, stock levels, status
- **Expiry tracking** — VALID / EXPIRING SOON / EXPIRED per item
- **Color-coded status** — GOOD / LOW / CRITICAL instantly visible
- **Expiry alerts** — expired and expiring soon items listed with dates
- **Gmail HTML delivery** — professional formatted email report

---

## Tech Stack

| Layer | Tool |
|---|---|
| Automation | n8n workflow |
| Database | Airtable |
| Email | Gmail HTML |

---

## Architecture

```
Weekly scheduled trigger (n8n)
        ↓
Airtable fetches all inventory items
        ↓
JavaScript calculates summary counts
        ↓
HTML report generated with full table
        ↓
Expiry alerts section added
        ↓
Gmail sends weekly summary email
```

---

## Difference vs Lab Inventory Refill & Expiry Alert

| Feature | Lab Inventory Refill & Expiry Alert | Weekly Lab Summary |
|---|---|---|
| Trigger | Daily | Weekly |
| Scope | Only problem items | All items |
| Summary | Critical + Low + Expired + Expiring Soon | Total + all counts |
| Purpose | Urgent alerts | Full weekly overview |

---

## Technical Notes

- JavaScript node calculates all status counts
- Color coding: RED (#ff0000) CRITICAL/EXPIRED, ORANGE (#ff8c00) LOW/EXPIRING SOON, GREEN (#008000) GOOD/VALID
- Expiry Status formula in Airtable — auto-calculated daily
- Consistent dark header styling with Lab Inventory system

---

*Built by Deman Meshram | BSc Biotechnology + AI Automation*
