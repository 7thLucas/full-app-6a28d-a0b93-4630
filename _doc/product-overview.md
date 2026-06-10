# Product Overview

## Product Name
**CaféAI** *(working title — free AI access platform for café customers)*

## Tagline
> "Order a coffee. Unlock AI — for 5 hours."

---

## Problem Statement

Indonesia adalah salah satu adopter AI terbesar di dunia. Banyak orang melakukan WFC (Work From Café) atau mengerjakan tugas kuliah di kafe karena ada wifi gratis yang kencang dan suasana kerja yang nyaman. Masalahnya, AI berlangganan itu mahal — mahasiswa dan remote worker butuh akses AI tapi tidak mau bayar subscription bulanan. Solusinya: cukup beli kopi, dapat kode unik dari struk, dan langsung akses AI unlimited selama 5 jam. Produktivitas maksimal dengan harga secangkir kopi.

---

## What It Is
CaféAI is a café-integrated, session-based AI access platform. When a customer purchases any item at a participating café and receives their receipt, they get a unique, auto-generated alphanumeric code printed on the receipt. They enter that code on the CaféAI web platform and instantly gain **unlimited AI chat access for 5 hours** — with no account required.

The platform includes:
- A **chat interface** (similar to ChatGPT / Claude) for end-users
- An **API connectivity layer** so café operators or power users can connect the AI to their own agents or workflows

---

## Target Users

### Primary — Café Walk-in Customers
- **WFC (Work From Café) workers**: remote professionals, freelancers, and hybrid workers who camp in cafés for productive sessions
- **College students**: undergraduates and postgraduates writing assignments, theses, or studying — the classic "library alternative" demographic
- Age range: ~18–35
- Tech-comfortable; already familiar with AI tools like ChatGPT, Claude, Gemini

### Secondary — Café Operators
- Independent cafés and small café chains in Indonesia
- Looking to differentiate their venue and increase dwell time / transaction value
- Receive a simple dashboard or API key to configure their AI offering

---

## Core Value Proposition

| For customers | For café operators |
|---|---|
| Free, high-quality AI access tied to a real purchase | A compelling, low-cost loyalty differentiator |
| No account sign-up — just a code | **Drives new foot traffic** — people actively choose "the café with AI" when deciding where to work or study |
| 5-hour unlimited window fits a WFC/study session perfectly | Drives higher ticket sizes (purchase = AI unlock) |
| Familiar ChatGPT-style interface | Increases dwell time — AI workers stay longer and order more |
| Completes real work (writing, coding, research) for the price of a coffee | Simple integration — print code on existing receipt printer; no hardware investment |

---

## How It Works (User Flow)

1. **Order & Pay** — Customer buys any item at the café (coffee, food, etc.)
2. **Get the Code** — A unique, auto-generated code appears on the printed receipt
3. **Go to Platform** — Customer visits the CaféAI web URL (or scans a QR code on the table)
4. **Enter Code** — Code is validated; a 5-hour session timer starts
5. **Chat** — Unlimited AI chat for the full session window
6. **Session Ends** — After 5 hours, the code expires; customer buys again to unlock more

---

## Key Features

### For End Users
- **Code-based access** — No sign-up, no password, no friction
- **5-hour unlimited session** — Timed from first activation
- **AI chat interface** — Clean, familiar chat UI (message bubbles, history within session, markdown rendering)
- **API connectivity** — Power users can connect the session token to their own AI agent tools via API

### For Café Operators
- **Auto-generated unique codes** — Each purchase triggers a new code (via POS integration or manual QR/receipt system)
- **Café dashboard** — View usage stats, active sessions, code redemption rates
- **Branding** — Co-branded experience (café name + CaféAI)
- **Simple integration** — REST API or webhook to existing POS / receipt printer systems

---

## Positioning
- **Category**: B2B2C — café operators are the distribution channel; café customers are the end users
- **Geography**: Indonesia (initial launch), particularly urban/campus café scenes (Jakarta, Bandung, Yogyakarta, Surabaya)
- **Competitive angle**: Not competing with ChatGPT/Claude directly — CaféAI is an access layer on top of existing AI models, bundled with the physical café experience
- **Monetization model** (TBD / future): Subscription per café operator, revenue share, or freemium API tiers for power users

---

## Brand & Tone
- **Tone**: Friendly, energetic, slightly playful — speaks to students and young professionals
- **Visual direction**: Clean and modern; warm café aesthetic meets tech minimalism
- **Language**: Indonesian-first UX copy; English for API/developer-facing docs

---

## Scope (MVP)
1. Code generation engine (unique code per purchase, single-use, 5-hour TTL)
2. Code redemption & session management (validate code → start timer → track expiry)
3. AI chat interface (web-based, session-scoped)
4. Basic API endpoint for agent connectivity
5. Café operator integration hook (webhook / simple REST to generate codes from POS events)

---

## Strategic Principles
1. **Zero friction for customers** — Code in, chat immediately. No accounts.
2. **Café as the distribution channel** — The product lives inside the café experience, not outside it
3. **Session parity with a WFC visit** — 5 hours matches a typical productive café stay
4. **AI-agnostic architecture** — Backend can swap or aggregate AI providers (OpenAI, Anthropic, etc.) without changing the UX
5. **Indonesia-first, scale later** — Localized launch; expand to other SEA markets as café partnerships grow
