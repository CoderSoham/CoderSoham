## Hi, I'm Soham

I'm a software engineer at Armor EDC in Pune, working on backend services and
data pipelines in the security space.

Most of what I build sits where a system meets messy real-world input — audio,
market data, résumés, live speech. I like that boundary. It's where the
interesting problems are, and it's where I've learned the most.

### Currently building

**Jarvis** is a voice assistant that runs entirely on my own machine. Wake word,
speech recognition, and response are all local, and it's fast enough that
talking to it feels like a conversation rather than a wait. I'm wiring up the
agent layer now so it can use tools and reach the internet when it needs to.

**rolefit** answers the question résumé scanners skip. Instead of "does this
résumé match this job," it works out what you should be applying for in the
first place, and which single skill would open the most doors if you learned it
next.

### Things I've built

**[NLP_FIR](https://github.com/CoderSoham/NLP_FIR)** turns a recording of an
emergency call into a structured report. It transcribes the call and detects the
language automatically, classifies what kind of emergency it is, pulls out names
and locations, writes a summary, and produces a printable FIR document. The
whole pipeline runs on CPU with no API keys — it was meant to work on modest
hardware, and it does.

**[FSD-Project](https://github.com/CoderSoham/FSD-Project)** is a real-time chat
and video platform. Accounts and friend invitations, direct messaging with
history, and group video rooms with screen sharing and call recording. The live
layer runs on Socket.IO, and the video is genuinely peer-to-peer over WebRTC
rather than routed through a server.

**[StockPredictor](https://github.com/CoderSoham/StockPredictor)** collects a
few years of experiments in short-horizon price prediction — tree ensembles,
LSTMs, transformers, graph networks, Monte Carlo simulation — alongside a
walk-forward evaluation harness that tests them properly across nine
instruments. Building the harness taught me more than any of the models did.

**[Job-Recommendation-using-ML](https://github.com/CoderSoham/Job-Recommendation-using-ML)**
reads a résumé, extracts skills with named-entity recognition, predicts a
suitable job title, and compares what someone has against what a role actually
asks for.

### Tools

Python, TypeScript, C#, Node, React, PostgreSQL, MongoDB, Docker, Linux.

<!-- Add your LinkedIn here, or delete this line. -->
📍 Pune, India
