# Hi, I'm Erin 👋

High school developer building full-stack apps and AI-powered tools.
Interested in the intersection of engineering and biology.

---

## 🛠️ Tech Stack

**Languages:** Python, JavaScript, TypeScript, SQL, HTML/CSS

**Frontend:** React 18, Next.js 16, Tailwind CSS, Vite

**Backend & Database:** Firebase Firestore, Supabase (PostgreSQL), PL/pgSQL

**AI/ML:** Anthropic SDK (Claude API, Files API, count_tokens)

**Infrastructure:** Vercel, Git/GitHub, npm

---

## 📌 Projects

### AquaGuardian — Household Water Conservation App
**[Live App](https://aquaguardian-jet.vercel.app)**

[Figma Mockup](https://www.figma.com/make/kvGCCYO0eP6chZ3kGuN45s/Water-Consumption-Tracker-App?t=KOEDXRd0Zx7DMu3C-1)

A Progressive Web App that turns household water conservation into a
daily habit through a living companion whose health responds to real
usage.

Families log water activities (showers, laundry, sprinklers); a
5-stage water spirit evolves based on their conservation streak.
Real-time sync via Firestore means every family device sees the same
spirit health instantly. Includes a usage heatmap, bill estimator,
behavioral psychology insight cards, and an offline-capable PWA
install for iPhone.

**Tech:** React 18 · Vite · Firebase Firestore & Auth · Vercel · PWA

---

### Claude Document Analysis Tool
*AI-powered research assistant for large financial documents*

*2-person student team*

Financial analysts spend hours manually reading dense S-1 filings and
10-Ks. This tool automates that: supply a PDF and a question list and
Claude reads the document end-to-end and returns a structured answer
file saved to Dropbox.

My independent contributions included async concurrent batch processing
(`asyncio.gather()`), token-accurate pre-flight batching via
Anthropic's `count_tokens` API (replacing a flat page heuristic,
confirmed on Klarna F-1b), a three-phase run cost tracker, a Dropbox
OAuth2 integration layer, and a web scraping pipeline with CSV export.

**Tech:** Python · Anthropic SDK · asyncio · pypdf · Dropbox API

---

### Los Khangeles (Simulation City) — Financial Platform
**[Financial Platform](https://los-khangeles.vercel.app/)**

**[City Council Dashboard](https://los-khangeles.vercel.app/court)**

Full-stack web app powering the economy of a school-wide city
simulation involving an entire high school. Serves as the central bank
and ledger — every sale, wage, VC investment, and government loan flows
through it.

Supports three account tiers (individual, corporate, government) with
distinct permissions, seven transaction types, automatic balance updates
via PostgreSQL triggers, a government lending system with per-borrower
loan histories, and a read-only City Council oversight dashboard.

**Tech:** Next.js 16 · TypeScript · React · Tailwind CSS · Supabase ·
PostgreSQL · PL/pgSQL · Vercel

---

## 📚 Currently Learning
- Flask and backend web frameworks
- Deploying Python apps (Render, Railway)
- IoT integration (ESP32 + Firebase Realtime Database)

---

## Contact
erinpeyang@gmail.com · https://www.linkedin.com/in/erin-yang-a40750320
