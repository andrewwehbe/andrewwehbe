# Andrew Wehbe

Software engineer. I build production web apps end to end: auth, payments, data pipelines, and the boring reliability work in between.

## Highlights

- **[txn-anomaly](https://github.com/andrewwehbe/txn-anomaly)** - explainable transaction anomaly detection: plain-English rule detectors plus IsolationForest under a gating policy. 91.2% recall with a ~30x smaller review queue on PaySim, with a leakage-hygiene writeup.
- **[FocusCam](https://github.com/andrewwehbe/FocusCam)** - on-device computer vision study companion. MediaPipe object and face detection fused in a Web Worker, with a hysteresis state machine to kill false positives.
- **[coaching](https://github.com/andrewwehbe/coaching)** - production fitness-coaching PWA with ~50 paying users. Clients log workouts on their phone; a nightly signals engine detects plateaus, fatigue and RIR drift, then drafts weekly coach notes. Next.js 16 + Supabase, 446 tests.
- **[client-progress-hub](https://github.com/andrewwehbe/client-progress-hub)** - deterministic strength-training analysis engine. FastAPI + Supabase + Google Sheets sync, classifies sessions (plateau, fatigue, RIR drift) and writes recommendations back.

Also in production, in private repos (happy to walk through either):

- **Medworx** - a provider-network SaaS designed, built and delivered end to end for a law firm (275 commits, hosted on the client's GitHub). TanStack Start on Cloudflare Workers, Stripe seat-based billing with verified webhooks, spreadsheet import pipeline, PWA, Playwright e2e.
- An agentic daily planner built on Claude with 38 tools and 600+ tests.

## Contact

andrewwehbe15@gmail.com
