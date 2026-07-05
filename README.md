# hey, i'm praniil

cs @ purdue. most of my projects start with something annoying me — a medical bill, a four-year plan spreadsheet, my own desk setup — and me deciding it's fixable with code. lately that's been a lot of healthcare stuff, some dev tooling, and whatever hackathon my friends drag me into.

---

## what i'm building right now

**CloudShare** — a vs code extension that puts claude in your editor for a flat monthly price, with real per-user token metering and hard budget ceilings underneath so nobody gets a surprise bill. building it with a friend. repo's private while we get it ready to ship, but this is where most of my commits are going these days.

**[BoilerPlanner](https://github.com/PMN123/BoilerPlanner)** — a purdue graduation planner that actually checks your plan against real degree requirements. pick any of ~445 majors/minors, it auto-builds a four-year schedule in prerequisite order, and if you drag a course somewhere illegal it immediately flags the broken prereq chain and offers a one-click fix. the backend is pure python stdlib, so it runs with one command.

**[FloodCut](https://github.com/PMN123/floodcut)** — my entry for the ieee response quest challenge 2026 (made it to phase 3). knowing a river is rising isn't the same as knowing what to do about it, so floodcut fuses live usgs gauges, nws forecasts, surveyed flood thresholds, and road graphs to predict which roads and hospitals lose access next — and turns that into a timed, ranked action board for emergency managers. fastapi + postgis backend, react + maplibre front end, one region replaying hurricane helene and one running live off real gauges.

**[handsfree-office](https://github.com/PMN123/handsfree-office-v2)** — control your computer from your phone: tilt to move the cursor, tap to click, voice for system actions. native ios client talking to a python server over websocket. this is the v2 rebuild — [v1 is here](https://github.com/PMN123/handsfree-office) with the android client too.

## healthcare ai

medical billing in the us is a mess and i keep building things to fight it.

**[BillClarity](https://github.com/UAgarwal7/BillClarity)** — upload a medical bill, it runs ocr, benchmarks every cpt code against medicare rates, flags likely billing errors, and generates a full dispute packet: appeal letter, evidence table, phone script. built at rockethacks 2026.

**[SaveSurance](https://github.com/UAgarwal7/SaveSurance)** — the insurance-side sibling of BillClarity, built at revolutionuc. same idea: turn "this bill looks wrong" into an actual, sendable dispute.

**[Churnless](https://github.com/UAgarwal7/Churnless)** — predicts which patients are likely to drop out of a clinical trial before they do, using deterministic risk scoring plus monte carlo scenario modeling, with ai-written summaries for the coordinators who actually run the trials.

also building a rag-based personal health chatbot (private for now) and an officers portal for a global nonprofit — next.js + supabase + keycloak sso, managing assignments and reports across a center → region → country → zone hierarchy. that one's in production.

## other stuff i'm proud of

**[artemis2-normative-modeling-n4](https://github.com/PMN123/artemis2-normative-modeling-n4)** — my entry for nasa's artemis ii human research data challenge. the problem: how do you do real statistics on a crew of four people? my answer: calibrate a normative model on a big terrestrial cohort (nhanes) and transfer it to real inspiration4 spaceflight biomarker data — empirical-bayes moderated t-tests, sign-flip permutation, gaussian-process recovery trajectories, the whole small-n toolkit. runs end to end with one command.

**[macos-live-wallpaper](https://github.com/PMN123/macos-live-wallpaper)** — i wanted video wallpapers on my mac and didn't want to pay for an electron app that eats 500mb of ram. so: native swift + appkit + avfoundation, lives in the menu bar, zero dependencies.

**battlecode** — i compete in mit's battlecode tournament every january. this year's bot had dynamic cheese spending, ratnap target inversion, and diagonal trap placement, most of which came from reading the game spec more carefully than our opponents did.

---

## stack

```
languages    python · typescript · java · swift · kotlin · sql
frontend     react · next.js · tailwind · vite
backend      fastapi · node/express · supabase · deno edge functions
ai/ml        claude api · gemini · aws textract + comprehend medical · rag
data         postgresql · sqlite · redis · pandas · scikit-learn · scipy
native       swiftui · appkit · jetpack compose
```

---

## find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-praniilnagaraj-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/praniilnagaraj)
[![Email](https://img.shields.io/badge/email-praniil.nagaraj@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:praniil.nagaraj@gmail.com)

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=PMN123&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PMN123&layout=compact&theme=default&hide_border=true&langs_count=8" height="150"/>
</p>

*always working on something. ask me what it is.*
