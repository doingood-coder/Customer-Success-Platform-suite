<div align="center">

# 🎯 Customer Success Platform Suite

### Interactive simulations of Gainsight, Totango & ChurnZero — built in a single HTML file

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge)](.)
[![Single File](https://img.shields.io/badge/Single-File-blueviolet?style=for-the-badge)](.)
[![Portfolio](https://img.shields.io/badge/Purpose-Portfolio%20%2F%20Demo-orange?style=for-the-badge)](.)

<br/>

> A fully interactive, zero-dependency frontend simulation of three leading Customer Success platforms — **Gainsight**, **Totango**, and **ChurnZero** — all inside one self-contained HTML file. No frameworks, no build tools, no server required.

<br/>

[![View Live Demo](https://img.shields.io/badge/▶%20View%20Live%20Demo-0a1628?style=for-the-badge&logoColor=white)](.)
[![Download HTML](https://img.shields.io/badge/⬇%20Download%20HTML-1a6bff?style=for-the-badge&logoColor=white)](./DOC-20260325-WA0008._1774425148861.html)

</div>

---

## 📸 Platforms at a Glance

| | Gainsight | Totango | ChurnZero |
|---|---|---|---|
| **Theme** | Navy · Blue · Teal | Deep Purple · Violet | Dark Teal · Pink |
| **Focus** | Advanced analytics & automation | Flexible segmentation & campaigns | Real-time churn prevention |
| **Retention Rate** | 92% | 91% | 91% |
| **Churn Rate** | — | 7% | 9% |
| **Unique Feature** | AI Playbooks & Health Weights | Modular Touchpoints | Real-time Alert Engine |

---

## 🚀 Getting Started

No installation. No server. No dependencies.

```bash
# 1. Clone the repo
git clone https://github.com/your-username/cs-platform-suite.git

# 2. Open the file in your browser
open DOC-20260325-WA0008._1774425148861.html
```

Or simply **download the HTML file** and double-click it. That's it.

---

## ✨ Features

### 🔵 Gainsight — Customer Success & Retention Platform

<details>
<summary><strong>Click to expand Gainsight modules</strong></summary>

| Module | Description |
|---|---|
| 📊 **Dashboard** | KPIs, health score overview, churn risk summary |
| 👥 **Customers** | Searchable & filterable customer list with health scores |
| ❤️ **Health Scoring** | Configurable weights for login, feature usage, support, engagement |
| 🎯 **Playbooks** | Automated recovery, renewal, onboarding & upsell playbooks |
| 📣 **Campaigns** | Email campaigns with step-by-step workflows |
| 📈 **Reports** | Churn analysis, engagement trends, AI prediction accuracy |
| ⚙️ **Settings** | Health weights, playbook triggers, user roles, notifications |

**Key Stats:** `92% Retention` · `−12% Churn Reduction` · `+18% Engagement Increase` · `87% AI Precision`

</details>

---

### 🟣 Totango — Flexible Customer Success Platform

<details>
<summary><strong>Click to expand Totango modules</strong></summary>

| Module | Description |
|---|---|
| 📊 **Dashboard** | Customer health overview with engagement and churn rate KPIs |
| 👥 **Customers** | Full customer directory with lifecycle stage filters |
| ❤️ **Health Tracking** | Interactive health score calculator with weighted parameters |
| 🗂️ **Segments** | Dynamic customer segments with criteria builder and action plans |
| 📣 **Campaigns** | Re-engagement, onboarding, renewal, and upsell campaigns |
| ⚙️ **Settings** | Segment rules, health thresholds, campaign triggers, user roles |

**Key Stats:** `640 Customers` · `74% Engagement Rate` · `7% Churn Rate` · `91% Retention`

</details>

---

### 🔴 ChurnZero — Real-Time Churn Prevention Platform

<details>
<summary><strong>Click to expand ChurnZero modules</strong></summary>

| Module | Description |
|---|---|
| 📊 **Dashboard** | Live churn risk signals and customer health overview |
| 👥 **Customers** | Searchable customer profiles with lifecycle stage and CSM info |
| 🚨 **Alerts** | Real-time alert engine — high churn risk, low login, renewal at risk |
| 🤝 **Engagement** | Customer touchpoint and activity tracking |
| 📣 **Campaigns** | Churn prevention, onboarding accelerator, renewal, upsell campaigns |
| 📈 **Reports** | Retention trends, churn breakdown, segment performance |
| ⚙️ **Settings** | Alert triggers, campaign rules, user roles, Slack & email notifications |

**Key Stats:** `720 Customers` · `160 At Risk` · `420 Healthy` · `9% Churn Rate` · `91% Retention`

</details>

---

## 🧭 Navigation

The app has a **fixed top navigation bar** that lets you switch between all three platforms instantly.

```
[ Platform ] [ 1 · Gainsight ] [ 2 · Totango ] [ 3 · ChurnZero ]   Page 1 of 3
```

Each platform has its own **sticky module navigation bar** for switching between sections:

- Gainsight → `Dashboard` `Customers` `Health` `Playbooks` `Campaigns` `Reports` `Settings`
- Totango → `Dashboard` `Customers` `Health` `Segments` `Campaigns` `Settings`
- ChurnZero → `Dashboard` `Customers` `Alerts` `Engagement` `Campaigns` `Reports` `Settings`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Markup** | HTML5 (semantic, scoped IDs per platform) |
| **Styling** | Pure CSS3 — CSS Variables, Flexbox, Grid, sticky/fixed positioning |
| **Logic** | Vanilla JavaScript — namespaced functions (`gs_`, `tt_`, `cz_`) |
| **Font** | [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts |
| **Dependencies** | **None** |

---

## 🗂️ File Structure

```
cs-platform-suite/
└── DOC-20260325-WA0008._1774425148861.html   ← everything is here
```

All CSS, JavaScript, and HTML are embedded in a single file. CSS is **scoped by section ID** (`#gs-section`, `#tt-section`, `#cz-section`) to prevent any style bleeding between platforms.

---

## 🎨 Design System

| Platform | Primary | Accent | Background |
|---|---|---|---|
| **Gainsight** | `#1a6bff` Blue | `#00c8b4` Teal | `#0a1628` Navy |
| **Totango** | `#6c3fc5` Purple | `#8b5cf6` Violet | `#1a0a40` Dark Purple |
| **ChurnZero** | `#e91e8c` Pink | `#26bfb8` Teal | `#091e26` Dark Teal |

---

## 📋 Interactive Elements

- ✅ **Health score sliders** — drag to recalculate scores live (Gainsight & Totango)
- ✅ **Playbook step tracker** — click steps to mark complete with progress bar
- ✅ **Customer search & filter** — real-time filtering by name, plan, and lifecycle stage
- ✅ **Alert selector** — click alerts to see conditions and recommended actions
- ✅ **Campaign selector** — browse campaigns with step-by-step playbooks
- ✅ **Settings toggles** — toggle notifications and system configuration on/off
- ✅ **Platform switcher** — switch between all three platforms from any section
- ✅ **Module navigation** — sticky nav bar per platform with instant panel switching

---

## 📌 Use Cases

- 🎓 **Learning** — Understand how enterprise CS platforms are structured
- 💼 **Portfolio** — Showcase frontend skills without a backend
- 🖥️ **Demos** — Present CS platform concepts to stakeholders
- 🔍 **Research** — Compare feature sets of Gainsight, Totango, and ChurnZero

---

## ⚠️ Disclaimer

> This project is a **frontend simulation** created for portfolio and demonstration purposes only. It is **not affiliated with, endorsed by, or connected to** Gainsight, Totango, or ChurnZero in any way. All data shown is fictional and for illustrative purposes only.

---

## 📄 License

This project is open for personal and educational use. Please do not redistribute commercially without attribution.

---

<div align="center">

Made with ❤️ using pure HTML, CSS & JavaScript

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](.)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](.)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](.)

</div>
