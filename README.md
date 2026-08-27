## Juan David Herrera

Software Engineering student at the University of Miami (B.S., May 2028). I build
AI systems that run against real constraints — a client's existing hardware, a
regulator's rulebook, someone's actual workflow — rather than demos.

Currently: an AI video analytics layer over a 37-camera security deployment, and
a cattle operations platform for a working feedlot in Colombia.

**C++ · Python · TypeScript · SQL · FastAPI · Next.js · PostgreSQL · Docker**

---

### Selected work

**SOFIA** — Cattle operations platform · `Next.js 16 · TypeScript · Prisma · PostgreSQL`
Weigh-ins, animal registry, paddock transfers, health events and gain-versus-threshold
reporting for a Colombian feedlot. Every screen reads live database state per request
rather than at build time, because the failure mode that matters is the owner quietly
stopping data entry. 45 test files across Vitest integration tests and Playwright
end-to-end flows.

**AnestIA** — Pre-anesthesia assessment · `TypeScript · PostgreSQL + pgvector · Prisma · Claude API`
Reads a patient's history and lab PDFs, drafts the clinical assessment, and hands it
to the anesthesiologist to correct and sign. The AI does the reconstruction work; the
clinical judgement stays with the physician, and nothing leaves the system unreviewed.
PDF text extraction escalates to vision only when the document is a scan — roughly 80%
cheaper than running vision on everything.

**Sellix AI** — Sales intelligence and WhatsApp CRM · `Next.js · TypeScript · Redis · Gemini`
Turns pharmacy point-of-sale data into commercial decisions: RFM segmentation, churn
flagging, refill prediction, cross-sell recommendations. Two-way WhatsApp inbox over
Twilio, and a prescription photographed by a customer comes back priced.

---

### Private work

These are client or in-progress projects. Happy to walk through the architecture and
the decisions in a conversation.

**VigilancIA** — AI video analytics over 37 existing security cameras at a residential
club. I built the rules and precedence engine that resolves the effective configuration
for every detection across a six-level hierarchy, and designed the vision pipeline:
batched inference on one on-site GPU node, decoupled from the rules engine by an event
bus. Along the way I found that 22 of the cameras depended on a single recorder capped
at 16 concurrent clients, and designed an RTSP distribution gateway around it.
`Python · YOLOX · Kafka · PostgreSQL` — 67 test files.

**Knowledge Intelligence (KI)** — Organizational knowledge map: who actually knows what,
and what breaks when they leave. Measures key-person concentration risk and supports
technical succession planning on an append-only audit trail. Built under the AI-Driven
Development Life Cycle methodology. `TypeScript · Python · PostgreSQL`

**BANKO** — Personal-finance platform for people living between Colombia and the US:
multi-bank, multi-currency aggregation with Claude-powered categorization.
`FastAPI · SQLAlchemy async · Celery · PostgreSQL · Redis · Docker` — paused.

---

📍 Coral Gables, FL · [LinkedIn](https://www.linkedin.com/in/juanherrera-dev/) · jdh272@miami.edu

*Looking for a Summer 2027 software engineering internship.*
