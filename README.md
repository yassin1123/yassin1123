# Yassin Al-Yassin

### I build AI agents for the engineers who design the physical world.

Second-Year Electronic Engineering at the University of Southampton, predicted First. Hardware-AI bilingual — I can read a schematic and ship a multi-agent system. Currently building [Substrate](https://www.yassinalyassin.com/deck), the agentic platform for deep-tech engineering, starting with legacy circuit modernisation.

Previously shipped [Argus](https://github.com/yassin1123/Argus) solo to 150 users across 180DC Southampton, placed 2nd of 100+ teams at the AMD Pervasive AI Contest, won 1st at BAE Systems Hack the Future, and won 1st in the Hardware & Infrastructure track at the Urban Friction 48-Hour Hackathon (London). Incoming Data & AI intern at Accenture, Summer 2026.

---

## 🛠️ What I'm building

**[Substrate](https://www.yassinalyassin.com/deck) — agentic AI for deep-tech engineering**
The engineers who design chips, circuits, and embedded systems still work in tools from the 1990s. Substrate is the agentic platform for that gap. Starting with Tracer, an agent that modernises legacy electronic circuits — the technical core placed 2nd of 100+ teams at AMD. Pre-seed, live design-partner conversations.
`Multi-provider LLM router · agentic core · domain-specific models · multimodal schematic reasoning`

**FlyBy — real-time plane-spotting display**
A physical IoT screen that detects every aircraft passing within a ~3-mile geofence around you and instantly shows its airline, aircraft type, and route — where it's flying from and to. An ESP32-S3 edge node drives the display; a Rust/Tokio ingestion service opens a firehose to the live global flight network while PostGIS computes in real time when a plane's altitude and trajectory pierce a 3D cylindrical geofence. **$20k in revenue**, built with an airline pilot as the initial investor and aviation-domain advisor.
`ESP32-S3 · Rust / embedded C · FastAPI · PostgreSQL + PostGIS · Redis · ADS-B telemetry`

---

## 🚀 Recently shipped

**[Argus](https://github.com/yassin1123/Argus) — multi-agent research platform**
Built solo as an MVP, grew to a deployment across the 150-person 180DC Southampton chapter over multiple release cycles. Planner → Researcher → Analyst → Critic → Verifier → Writer pipeline that turns ambiguous strategic questions into evidence-backed consulting-grade reports. Awarded £3,000 Enterprise Prize, pitched at Future Worlds. Left May 2026 to focus on Substrate.
`Next.js · FastAPI · Python · Celery · PostgreSQL/pgvector · embeddings · LLM APIs`

**[Adaptive Traffic Signal Control](https://github.com/yassin1123/adaptive-traffic-signal-control) — radar-sensed adaptive traffic system**
Built solo in a 48-hour hackathon; won 1st in the Hardware & Infrastructure track. A complete sensing-to-decision system in two halves: a TI IWR6843 mmWave radar node running the full FMCW signal chain in embedded C (range/Doppler FFT → CFAR → angle-of-arrival → tracking), feeding a Python receding-horizon optimiser that allocates green time across a 2×2 grid of intersections. Cuts average wait up to 94% vs a fixed timer while keeping the grid stable, with the two halves connected by a verified per-approach contract.
`Embedded C · IWR6843 / FMCW DSP · Python · receding-horizon optimisation · pygame`

**[DormDrop](https://github.com/yassin1123/DormDrop) — peer-to-peer student delivery platform**
24/7 delivery across University of Southampton halls. Grew to hundreds of active users before university shutdown mid-semester. Full order lifecycle — browse, pay, track, deliver, rate — with live GPS tracking, real-time updates, and an admin analytics dashboard.
`Next.js · TypeScript · Supabase · Stripe · Google Maps · Realtime · PWA`

**[Circuit Reasoning Engine](https://github.com/yassin1123/Circuit-Reasoning-Engine) — deterministic circuit analysis**
Functional block detection, parameter estimation, and auditable analysis of netlists. The technical foundation that became Substrate's Tracer agent.
`Python · netlist parsing · symbolic reasoning · multimodal LLMs`

---

## 🏆 Selected wins

- 🥇 **Urban Friction 48-Hour Hackathon 2026 (London)** — 1st place, Hardware & Infrastructure track. Built a complete radar-sensed adaptive traffic-control system solo — embedded FMCW radar firmware for a TI IWR6843 plus a Python control brain — connected by a verified contract.
- 🥈 **AMD Pervasive AI Contest 2025** — 2nd of 100+ teams. End-to-end AI system on AMD GPUs that infers a circuit's components and functional intent.
- 🥇 **BAE Systems Hack the Future 2025** — 1st of ~15 teams. Full-stack World Cup fan-experience system across hardware, networking, backend, and UI in 24 hours.
- 🏅 **Zepler Prize** — top practical lab grades in cohort, University of Southampton.

---

## 🧰 Stack

**AI/ML** Python · PyTorch · TensorFlow · OpenAI / Anthropic / Google / xAI APIs · multi-agent orchestration · RAG · embeddings · pgvector
**Backend** FastAPI · Celery · PostgreSQL · Docker · AWS · Azure
**Frontend** TypeScript · React · Next.js
**Hardware / EE** Verilog · VHDL · STM32 / embedded C · FMCW radar DSP · MATLAB · Simulink · LTspice · KiCad

---

## 📝 Writing

I write occasionally about agentic systems, deep-tech, and what shipping real AI products actually looks like — on [my site](https://www.yassinalyassin.com/).

- What 150 users taught me about agentic UX — notes from shipping Argus
- Why I left Argus at Southampton — on building things that outlast you

---

## 📫 Get in touch

Open to: founder conversations, Substrate design partners.

[Portfolio](https://www.yassinalyassin.com/) · [LinkedIn](https://linkedin.com/in/yassinalyassin) · [yassinalyassin771@gmail.com](mailto:yassinalyassin771@gmail.com)
