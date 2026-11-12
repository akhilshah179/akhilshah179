
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
- 🛠️ I've created **6 full-stack systems** spanning fintech, e-commerce, developer tooling, marketplaces, and edtech.
- ⚙️ My strongest work is on the backend: real-time data flow, caching, authentication, payments, and database transactions.
- 📚 Currently going deeper on **System Design, Distributed Systems, and DSA in C++**.
- 💼 **Open to:** Software Engineering / Backend internships and full-time roles.

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧭 [CodePilot](https://github.com/akhilshah179/CodePilot)

**Codebase Intelligence for GitHub Repositories**

Point it at a repo and it builds an explorable map of how the code actually fits together.

- Parses source into **dependency graphs** with deterministic layouts and cycle visualization.
- Generates **architecture maps** where every claim links back to a file.
- Traces **execution flows** from a UI action through services down to the database.
- Interactive **3D view** of the codebase (Three.js + D3).

`TypeScript` `React 19` `Fastify` `SQLite` `Three.js` `D3`

</td>
<td width="50%" valign="top">

### 📈 [QuantFlow](https://github.com/akhilshah179/QuantFlow)

**Real-Time Market Terminal & Paper Trading**

A trading terminal with live multi-asset data, analytics, and simulated execution.

- **Live market streaming** over WebSockets, cached with Redis.
- Indicator engine: **SMA, EMA, RSI, MACD, Bollinger Bands, VWAP, ATR**.
- **ACID paper trading** — orders, balances and positions update in one atomic Prisma transaction.
- Multi-factor **stock screener** across global markets.

`TypeScript` `React` `Node.js` `PostgreSQL` `Prisma` `Redis`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💧 [FluxCart](https://github.com/akhilshah179/FluxCart)

**E-Commerce Engine with Dynamic Pricing**

Prices that respond to demand, user activity, and stock levels — pushed live to every open browser.

- Pricing model built with **scikit-learn** on demand and inventory signals.
- Price changes fan out via **Redis Pub/Sub → WebSockets**.
- **Google OAuth 2.0** login with role-based access (admin / customer).

`Python` `FastAPI` `SQLAlchemy` `Redis` `React` `scikit-learn`

</td>
<td width="50%" valign="top">

### 🧠 [MindScape](https://github.com/akhilshah179/MindScape)

**All-in-One Student Productivity Platform**

Study tools, coding practice, and collaboration in a single dashboard.

- **Coding arena** with remote code execution.
- PDF-based learning and study management.
- **Live video collaboration** between students.
- Authentication with **AWS Cognito**, files on **S3**, data in **DynamoDB**.

`React 19` `Node.js` `Express` `AWS Cognito` `S3` `DynamoDB`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚡ [Stratagem](https://github.com/akhilshah179/Stratagem-Project-main)

**Meeting Intelligence & Task Automation**

Turns conversations in meetings and chat into tracked, assigned tasks.

- **Slack integration** for assigning tasks right from chat.
- **Chrome extension** that detects Google Meet sessions.
- **Two-way sync** with GitHub Issues.
- **Real-time updates** across the team over WebSockets.

`Python` `FastAPI` `Firebase` `WebSockets` `Slack API` `React`

</td>
<td width="50%" valign="top">

### 🛠️ [NexServe](https://github.com/akhilshah179/NexServe)

**On-Demand Service Booking Marketplace**

Connects customers with service providers, from picking a slot to paying for it.

- **Multi-step booking** flow for customers.
- **Provider scheduling** with slot availability.
- **Razorpay checkout** with payment verification.
- Full **booking lifecycle** — requested → confirmed → completed / cancelled.

`Python` `FastAPI` `SQLAlchemy 2.0` `PostgreSQL` `Razorpay` `React`

</td>
</tr>
</table>

---

## Engineering Highlights

What these projects taught me to build — and can talk through in depth:

| Engineering Area | Implementation |
|---|---|
| **Real-Time Delivery** | Redis Pub/Sub feeding WebSocket broadcasts so many clients see price and market updates instantly (FluxCart, QuantFlow, Stratagem). |
| **Data Integrity** | Atomic multi-table transactions so a trade can never debit cash without creating a position (QuantFlow). |
| **Authentication & Security** | JWT, Google OAuth 2.0, Firebase Auth, AWS Cognito, and role-based access control across projects. |
| **Payments** | Razorpay order creation and verification tied to a booking state machine (NexServe). |
| **Static Analysis** | Parsing real repositories into graphs and tracing flows end-to-end (CodePilot). |
| **Cloud Infrastructure** | AWS (Cognito, S3, DynamoDB), Docker, and CI with GitHub Actions. |

---

## Technical Skills

<table>
<tr>
<td width="20%" valign="middle"><b>Languages</b></td>
<td width="34%" valign="middle">
<img src="https://skillicons.dev/icons?i=c,cpp,python,react,js,html,css" />
</td>
<td valign="middle">
C · C++ · Python · SQL · React · JavaScript (ES6+) · HTML5 · CSS3
</td>
</tr>

<tr>
<td valign="middle"><b>Backend and APIs</b></td>
<td valign="middle">
<img src="https://skillicons.dev/icons?i=nodejs,fastapi,redis,postgres,mysql" />
</td>
<td valign="middle">
Node.js · FastAPI · RESTful APIs · WebSockets · JWT · Redis · PostgreSQL · MySQL
</td>
</tr>

<tr>
<td valign="middle"><b>Infra and Tools</b></td>
<td valign="middle">
<img src="https://skillicons.dev/icons?i=aws,docker,firebase,git,github,vscode" />
</td>
<td valign="middle">
AWS · Docker · Firebase · n8n · Git · GitHub · VS Code · Wireshark
</td>
</tr>

<tr>
<td valign="middle"><b>Core CS</b></td>
<td valign="middle">
<img src="https://skillicons.dev/icons?i=cpp,python" />
</td>
<td valign="middle">
Data Structures and Algorithms · OOP · Operating Systems · DBMS · Computer Networks · Cloud Fundamentals
</td>
</tr>

<tr>
<td valign="middle"><b>Soft Skills</b></td>
<td valign="middle">
<img src="https://img.shields.io/badge/Problem_Solving-2563EB?style=flat-square" />
<img src="https://img.shields.io/badge/Communication-0891B2?style=flat-square" />
<img src="https://img.shields.io/badge/Teamwork-059669?style=flat-square" />
</td>
<td valign="middle">
Problem Solving · Communication · Teamwork
</td>
</tr>
</table>

---

<div align="center">

## GitHub Activity

<img height="165" src="https://github-readme-stats.vercel.app/api?username=akhilshah179&show_icons=true&hide_border=true&theme=transparent&hide_rank=true&include_all_commits=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akhilshah179&layout=compact&hide_border=true&theme=transparent&langs_count=6" />

<img width="70%" src="https://streak-stats.demolab.com?user=akhilshah179&hide_border=true&theme=transparent" />

<br/><br/>

**Hiring for a backend or full-stack role?**

I'd love to chat.

<a href="https://www.linkedin.com/in/akhilshah04/">LinkedIn</a> · <a href="mailto:akhilshah179@gmail.com">Email</a>

</div>
