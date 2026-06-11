# Weekly Lab Summary — Automated Inventory Report

> Automated weekly lab inventory summary delivered via Gmail every week.



![Status](https://img.shields.io/badge/Status-Complete-brightgreen)



---

## The Problem

Lab managers need a complete picture of inventory status every week — not just alerts when things go wrong. Without a weekly overview, it's hard to plan ahead, budget for supplies, or catch slow-declining stock before it becomes critical.

Manual weekly inventory checks take 30-60 minutes and are often skipped.

---

## The Solution

Weekly Lab Summary automatically pulls all inventory data from Airtable every week and delivers a complete, color-coded HTML report to Gmail — so lab managers always have a full picture without any manual effort.

- Full inventory overview — every item, every week
- Summary counts — Total / Critical / Low / Healthy at a glance
- Color-coded status — instant visual identification
- Zero manual effort — fully automated weekly delivery

---

## Time & Effort Saved

| Task | Manual | This Automation |
|---|---|---|
| Weekly inventory check | 30-60 mins/week | Zero — fully automatic |
| Creating status report | Manual spreadsheet | Auto-generated HTML |
| Sending to team | Manual email | Auto-delivered to Gmail |
| Tracking trends | Memory/notes | Weekly email history |

---

## Final Output

- ✅ Inventory Summary — Total / Critical / Low / Healthy count
- ✅ Complete color-coded table — all items with status
- ✅ RED for CRITICAL, ORANGE for LOW, GREEN for GOOD
- ✅ Professional dark header HTML Gmail report
- ✅ Delivered automatically every week

---

## What It Does

Automatically generates a complete weekly lab inventory summary from Airtable and delivers a formatted HTML report via Gmail every week.

- **Weekly automated report** — runs every week automatically
- **Inventory Summary** — Total / Critical / Low / Healthy count
- **Full inventory overview** — all items, stock levels, status
- **Color-coded status** — GOOD / LOW / CRITICAL instantly visible
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
Gmail sends weekly summary email
```

---

## Difference vs Lab Inventory Alert

| Feature | Lab Inventory Alert | Weekly Lab Summary |
|---|---|---|
| Trigger | Daily | Weekly |
| Scope | Only LOW/CRITICAL items | All items |
| Summary | Critical + Low count | Total + Critical + Low + Healthy |
| Purpose | Urgent refill alerts | Full inventory overview |

---

## Technical Notes

- JavaScript node calculates CRITICAL / LOW / GOOD counts
- Color coding: RED (#ff0000) CRITICAL, ORANGE (#ff8c00) LOW, GREEN (#008000) GOOD
- Consistent dark header styling with Lab Inventory Alert

---

*Built by Deman Meshram | BSc Biotechnology + AI Automation*
