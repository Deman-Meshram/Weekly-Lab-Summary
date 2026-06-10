# Weekly Lab Summary — Automated Inventory Report

> Automated weekly lab inventory summary delivered via Gmail every week.



![Status](https://img.shields.io/badge/Status-Complete-brightgreen)



---

## What It Does

Automatically generates a complete weekly lab inventory summary from Airtable and delivers a formatted HTML report via Gmail every week.

- **Weekly automated report** — runs every week automatically
- **Full inventory overview** — all items, stock levels, status
- **GOOD / LOW / CRITICAL summary** — quick status overview
- **Gmail HTML delivery** — professional formatted email report
- **Consistent styling** — matches Lab Inventory Alert dark header style

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
n8n aggregates full inventory data
        ↓
HTML report generated with all items
        ↓
Gmail sends weekly summary email
```

---

## Key Features

- Weekly scheduled trigger
- Full inventory status report
- Color-coded GOOD / LOW / CRITICAL items
- Professional dark header HTML email
- Consistent styling with Lab Inventory Alert System

---

## Difference vs Lab Inventory Alert

| Feature | Lab Inventory Alert | Weekly Lab Summary |
|---|---|---|
| Trigger | Daily | Weekly |
| Scope | Only LOW/CRITICAL items | All items |
| Purpose | Urgent refill alerts | Full inventory overview |

---

*Built by Deman Meshram | BSc Biotechnology + AI Automation*
