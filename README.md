# Scrub & Squish — Detailing Manager

A single-file business-management app for an auto-detailing shop. No backend, no build step — everything runs in the browser and saves to `localStorage`.

**Live app:** https://jponsky2.github.io/detailing-manager/
**Public booking page:** https://jponsky2.github.io/detailing-manager/#book

## Features

- **Dashboard** — month selector with revenue, profit, expenses, customer/service/add-on counts, and today's schedule
- **Customers** — searchable CRM with contact info, address, vehicle, recurring plans, total spend, visit count, and appointment history
- **Schedule** — month calendar with booked-revenue/appointment totals and per-day appointment dots
- **Services & Add-ons** — full price catalog (Full Detail + Basic Wash tiers per vehicle size)
- **Expenses** — logged and rolled into monthly profit
- **Goals** — monthly revenue goal with progress tracking
- **24/7 Booking Link** — branded public self-booking page that drops appointments straight onto the schedule
- **Reminders** — appointment reminders with a due-soon badge
- **Invoices/Receipts** — auto-numbered, printable (Save as PDF)
- **Backup** — export/import all data as JSON

## Usage

Open `index.html` in any modern browser. All data is stored locally in the browser.

## Tech

Plain HTML, CSS, and vanilla JavaScript in one file. No dependencies.
