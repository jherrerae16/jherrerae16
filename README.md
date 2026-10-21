<img src="assets/header.svg" width="100%" alt="Juan David Herrera · Software Engineering @ University of Miami · B.S. May 2028">

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

<p align="center">
  <b>Software Engineering Intern</b> @ Informática y Tributos (Summer 2026) · <b>2nd place</b>, Pulse Miami Hackathon (2026)
</p>

### What I can do

<table>
<tr>
<td width="33%" valign="top">

**LLM products**<br>
<sub>Claude and Gemini inside real workflows: clinical drafts a doctor signs, a WhatsApp agent that sells.</sub>

</td>
<td width="33%" valign="top">

**Computer vision**<br>
<sub>People and vehicle detection on the cameras a site already has; prescription photos read and priced.</sub>

</td>
<td width="33%" valign="top">

**Full-stack products**<br>
<sub>Next.js, FastAPI and PostgreSQL apps people use every day, from a farm to a medical practice.</sub>

</td>
</tr>
<tr>
<td width="33%" valign="top">

**Payments and messaging**<br>
<sub>PayPal, Google Meet, Twilio and WhatsApp wired into one flow that runs on its own.</sub>

</td>
<td width="33%" valign="top">

**Data and analytics**<br>
<sub>Churn and refill prediction, weight gain and money per lot, key-person risk.</sub>

</td>
<td width="33%" valign="top">

**AI-built software, done carefully**<br>
<sub>My own harness: mockups first, review by a different agent, test output on record.</sub>

</td>
</tr>
</table>

### Selected work

<sub>The code of these three is private. The screens below are the real apps running on sample data.</sub>

#### VigilancIA <img src="https://img.shields.io/badge/Security-0969da?style=flat-square" alt="Security"> <sub>private · in production</sub>
`Python · YOLOX · FastAPI · PostgreSQL`

AI for security cameras. It adds people and vehicle detection to the cameras a site already has,
runs on local hardware so no video leaves the site, and puts every alert in one queue with its photo
and the reason it fired. 0.7 s median latency from camera to alert in the live test.

<img src="assets/vigilancia/queue.png" width="100%" alt="VigilancIA operator queue: six open alerts by severity, the shift timeline, and a critical vehicle alert open with its detection photo">

<table>
<tr>
<td align="center"><img src="assets/vigilancia/alert.gif" width="250" alt="A new critical alert arrives during the shift"><br><sub>A new alert arrives without taking over the screen</sub></td>
<td align="center"><img src="assets/vigilancia/incident.gif" width="250" alt="Opening an incident and confirming it"><br><sub>Open an incident, check the photo, confirm it</sub></td>
<td align="center"><img src="assets/vigilancia/rules.gif" width="250" alt="Changing a camera rule with a required reason"><br><sub>Rules per camera, every change with a reason</sub></td>
</tr>
</table>

<details>
<summary>More screens</summary>
<br>
<img src="assets/vigilancia/live.png" width="49%" alt="Live view of nearby cameras"> <img src="assets/vigilancia/queue-dark.png" width="49%" alt="The queue in dark theme">
<img src="assets/vigilancia/rules.png" width="49%" alt="Rules screen with change history">
</details>

#### SOFIA <img src="https://img.shields.io/badge/Agriculture-9a6700?style=flat-square" alt="Agriculture"> <sub>private · in production</sub>
`Next.js 16 · Prisma · PostgreSQL`

Runs a working cattle feedlot in Colombia: weigh-ins, paddocks, health events, purchase and sale
prices per kilo. Used every day on the farm, mostly from a phone in the corral.
504 unit and 130 browser tests.

<img src="assets/sofia/cattle.png" width="75%" alt="SOFIA cattle screen: lot gaining 783 g/day, one bar per steer against the 750 g/day target, and the weight curve"> <img src="assets/sofia/weigh-ins-phone.png" width="23%" alt="Recording weigh-ins on a phone">

<table>
<tr>
<td align="center"><img src="assets/sofia/weigh.gif" width="250" alt="Typing weights with the gain shown live"><br><sub>Weigh a lot: the gain shows as you type</sub></td>
<td align="center"><img src="assets/sofia/purchase.gif" width="250" alt="Registering a cattle purchase"><br><sub>Buy cattle: cost per kilo updates live</sub></td>
<td align="center"><img src="assets/sofia/calendar.gif" width="250" alt="Farm calendar with week and month views"><br><sub>Calendar of health tasks and to-dos</sub></td>
</tr>
</table>

<details>
<summary>More screens</summary>
<br>
<img src="assets/sofia/home.png" width="49%" alt="Home: lots, week calendar, to-dos and money for the month"> <img src="assets/sofia/animal.png" width="49%" alt="One animal's weight against the target and its history">
<img src="assets/sofia/paddocks.png" width="49%" alt="Paddocks">
</details>

#### Medical practice platform <img src="https://img.shields.io/badge/Healthcare-cf222e?style=flat-square" alt="Healthcare"> <sub>private · client</sub>
`Next.js · Prisma · PostgreSQL · PayPal`

International consultations end to end: the patient registers from a personal link, picks a time,
pays by PayPal, and the Google Meet link and WhatsApp confirmation go out on their own.

<img src="assets/practice/schedule.png" width="75%" alt="Doctor's weekly schedule with 21 paid virtual consultations"> <img src="assets/practice/booking-phone.png" width="23%" alt="Patient picking a day and time on a phone">

<table>
<tr>
<td align="center"><img src="assets/practice/register.gif" width="250" alt="Patient registering from a personal link"><br><sub>The patient registers from a personal link</sub></td>
<td align="center"><img src="assets/practice/pay.gif" width="250" alt="Picking a time and reaching PayPal"><br><sub>Picks a time and pays with PayPal</sub></td>
<td align="center"><img src="assets/practice/confirm.gif" width="250" alt="Paid appointment with Meet link and WhatsApp confirmation"><br><sub>Meet link and WhatsApp confirmation, ready</sub></td>
</tr>
</table>

<details>
<summary>More screens</summary>
<br>
<img src="assets/practice/today.png" width="49%" alt="Today: confirmations to send, payments, unfinished registrations"> <img src="assets/practice/appointment.png" width="49%" alt="Appointment panel: payment, video call, confirmation and history">
<img src="assets/practice/patient.png" width="49%" alt="Patient record with timeline"> <img src="assets/practice/settings.png" width="49%" alt="Consultation price, length and hours">
</details>

#### X Pro Column Analyzer <img src="https://img.shields.io/badge/Government-8250df?style=flat-square" alt="Government"> <sub>private · client</sub>
`Node · SQLite · Chrome extension · Claude API`

Social listening for government press offices. A Chrome extension captures X Pro columns; the dashboard
turns them into topics, sentiment, who amplifies whom, and a printable report for the press chief.
An AI assistant answers with citations to the tweets it used. 1,305 tests.

<img src="assets/xpro/pulse.png" width="100%" alt="X Pro Analyzer Pulse: tweets captured, relevant, noise and engagement, activity by hour and day, and a critical alert with its evidence tweets">

<table>
<tr>
<td align="center"><img src="assets/xpro/topics.gif" width="250" alt="Topic map and conversation climate"><br><sub>Topic map and conversation climate</sub></td>
<td align="center"><img src="assets/xpro/assistant.gif" width="250" alt="AI assistant answering with cited tweets"><br><sub>AI assistant that cites the tweets it used</sub></td>
<td align="center"><img src="assets/xpro/summary.gif" width="250" alt="Weekly summary and printable press report"><br><sub>Weekly summary and the press report</sub></td>
</tr>
</table>

<details>
<summary>More screens</summary>
<br>
<img src="assets/xpro/press-room.png" width="49%" alt="Press room with executive advice"> <img src="assets/xpro/network.png" width="49%" alt="Coordination network: accounts posting the same text">
<img src="assets/xpro/profile.png" width="49%" alt="Account profile with coordination signals"> <img src="assets/xpro/extension.png" width="20%" alt="Chrome extension popup after a capture">
</details>

#### More projects

<table>
<tr>
<td width="50%" valign="top">

#### AnestIA <img src="https://img.shields.io/badge/Healthcare-cf222e?style=flat-square" alt="Healthcare"> <sub>private · client</sub>
`TypeScript · pgvector · Claude API`

Reads patient history and lab PDFs, drafts the pre-anesthesia document, and the
anesthesiologist corrects and signs. Vision runs only on scans, about 80% cheaper.

</td>
<td width="50%" valign="top">

#### [Sellix AI](https://github.com/jherrerae16/Sellix-AI) <img src="https://img.shields.io/badge/Retail-1a7f37?style=flat-square" alt="Retail"> <sub>public · [live demo](https://sellix-ai-mvp.vercel.app)</sub>
`Next.js · Redis · Gemini · Twilio`

Pharmacy sales data turned into decisions: churn, refills, cross-sell. A two-way
WhatsApp inbox where a photographed prescription comes back priced.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### JD² <img src="https://img.shields.io/badge/Dev_tooling-59636e?style=flat-square" alt="Dev tooling"> <sub>private</sub>
`JavaScript · Node · 189 tests`

My harness for building software with AI agents: reopenable gates, review by an
agent that did not write the code, and test output on record before anything ships.

</td>
</tr>
</table>

Also: **Knowledge Intelligence**, key-person risk for a tech company, and **BANKO**, personal finance
across Colombia and the US. Both private and paused. Happy to walk through any private project in a conversation.

### How I build

- Screens are approved as mockups before code is written.
- An agent that did not write the change reviews it.
- "Tests pass" means the command, its output and the exit code are on record.

---

<p align="center">
  Looking for a <b>Summer 2027 software engineering internship</b> · Backend · Applied AI · Distributed systems<br>
  <a href="https://www.linkedin.com/in/juanherrera-dev/">LinkedIn</a> ·
  <a href="mailto:jdh272@miami.edu">jdh272@miami.edu</a> ·
  Coral Gables, FL
</p>
