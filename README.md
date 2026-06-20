<div align="center">

<img src="brainboxe-logo.svg" alt="BrainBoxe" width="300" />

### AI delivered as **product**, not project.

Focused AI modules — packaged software you deploy, not models you babysit.

<br/>

[![Live Site](https://img.shields.io/badge/live-brainboxe.com-C5F82A?style=for-the-badge&labelColor=0A0C08)](https://brainboxe.com)
[![Studio](https://img.shields.io/badge/AI_Product_Studio-2026-0A0C08?style=for-the-badge&labelColor=C5F82A)](https://brainboxe.com)
[![Built with](https://img.shields.io/badge/built_with-HTML_·_Supabase_·_Cloudflare-0A0C08?style=for-the-badge)](https://brainboxe.com)

**[→ Visit brainboxe.com](https://www.brainboxe.com)**

</div>

---

## Our vision

Most "AI products" are still prototypes wearing a pricing page. Demos that dazzle, then fall apart the moment they meet real data, real users, real deadlines.

**BrainBoxe exists to change that.** We build AI as *product* — focused, packaged modules that work the first week, run the second, and earn their keep by the third. No twelve-week integration cycles. No babysitting a model. No magic, no demos.

Each module is a box of cognitive capability you can pick up and put to work — which is exactly what the name means. The long game: a catalog of these modules, each solving one real problem deeply, that together give teams outcomes instead of experiments.

> We don't sell potential. We ship modules that work.

---

## The catalog

### 🟢 DocuPulse — *Live*
**Legal document intelligence.** Extracts clauses, flags risk, and surfaces what matters in long contracts — without the analyst hours. Feed it a PDF or DOCX, get structured insight and risk flags back.

### 🟡 Buildra — *In build*
**A modular SaaS chassis.** Compose AI features into your product without rebuilding the boring scaffolding around them every time. Built for founders and builders who want to ship, not re-plumb.

*More modules are on the bench. The catalog grows through 2026.*

---

## How we build

Three rules behind every module we ship:

| Principle | What it means |
|-----------|---------------|
| **Narrow** | One job per module. Generalist AI fails in production — each module solves one well-scoped problem deeply, with the workflow already designed around it. |
| **Deployable** | It runs the day you buy it. Modules ship with the plumbing, prompts, and guardrails included. You connect data, it works. |
| **Honest** | No magic, no demos. We tell you what each module can and can't do, where it breaks, and which evals it passes. If it isn't ready, we won't sell it. |

---

## This repository

The BrainBoxe landing page — a single, self-contained site with a live product catalog you can manage from a built-in admin panel.

**Stack**
- **Frontend** — single-file `index.html`, no build step, glassmorphism UI (lime on near-black)
- **Backend** — [Supabase](https://supabase.com) (Postgres + Auth) with Row Level Security
- **Hosting** — [Cloudflare Pages](https://pages.cloudflare.com) on the global edge with automatic HTTPS
- **Admin** — password-gated panel to add, edit, and remove products; changes go live instantly for all visitors

**Features**
- ⚡ Loads instantly — one file, no framework, no bundler
- 🔐 Real auth — admin login verified server-side by Supabase, never exposed in source
- 🗂️ Live catalog — products stored in a real database, editable without redeploying
- 🎨 Distinct identity — custom lime/black glass design and neural-box logo
- 📱 Fully responsive — built mobile-first

---

## Run it locally

```bash
# clone
git clone https://github.com/Nion9/brainboxe.git
cd brainboxe

# open it — that's it, no build step
open index.html        # macOS
# or just double-click index.html
```

To connect your own backend, set your Supabase **Project URL** and **anon public key** near the top of the `<script>` block in `index.html`. Without keys it runs in a local demo mode.

## Deploy

The site is a static file — drop `index.html` onto any static host. We use **Cloudflare Pages**: drag the file into a Pages project, attach a custom domain, done. SSL is automatic.

---

## Connect

<div align="center">

**Built by [Nion](https://github.com/Nion9)** — solo founder, BrainBoxe

[![Website](https://img.shields.io/badge/brainboxe.com-C5F82A?style=for-the-badge&labelColor=0A0C08&logo=safari&logoColor=0A0C08)](https://brainboxe.com)
[![Email](https://img.shields.io/badge/Email-0A0C08?style=for-the-badge&logo=gmail&logoColor=C5F82A)](mailto:minhajulislamnion@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0C08?style=for-the-badge&logo=linkedin&logoColor=C5F82A)](https://linkedin.com/in/Nion007)
[![GitHub](https://img.shields.io/badge/GitHub-0A0C08?style=for-the-badge&logo=github&logoColor=C5F82A)](https://github.com/Nion9)

<br/>

*AI delivered as product, not project.*

© 2026 BrainBoxe

</div>
