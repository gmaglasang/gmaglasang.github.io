# LinkedIn Job Search CRM

A self-contained, browser-based CRM built to manage a high-volume job search — no backend, no database, no installation required. Just open the HTML file and go.

![Demo](https://img.shields.io/badge/Demo-Live-blue) ![HTML](https://img.shields.io/badge/Built%20With-HTML%2FJS%2FCSS-orange) ![No Backend](https://img.shields.io/badge/Backend-None-green)

## 🔗 Live Demo

[**Open the demo →**](https://gmaglasang.github.io/App_Build/linkedin-crm/)

---

## Why I Built This

When you're running a serious job search — hundreds of LinkedIn messages, connections, and applications — spreadsheets fall apart fast. I needed something that felt like a real CRM: filterable, sortable, with status tracking and notes. So I built one.

No frameworks, no npm install, no cloud subscription. Just a single HTML file that runs in any browser.

---

## Features

**Messages Tab**
- Track every LinkedIn conversation with status tags: New, Replied, Hot, Interview, Passed, Ghosted, Archive
- Filter by status, search by name or subject
- Add notes per conversation
- Dashboard cards showing live counts for each stage

**Connections Tab**
- Browse and search your full LinkedIn connection list
- Sortable by name, company, title, or connection date
- Add new connections manually

**Applications Tab**
- Log every job application with date, company, and title
- Searchable and sortable
- Export everything to Excel with one click

**AI Follow-up Assistant** *(optional)*
- Plugs into your own API key (Google Gemini is free — no credit card needed)
- Generates follow-up messages, drafts replies, and assesses opportunity quality
- Supports Gemini, Anthropic, and Groq

**Data Portability**
- Import from a LinkedIn data export (messages.json, connections.csv, applications.csv)
- Export to Excel at any time
- All data stored locally in your browser (localStorage) — nothing leaves your machine

---

## How to Use

1. Download `index.html`
2. Open it in any browser
3. Add your data manually, or import from a LinkedIn export
4. Optionally set an AI API key in the top-right corner for follow-up suggestions

---

## Tech Stack

| Layer | Choice |
|---|---|
| UI | Vanilla HTML + CSS (no framework) |
| Logic | Vanilla JavaScript |
| Styling | Custom design system (CSS variables) |
| Fonts | Outfit + JetBrains Mono (Google Fonts) |
| Excel Export | SheetJS (CDN) |
| AI | Gemini / Anthropic / Groq API (user-supplied key) |
| Storage | localStorage (all local, nothing sent to a server) |

---

## Privacy

This demo uses entirely fictional sample data. No real names, messages, or personal information are included. When you use this tool yourself, all your data stays in your browser — it is never transmitted anywhere.

---

## Project Structure

```
App_Build/
  linkedin-crm/
    index.html    ← the entire app (single file)
    README.md     ← this file
```

---

*Built by [Guilbert Maglasang](https://github.com/gmaglasang) · Part of my portfolio at [gmaglasang.github.io](https://gmaglasang.github.io)*
