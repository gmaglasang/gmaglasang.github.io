# SaaS Metrics Dashboard – Power BI Demo

A browser-based Power BI-style analytics dashboard showcasing SaaS business metrics across revenue, customer health, and growth — built entirely in HTML/JS with no backend required.

![Demo](https://img.shields.io/badge/Demo-Live-blue) ![HTML](https://img.shields.io/badge/Built%20With-HTML%2FJS%2FCSS-orange) ![No Backend](https://img.shields.io/badge/Backend-None-green)

## 🔗 Live Demo

[**Open the dashboard →**](https://gmaglasang.github.io/App_Build/saas-metrics/demo.html)

---

## Why I Built This

Most Power BI portfolio pieces are screenshots. This is interactive. I wanted to show exactly how a SaaS executive dashboard looks and behaves — with real filters, live chart updates, and multi-page navigation — without requiring anyone to install Power BI Desktop or request workspace access.

---

## Screenshots

**Executive Overview** — MRR trends, active customer count, churn rate KPIs, and revenue by plan and industry
![Executive Overview](../../assets/saas-overview.png)

**Revenue Breakdown** — Year-over-year MRR vs. target with growth rate trends and country-level distribution
![Revenue Breakdown](../../assets/saas-revenue.png)

**Customer Health** — Active customer trends, churn by plan, top customers by MRR, and at-risk account identification
![Customer Health](../../assets/saas-health.png)

---

## Dashboard Pages

**Executive Overview**
- MRR trend line with monthly breakdowns
- Active customer count and churn rate KPIs
- Revenue split by plan type and industry segment

**Revenue Breakdown**
- Year-over-year MRR vs. target comparison
- Growth rate trend with country-level revenue distribution
- Interactive filtering by year, country, and plan

**Customer Health**
- Active customer trends over time
- Churn analysis segmented by plan
- Top customers by MRR
- At-risk account identification for proactive outreach

---

## Features

- **4 interactive filters** — Year, Country, Plan Type, Industry (all charts update live)
- **3 dashboard pages** — tabbed navigation mimicking Power BI report pages
- **KPI cards** — highlight metrics like Total Revenue YTD, Active Customers, MRR Growth
- **Chart.js visualizations** — line, bar, doughnut, and horizontal bar charts
- **Fully self-contained** — single HTML file, no installation, no login

---

## Tech Stack

| Layer | Choice |
|---|---|
| UI | Vanilla HTML + CSS (no framework) |
| Logic | Vanilla JavaScript |
| Charts | Chart.js 4.4 (CDN) |
| Styling | Power BI-inspired design system (CSS variables) |
| Storage | None — static demo data embedded in the file |

---

## Privacy

All data in this demo is entirely fictional. No real company, customer, or financial data is included.

---

## Project Structure

```
App_Build/
  saas-metrics/
    demo.html     ← the entire dashboard (single file)
    README.md     ← this file
```

---

*Built by [Guilbert Maglasang](https://github.com/gmaglasang) · Part of my portfolio at [gmaglasang.github.io](https://gmaglasang.github.io)*
