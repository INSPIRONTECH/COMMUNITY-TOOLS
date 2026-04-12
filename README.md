<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:010409,50:0d1117,100:00D2FF&height=200&section=header&text=COMMUNITY%20TOOLS&fontSize=44&fontColor=FFFFFF&fontAlignY=35&desc=Free%20NBR%20Compliance%20Tools%20for%20Bangladesh%20SMEs&descSize=16&descAlignY=55&animation=fadeIn" width="100%">

[![Live Tools](https://img.shields.io/badge/tools.inspiron.tech-LIVE-30D158?style=for-the-badge&logo=vercel&logoColor=white)](https://tools.inspiron.tech)
[![AI: Claude](https://img.shields.io/badge/AI-Anthropic%20Claude-cc785c?style=for-the-badge&logoColor=white)](https://anthropic.com)
[![Manager.io](https://img.shields.io/badge/Manager.io-Official%20Partner-FFD700?style=for-the-badge&logoColor=white)](https://manager.io/advisors)
[![License: MIT](https://img.shields.io/badge/License-MIT-00D2FF?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

---

### What This Is

Open-source, **Claude-powered compliance tools** built for Bangladeshi SMEs and tax practitioners. Every tool is free, bilingual (English/বাংলা), requires no login, and exports directly to [Manager.io](https://manager.io).

<div align="center">

`Free forever` · `No login required` · `Mobile-first` · `Bilingual EN/BN` · `Manager.io CSV export` · `AI-powered Q&A`

</div>

---

### 🛠️ Live Tools

<table>
<tr>
<td width="100%" valign="top">

#### 📅 [TAX-CALENDAR-BD](./TAX-CALENDAR-BD/) — [Live →](https://tools.inspiron.tech)

The definitive NBR compliance calendar for FY2025-26. Built at **0.1% precision** against official NBR circulars.

| Feature | Detail |
|---|---|
| **Deadlines** | VAT (Mushak-9.1), Income Tax, TDS (Form 108), VDS, Advance Tax |
| **AI Q&A** | Ask any NBR tax question — powered by Anthropic Claude |
| **Penalty Calculator** | Official Section 85(f) VAT penalty + Income Tax Act 2023 formula |
| **Manager.io Export** | One-click CSV → Journal Entries with pre-mapped tax accounts |
| **Business Types** | Trading · Manufacturing · Service · Sole Proprietor · Limited Company · Import/Export |

`HTML` `JavaScript` `Claude API` `Vercel Serverless` · **Self-contained — zero build step**

</td>
</tr>
</table>

---

### 🗺️ Roadmap

| # | Tool | Description | AI | Status |
|---|---|---|---|---|
| 1 | **[TAX-CALENDAR-BD](https://tools.inspiron.tech)** | NBR deadline calendar + penalty calc + Manager.io export | Claude | ![Live](https://img.shields.io/badge/Live-30D158?style=flat-square) |
| 2 | **MUSHAK-FORM-GENERATOR** | Auto-generate Mushak 6.3, 9.1, 16, 17, 18, 19 from transaction data | Claude | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 3 | **TIN-VALIDATOR-BD** | Validate Bangladesh TIN numbers against NBR format rules | — | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 4 | **INVOICE-COMPLIANCE-CHECK** | Scan invoices for missing VAT fields, BIN numbers, Mushak refs | Claude | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 5 | **COA-TEMPLATE-BD** | Ready-to-import Chart of Accounts templates for BD industries | — | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 6 | **AIT-CALCULATOR** | Advance Income Tax calculator with source-wise rate lookup | — | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 7 | **VDS-RATE-FINDER** | VDS rates by service category (SRO-based) | Claude | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 8 | **SALARY-SHEET-BD** | Payroll calculator with BD income tax slabs + provident fund | — | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 9 | **TRADE-LICENSE-RENEWAL** | Track trade license, IRC, ERC, BIDA renewal deadlines | — | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |
| 10 | **NBR-SRO-SEARCH** | Search & explain NBR SROs in plain language | Claude | ![Planned](https://img.shields.io/badge/Planned-00D2FF?style=flat-square) |

---

### 🤖 Claude Integration

<table>
<tr>
<td width="50%" valign="top">

#### 💬 Tax Q&A Engine
Natural language questions about Bangladesh NBR rules, deadlines, penalties, and Mushak forms — in English or বাংলা.

`Claude Haiku` `Serverless Proxy` `Real-time`

</td>
<td width="50%" valign="top">

#### 📋 Compliance Intelligence
Explains which forms apply to your business type. Interprets SROs. Guides filing procedures step-by-step.

`Context-aware` `Business-type filtering`

</td>
</tr>
</table>

> Built by a solo architect using Claude as the core engineering engine across every tool.
> [Read more about INSPIRON TECH's Claude-powered practice →](https://inspiron.tech)

---

### 🏗️ Architecture

```
COMMUNITY-TOOLS/
├── TAX-CALENDAR-BD/              ← Live at tools.inspiron.tech
│   ├── index.html                ← Self-contained SPA (HTML + CSS + JS)
│   ├── fonts/                    ← Neo Sans Pro + Li Ador Noirrit
│   ├── api/                      ← Vercel serverless — Claude Haiku proxy
│   └── vercel.json               ← Deployment config
├── [FUTURE-TOOL]/
│   └── ...
├── CONTRIBUTING.md
├── CHANGELOG.md
└── LICENSE (MIT)
```

Each tool is a **self-contained directory** — one HTML file, one optional API route. No build step. No framework. Just ship.

---

### 🛠️ Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Claude API](https://img.shields.io/badge/Claude-API-cc785c?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Manager.io](https://img.shields.io/badge/Manager.io-ERP-00D2FF?style=flat-square)
![Neo Sans Pro](https://img.shields.io/badge/Neo%20Sans%20Pro-Typography-FFD700?style=flat-square)

</div>

---

### 🤝 Why Open Source?

We believe every Bangladeshi SME should have access to free, accurate NBR compliance tooling — regardless of size or budget.

The expert **implementation** layer — Manager.io system builds, Chart of Accounts architecture, full VAT/TDS compliance automation — is where [INSPIRON TECH](https://inspiron.tech) delivers paid advisory services.

<div align="center">

**Open tools build trust. Trust builds clients.**

</div>

---

<div align="center">

[![Website](https://img.shields.io/badge/inspiron.tech-00D2FF?style=for-the-badge&logo=vercel&logoColor=white)](https://inspiron.tech)
[![Hire on Upwork](https://img.shields.io/badge/Hire%20on%20Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/cyberhasan)
[![Manager.io Profile](https://img.shields.io/badge/Manager.io%20Advisor-FFD700?style=for-the-badge&logoColor=white)](https://www.manager.io/advisors/profile?username=7478b418-50b1-70e2-549b-3a506372d7c0)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/8801719300849)
[![Email](https://img.shields.io/badge/hello@inspiron.tech-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@inspiron.tech)

---

**MD ABU HASAN** · Founder & Chief Architect, INSPIRON TECH

_"I do not install software. I architect logic."_

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:010409,50:0d1117,100:00D2FF&height=100&section=footer" width="100%">

</div>
