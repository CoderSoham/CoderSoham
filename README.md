## Soham Boravke

Software Engineer at **Armor EDC**, Pune. I work on backend services and data
pipelines in the network and application security domain.

Most of what I build lives at the boundary between a system and the messy real
world it has to ingest — audio, market data, resumes, job postings, voice. That
boundary is where the interesting failures are, and it's most of what I find
worth writing about.

---

### What I'm working on

**Jarvis** *(private)* — a local-first voice assistant with a typed asyncio
event bus, wake-word detection, and a measured latency budget. End-of-speech to
transcript runs 770–890 ms at ~13% of one core idle. Currently wiring the
agentic brain and an MCP client.

**rolefit** *(private)* — a career diagnostic that answers the question every
résumé tool skips: not "does this résumé match this job," but "what should I be
applying for, and what do I learn next?" Ranks missing skills by how many
otherwise-qualified postings each one unlocks.

---

### Selected work

| | |
|---|---|
| **[NLP_FIR](https://github.com/CoderSoham/NLP_FIR)** | Emergency call triage — Whisper transcription with language auto-detect, zero-shot classification, NER, summarisation, and a generated FIR report. Runs CPU-only, no API keys. |
| **[FSD-Project](https://github.com/CoderSoham/FSD-Project)** | Real-time chat and video platform. WebRTC signalling over nine socket handlers, JWT auth, screen share, call recording. Deployed. |
| **[StockPredictor](https://github.com/CoderSoham/StockPredictor)** | Price forecasting experiments — and the walk-forward harness that proved my own earlier models were leaking their target. Reports the negative result. |
| **[Job-Recommendation-using-ML](https://github.com/CoderSoham/Job-Recommendation-using-ML)** | Résumé parsing to skill-gap analysis to live job matching through the Adzuna API. |

---

### A note on StockPredictor

It's the repo I'd point at first, because it contains its own negative result.

Earlier versions reported sub-1% prediction error. That error was target
leakage — `Close` sat inside the feature matrix while `Close` was the label. I
found it, built a leakage-free walk-forward evaluation across nine instruments
and three horizons, and measured what was actually there: **no model beat a
persistence baseline, and none beat the majority-class baseline on direction.**

That's the honest answer, it's written up in the README, and I think finding it
is worth more than the number it replaced.

---

### Tools

Python · TypeScript · C# · Node · React · PostgreSQL · MongoDB · Docker · Linux

Day to day: backend services, data pipelines, and the ML tooling around them.

---

<!-- Add your real LinkedIn URL here before publishing, or delete this line. -->
📍 Pune, India
