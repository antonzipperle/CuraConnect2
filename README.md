# CuraConnect

**A platform connecting seniors with young helpers for everyday tasks**

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Express](https://img.shields.io/badge/Express-4.x-000000?logo=express&logoColor=white)](https://expressjs.com)
[![SQLite](https://img.shields.io/badge/SQLite-3-003B57?logo=sqlite&logoColor=white)](https://sqlite.org)
[![Gemini](https://img.shields.io/badge/Gemini_AI-2.0_Flash-4285F4?logo=google&logoColor=white)](https://ai.google.dev)
[![Tailwind](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

*Developed for [Jugend Gründet 2025/26](https://www.jugend-gruendet.de/) — ranked **31st out of ~1,500 teams***

</div>

---

## The Idea

Germany has over 5.7 million people in need of care, most of them living at home. They need help with everyday things — carrying groceries, setting up a router, mowing the lawn — but professional services are expensive and inflexible, and family isn't always around.

At the same time, millions of students and young people want to earn money on their own schedule, without committing to fixed shifts or long-term contracts.

CuraConnect bridges the gap. Seniors post small tasks. Young people nearby apply, show up, and get paid. Simple, local, human.

---

## Background

CuraConnect was developed for **Jugend Gründet 2026**, one of Germany's largest student entrepreneurship competitions (~1,500 teams). The business plan scored **1,549 / 2,000 points**, placing the team in the top tier of the first phase.

The concept was developed by a five-person team from **Hebel-Gymnasium Schwetzingen** (Team ID: 58130).

This website is a **prototype**, vibecoded by me in [Google AI Studio](https://aistudio.google.com/) to visualise what CuraConnect could look like as a real product in the future. It's a tangible way to show the idea, make it clickable, and bring the business plan to life beyond a PDF.

---

## How It Works

**For seniors:** You log in, describe what you need help with (by typing, or just talking to the built-in AI assistant), pick a time and location, and post your request. When a young helper applies, you see their profile and rating before deciding. Once the job is done and you confirm it, payment is released automatically.

**For students:** You browse open tasks near you, filter by category (garden, household, tech, shopping), and apply with one tap. Once you're selected and complete the job, you get paid — and earn CuraCoins, a loyalty currency redeemable for local vouchers like coffee or cinema tickets.

**Trust and safety** are built in throughout: ratings after every job, an escrow-style payment system so money is only released on confirmation, and CuraCare — a basic insurance layer active on every booking.

---

## What's in the App

- Landing page and full registration / login flow with role selection (senior or helper)
- Senior dashboard for posting tasks, managing applicants, and tracking payments
- AI assistant that lets seniors describe a task by voice or text — it fills out the form for them
- Student dashboard with a filterable job feed, active job tracker, and earnings history
- Wallet with CuraCoin balance, reward redemption, and transaction history
- User profiles with ratings, reviews, and editable bios
- Payment overview with escrow status per job

---

## Business Model

CuraConnect takes a **10% fee** on each completed job. On top of that, seniors can subscribe to **Cura+** (€60/year) for priority matching and no ads, and local businesses can place ads in the app. Based on projected year-3 numbers, the platform is designed to be self-sustaining at moderate scale.

---

## Team

**Anton Zipperle · Lena Goschmann · Teresa Schulz · Atakan Tink · Nicolas Stefanski**  
Hebel-Gymnasium Schwetzingen — Jugend Gründet 2026

View the app in Render: https://curaconnect-dma9.onrender.com

---

## Context

CuraConnect was originally built for **Jugend Gründet 2025/26**, a national entrepreneurship competition. The prototype placed **31st out of approximately 1,500 teams**.

This repository is the refactored version: components split from a monolithic 2,000-line file, a persistent SQLite backend added, and the Gemini integration moved server-side to eliminate API key exposure in the browser.

---

## Vibe-Coded with:
<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />



## License

MIT
