# hey, I'm Praniil 👋

> CS @ Purdue. I build things that should exist but don't.

I have a weird habit of seeing a broken system — medical billing, clinical trials, disaster response — and thinking "this is actually a software problem." Then I spend the next few weeks building something about it. Some of it ships. Some of it wins hackathons. Some of it just scratches the itch.

Right now I'm deep in healthcare AI (on purpose), game AI (for fun), and anything at the edge of "this probably shouldn't be a side project but here we are."

---

## what I actually build

**AI that fights for patients** — Medical bills are predatory by design. I've built two full-stack platforms ([BillClarity](https://github.com/PMN123/BillClarity) and [SaveSurance](https://github.com/PMN123/SaveSurance)) that parse uploaded bills with OCR, benchmark every CPT code against Medicare rates, flag billing errors with AI, and generate complete dispute packets — appeal letter, evidence table, phone script, all of it. The kind of thing a billing advocate charges $300/hr to do.

**Clinical ops tooling** — [RetainIQ](https://github.com/PMN123/Churnless) predicts which patients are most likely to drop out of clinical trials before they do. Deterministic risk scoring + Monte Carlo scenario modeling + AI coordinator summaries. Built for the coordinators who actually run the trials, not the executives who approve the budget.

**Your phone as a computer controller** — [HandsFree Office](https://github.com/PMN123/handsfree-office) lets you drive your desktop from your phone — cursor via tilt, clicks via tap, system actions via voice. Native iOS (Swift) + Android (Kotlin) clients talking to a cross-platform Python server over WebSocket. The v2 PRD is 40+ pages. I got a little carried away.

**Disaster response GIS** — FloodCut (for the [IEEE Response Quest Challenge](https://github.com/PMN123/ieee)) predicts which roads will get cut off before floodwaters overtop them, ranks which facilities lose access, and gives responders a timed action board instead of just a map. Because knowing water is rising is not the same as knowing what to do about it.

**Medical PII at scale** — A CLI tool that strips PHI from medical PDFs using PyMuPDF redaction + Tesseract OCR, targeting names, MRNs, DOBs, account numbers, and 20+ other identifier classes. Bulk-processes folders, outputs redaction reports, doesn't just black-box over text.

**Officers portal for a global org** — Full Next.js 15 / Supabase / Keycloak SSO system for the Sri Sathya Sai International Organization — manages officer assignments, dashboards, and reports across Center → Region → Country → Zone hierarchy. In production.

**Battlecode AI** — Compete annually in MIT's Battlecode tournament. This year's bot has dynamic cheese spending, ratnap target inversion, diagonal trap placement, and a handful of other combat exploits reverse-engineered from the spec. Sometimes the best strategy is just reading the rulebook more carefully than your opponents.

---

## stack

```
Languages    Python · TypeScript · Java · Swift · Kotlin · SQL
Frontend     React · Next.js 15 · Tailwind · Vite · shadcn/ui
Backend      FastAPI · Node/Express · Supabase · Deno Edge Functions
AI/ML        Gemini · AWS Textract + Comprehend Medical · RAG pipelines
Data         PostgreSQL · SQLite · Redis · pandas · scikit-learn
Infra        Firebase · Keycloak SSO · Docker (where needed)
Native       SwiftUI · Jetpack Compose (Android)
```

---

## elsewhere

[![LinkedIn](https://img.shields.io/badge/LinkedIn-praniil--nagaraj-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/praniilnagaraj)
[![Email](https://img.shields.io/badge/email-praniil.nagaraj@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:praniil.nagaraj@gmail.com)

---

## github stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=PMN123&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PMN123&layout=compact&theme=default&hide_border=true&langs_count=8" height="150"/>
</p>

---

*I'm always working on something. Ask me what it is.*
