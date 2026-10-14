<h1 align="center">Juan David Herrera</h1>

<p align="center">
  Software Engineering @ University of Miami · B.S. May 2028<br>
  <sub>I build AI systems that run against real constraints — a client's existing hardware,<br>a regulator's rulebook, someone's actual workflow — rather than demos.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Java-E76F00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <br>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

---

### In production

**An AI video analytics layer over a 37-camera security deployment**, and a cattle
operations platform running a working feedlot in Colombia. Now building a booking and
payments platform for a medical practice.

---

### Open work

<table>
<tr>
<td width="50%" valign="top">

#### [SOFIA](https://github.com/jherrerae16/sofia)
`Next.js 16 · TypeScript · Prisma · PostgreSQL`

Cattle operations for a Colombian feedlot: weigh-ins, animal
registry, paddock transfers, health events, gain-versus-threshold
reporting, purchase and sale prices per kilo, expenses by month.

In daily use on the farm. Every screen reads live database state
per request rather than at build time — the failure mode that
matters is the owner quietly stopping data entry. **428 unit and
118 browser tests** across Vitest and Playwright.

</td>
<td width="50%" valign="top">

#### [AnestIA](https://github.com/jherrerae16/AnestIA)
`TypeScript · pgvector · Prisma · Claude API`

Pre-anesthesia assessment: reads patient history and lab PDFs,
drafts the clinical document, hands it to the anesthesiologist
to correct and sign.

The AI does the reconstruction; the clinical judgement stays with
the physician, and nothing leaves unreviewed. PDF text extraction
escalates to vision only for scans — **~80% cheaper** than running
vision on everything.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Sellix AI](https://github.com/jherrerae16/Sellix-AI) · [live demo](https://sellix-ai-mvp.vercel.app)
`Next.js · TypeScript · Redis · Gemini · Twilio`

Turns pharmacy point-of-sale data into commercial decisions: RFM
segmentation, churn flagging, refill prediction, cross-sell.

Two-way WhatsApp inbox over Twilio, and a prescription photographed
by a customer comes back priced. **23,500 lines** across 18 API
routes and 13 pages.

</td>
<td width="50%" valign="top">

#### Interested in
`Backend · Distributed systems · Applied AI`

Systems where correctness is measurable and the constraints are
someone else's: existing hardware, a regulator's rulebook, a
budget that will not move.

Looking for a **Summer 2027 software engineering internship**.

</td>
</tr>
</table>

---

### Client and in-progress work

These stay private. Happy to walk through the architecture and the decisions in a conversation.

**VigilancIA** — AI video analytics over 37 existing security cameras at a residential club,
now in production on site. I built the rules and precedence engine that resolves the effective
configuration for every detection across a six-level hierarchy, the detection node and the
operator console. The site server has no discrete GPU, so the first rollout covers the 10
critical cameras on the existing Intel hardware, with the vision adapter behind an interface
so a GPU can drop in later. Along the way I found that 22 of the cameras depended on a single
recorder capped at 16 concurrent clients, and designed an RTSP distribution gateway around it.
Live test on real cameras: 0.7 s median latency.
<br><sub>`Python · YOLOX · FastAPI · PostgreSQL` — 35,000 lines, 237 test files</sub>

**Medical practice platform** — Booking and payments for international consultations: the
patient gets a personal registration link, pays by PayPal on the same page, and a webhook
books the Google Meet call and sends the WhatsApp confirmation. Built so the doctor and one
assistant can run it without technical help.
<br><sub>`Next.js · TypeScript · Prisma · PostgreSQL · PayPal` — 396 test files, client work</sub>

**JD²** — My own harness for building products with AI agents: a CLI that tracks phases,
reopenable gates and handoffs, generates a read-only status page, and runs adversarial review
and QA agents before anything is called done. Dogfooded on the medical practice platform.
<br><sub>`JavaScript · Node` — v0.2.2</sub>

**Knowledge Intelligence** — Organizational knowledge map: who actually knows what, and what
breaks when they leave. Measures key-person concentration risk and supports technical
succession planning on an append-only audit trail.
<br><sub>`TypeScript · Python · PostgreSQL` — built under the AI-DLC methodology, paused</sub>

**BANKO** — Personal-finance platform for people living between Colombia and the US:
multi-bank, multi-currency aggregation with Claude-powered categorization.
<br><sub>`FastAPI · SQLAlchemy async · Celery · PostgreSQL · Redis · Docker` — paused</sub>

---

<p align="center">
  <a href="https://www.linkedin.com/in/juanherrera-dev/">LinkedIn</a> ·
  <a href="mailto:jdh272@miami.edu">jdh272@miami.edu</a> ·
  Coral Gables, FL
</p>
