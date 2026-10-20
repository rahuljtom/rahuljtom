# Rahul Joseph Thomas

**Growth, Product Analytics & GTM Systems** · CS ’27 @ VIT Vellore  
`SQL` · `Python` · `Looker Studio` · `Sheets Modeling` · `Evaluated AI Workflows`

I use code, public market telemetry, and statistical rigor to figure out where products lose users or revenue, and build the workflows and experiments to test fixes.

---

### Featured Growth Case Study: Wispr Flow India

Public data only, no internal numbers; every figure traces to a numbers ledger and results are directional.

- **The gap:** Sensor Tower via TechCrunch puts India at **~14% of installs (#2 after the US)** but **~2% of in-app-purchase revenue** (`0.143×` global revenue per install). Wispr separately says India is its **#2 market by users and paying subscribers**.
- **Pricing as arithmetic, not cause:** localized list price (`₹320/mo` annual vs `$12/mo`) gives a `0.283` price index and a `0.504` residual (`0.22–1.22` across 12 scenarios). If a large share of India revenue bills outside the app stores (Wispr documents web Stripe billing; CRED/Zepto Pro trials are claimed in a browser), the residual passes `1.0` (`1.22` at 60% missed). That is a hypothesis reconciling the `2%` IAP share with the #2 claim, not a finding.
- **Review signals (`micro-F1 = 0.784`, `κ = 0.830` on a held-out gold split):** a PII-scrubbed Gemini tagging workflow on an interim sample of 321 Play reviews. Pricing/paywall themes appear in **26.9% of 1–2★ reviews vs 11.2% overall (2.4×)**; onboarding/permission-setup themes in **13.5% vs 4.4% (intervals overlap)**. Recent reviews, not India-specific.
- **Competition & experiments:** scored 10 rivals on 5 criteria: **Gboard (`13/15`)** is the leading free default; **Superflow (`11` across 4 known criteria, `11–14` possible; developer is a Bengaluru-registered company)** is the closest dedicated Android dictation rival. Power-sized 3 proposed India experiments (`1,376` to `3,788` users per arm), checked against `numbers_ledger.csv`. None has been run.

**Open:** [Looker Studio Dashboard ↗](https://lookerstudio.google.com/reporting/bdcc93a1-66f1-4f6b-9496-c69d8ba01035) · [10-Slide Deck ↗](https://docs.google.com/presentation/d/1itgf-Vjq8WL_pxCx-8aFIfCaeLe-iqgf/edit?usp=sharing) · [Repository & Ledger ↗](https://github.com/rahuljtom/wispr-flow-india-growth-study)

---

### AI & Data Systems

**[llm-inference-gateway](https://github.com/rahuljtom/llm-inference-gateway)**: OpenAI-compatible multi-provider gateway (FastAPI, Redis, PostgreSQL). **[Walkthrough ↗](https://www.loom.com/share/8916ae03dfa345b683c4e235d31c3eea)**

- Exact-match response caching and per-key usage logs.
- Configurable **cost / p95-latency routing policies** (based on configured estimates, not measured savings).
- **Team monthly budget reservations** on estimated spend.
- PostgreSQL token, latency and cost-estimate analytics.

---

**[LinkedIn](https://www.linkedin.com/in/rahuljosephthomas/)** · **[Portfolio](https://rahuljtom.github.io)** · **[rahuljtoms@gmail.com](mailto:rahuljtoms@gmail.com)**
