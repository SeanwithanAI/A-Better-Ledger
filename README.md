<div align="center">

# A Better Ledger

**Budget and Planner: a private, single-file replacement for Monarch and Actual Budget**

![Version](https://img.shields.io/badge/version-2026--11--12%20mk7-15803D)
![Single file](https://img.shields.io/badge/single%20file-HTML-0B3D2E)
![No account needed](https://img.shields.io/badge/no%20sign--up-required-334155)
![PageVault ready](https://img.shields.io/badge/PageVault-ready-2563eb)

*by SeanwithanAI*

</div>

![Overview: income, spending, net and savings rate for the month, with top categories, recent transactions and account balances](docs/screenshots/overview.png)

---

## Overview

A Better Ledger tracks your accounts, transactions and monthly budget, and plans for retirement and future pay. Everything is in one HTML file: there's nothing to install, no subscription, and no third party ever holds your financial data.

It can bring in your history from **Actual Budget**, and export a file Actual can read back, so you're never locked in.

## Features

### Budgeting
| | |
|---|---|
| **Overview** | Income, spending, net and savings rate for the month, compared with last month. Includes a running spending chart, top categories, recent transactions and account balances. |
| **Transactions** | Every transaction in one list, with categories, notes and attachments (receipts, PDFs, photos). |
| **Cash flow** | Money in against money out, month by month. |
| **Spending** | Spending by category or group for the year, with monthly trends and a year-over-year comparison. |
| **Budget** | Monthly amounts per category, grouped (Bills, Everyday…). Fill empty months from your 3-month average, and save up for irregular bills. |
| **Recurring** | Scheduled transactions (rent, subscriptions, paychecks) added automatically when they come due. |
| **Accounts** | Checking, savings, credit cards with payment tracking, and off-budget accounts such as investments and loans. |

### Planning
| | |
|---|---|
| **Retirement** | Projects your savings to retirement age and tells you whether you're on track, and roughly how much more to invest if you're not. |
| **Future pay** | Plans upcoming paychecks and take-home pay for any US state (federal W-4, state income tax, paid leave, local tax, any retirement plan), and can feed expected income into the budget. |

### Also included
- **Import from Actual Budget**, and **export** a file Actual can import.
- **Backup and restore** to a single JSON file.
- **Day, Dark and Auto** themes. Works on phones, tablets and desktops.

## Screenshots

| Spending by category | Overview |
|---|---|
| ![Spending by category for the year, with Rent highlighted and a monthly chart](docs/screenshots/spending.png) | ![Monthly overview](docs/screenshots/overview.png) |

<sub>Screenshots use made-up example data.</sub>

## Getting started

**Option 1: open the file.** Download `A_Better_Ledger_<date>_<mk>_by_SeanwithanAI.html` and open it in any modern browser. Click **Import from Actual Budget** or **Start with an empty account**.

**Option 2: host it on PageVault (recommended).** Install it as an app in [PageVault](#hosting-on-pagevault) on your own server. Your ledger is then saved on your server, follows you to any device, and each family member gets their own private ledger.

## Where your data is stored

| Opened from… | Saved to | Status shown in the app |
|---|---|---|
| **PageVault** | Your own server, separately for each signed-in person. Nothing is kept in the browser. | *Saved to your server* |
| **Claude** | Your Claude account, with this browser as a backup | *Saved to your account* |
| **A local file** | This browser only | *Saved on this device only* |

When data lives in only one browser, the app reminds you every 7 days to download a backup.

**Conflict protection (PageVault):** if the ledger is open on two devices, an out-of-date screen can't overwrite newer data. It asks you to reload instead.

## Hosting on PageVault

PageVault watches this repository and installs new versions automatically (or with one tap). Each update keeps the app's link and everyone's saved data. Releasing a new version is just adding the new file here; see **Versioning** below.

## Versioning

Every release is a new file named with the release date, plus `mkN` when there's more than one release that day:

```
A_Better_Ledger_2026-11-12_mk7_by_SeanwithanAI.html
                └──date──┘ └mk┘
```

The same version appears in the app's sidebar and footer. Older files stay in the repo, so any version can be restored (PageVault: **Updates → Install this version**).

| Version | Notes |
|---|---|
| **2026-11-12 mk7** | Future pay works for every state: pick your state (all 50 + DC, 2026 brackets), state filing status, Head of household, W-4 Steps 2–4, Social Security wage cap and on/off switch, any retirement plan (pre-tax or Roth), state paid leave and local income tax. Minnesota keeps its exact paystub formula; saved PERA/MN settings carry over. |
| **2026-11-11 mk6** | Saves to the PageVault server (data and attachments) when hosted there, with no browser copy. Behaves as before everywhere else. |

---

<div align="center"><sub>A Better Ledger · Budget and Planner · by SeanwithanAI · private repository</sub></div>
