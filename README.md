<div align="center">

# Akhil Shah

### Backend-focused Full-Stack Engineer

I build real-time, data-heavy web systems — WebSocket pipelines, async APIs, transactional backends, and the React frontends on top of them.

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&duration=3200&pause=900&color=2EA8FF&center=true&vCenter=true&width=620&lines=Real-time+systems+with+WebSockets+%2B+Redis+Pub%2FSub;Async+APIs+with+FastAPI+and+Node.js;Transactional+backends+on+PostgreSQL;Static+analysis+%26+codebase+visualization" alt="What I build" />

<a href="https://www.linkedin.com/in/akhilshah04/"><img src="https://img.shields.io/badge/LinkedIn-akhilshah04-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:akhilshah179@gmail.com"><img src="https://img.shields.io/badge/Email-akhilshah179%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

---

## About

- 🎓 **B.Tech, Information & Communication Technology** — Pandit Deendayal Energy University
- 🛠️ I've shipped **6 full-stack systems** spanning fintech, e-commerce, developer tooling, marketplaces, and edtech
- ⚙️ My strongest work is on the backend: real-time data flow, caching, auth, payments, and database transactions
- 📚 Currently going deeper on **system design, distributed systems, and DSA in C++**
- 💼 **Open to** Software Engineering / Backend internships and full-time roles

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧭 [CodePilot](https://github.com/akhilshah179/CodePilot)
**Codebase intelligence for GitHub repositories**

Point it at a repo and it builds an explorable map of how the code actually fits together.

- Parses source into **dependency graphs** with deterministic layouts and cycle visualization
- Generates **architecture maps** where every claim links back to a file
- Traces **execution flows** from a UI action through services down to the database
- Interactive **3D view** of the codebase (Three.js + D3)

`TypeScript` `React 19` `Fastify` `SQLite` `Three.js` `D3`

</td>
<td width="50%" valign="top">

### 📈 [QuantFlow](https://github.com/akhilshah179/QuantFlow)
**Real-time market terminal & paper trading**

A trading terminal with live multi-asset data, analytics, and simulated execution.

- **Live market streaming** over WebSockets, cached with Redis
- Indicator engine: **SMA, EMA, RSI, MACD, Bollinger Bands, VWAP, ATR**
- **ACID paper trading** — orders, balances and positions update in one atomic Prisma transaction
- Multi-factor **stock screener** across global markets

`TypeScript` `React` `Node.js` `PostgreSQL` `Prisma` `Redis`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💧 [FluxCart](https://github.com/akhilshah179/FluxCart)
**E-commerce engine with dynamic pricing**

Prices that respond to demand, user activity, and stock levels — pushed live to every open browser.

- Pricing model built with **scikit-learn** on demand and inventory signals
- Price changes fan out via **Redis Pub/Sub → WebSockets**
- **Google OAuth 2.0** login with role-based access (admin / customer)

`Python` `FastAPI` `SQLAlchemy` `Redis` `React` `scikit-learn`

</td>
<td width="50%" valign="top">

### 🧠 [MindScape](https://github.com/akhilshah179/MindScape)
**All-in-one student productivity platform**

Study tools, coding practice, and collaboration in a single dashboard.

- **Coding arena** with remote code execution
- PDF-based learning and study management
- **Live video collaboration** between students
- Auth with **AWS Cognito**, files on **S3**, data in **DynamoDB**

`React 19` `Node.js` `Express` `AWS Cognito` `S3` `DynamoDB`

</td>
</tr>
</table>

### More projects

| Project | What it does | Stack |
| --- | --- | --- |
| ⚡ [**Stratagem**](https://github.com/akhilshah179/Stratagem-Project-main) | Turns meetings and chat into tracked tasks — Slack task assignment, a Chrome extension that detects Google Meet sessions, and two-way GitHub Issues sync | `FastAPI` `Firebase` `WebSockets` `Slack API` `React` |
| 🛠️ [**NexServe**](https://github.com/akhilshah179/NexServe) | Service-booking marketplace with multi-step booking, provider slot scheduling, Razorpay checkout, and a full booking lifecycle (requested → confirmed → completed / cancelled) | `FastAPI` `SQLAlchemy 2.0` `PostgreSQL` `Razorpay` `React` |

---

## Engineering Highlights

What these projects taught me to build — and can talk through in depth:

| | |
| --- | --- |
| **Real-time delivery** | Redis Pub/Sub feeding WebSocket broadcasts so many clients see price and market updates instantly (FluxCart, QuantFlow, Stratagem) |
| **Data integrity** | Atomic multi-table transactions so a trade can never debit cash without creating a position (QuantFlow) |
| **Auth & security** | JWT, Google OAuth 2.0, Firebase Auth, AWS Cognito, and role-based access control across projects |
| **Payments** | Razorpay order creation and verification tied to a booking state machine (NexServe) |
| **Static analysis** | Parsing real repositories into graphs and tracing flows end-to-end (CodePilot) |
| **Cloud** | AWS (Cognito, S3, DynamoDB), Docker, and CI with GitHub Actions |

---

## Tech Stack

<table>
<tr><td><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=cpp,py,ts,js,postgres" /></td><td>C++ · Python · TypeScript · JavaScript · SQL</td></tr>
<tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=nodejs,express,fastapi" /></td><td>Node.js · Express · Fastify · FastAPI · REST · WebSockets</td></tr>
<tr><td><b>Frontend</b></td><td><img src="https://skillicons.dev/icons?i=react,vite,tailwind,threejs" /></td><td>React · Vite · Tailwind CSS · Three.js · D3</td></tr>
<tr><td><b>Data</b></td><td><img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,dynamodb,firebase,prisma" /></td><td>PostgreSQL · Redis · SQLite · DynamoDB · Firebase · Prisma · SQLAlchemy</td></tr>
<tr><td><b>Cloud & DevOps</b></td><td><img src="https://skillicons.dev/icons?i=aws,docker,githubactions,git" /></td><td>AWS · Docker · GitHub Actions · Git</td></tr>
</table>

---

<div align="center">

## GitHub Activity

<img height="165" src="https://github-readme-stats.vercel.app/api?username=akhilshah179&show_icons=true&hide_border=true&theme=transparent&hide_rank=true&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akhilshah179&layout=compact&hide_border=true&theme=transparent&langs_count=6" />

<img width="70%" src="https://streak-stats.demolab.com?user=akhilshah179&hide_border=true&theme=transparent" />

<br><br>

**Hiring for a backend or full-stack role?** I'd love to chat — [LinkedIn](https://www.linkedin.com/in/akhilshah04/) · [Email](mailto:akhilshah179@gmail.com)

</div>
