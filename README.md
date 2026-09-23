<div align="center">

<h1>Jerónimo Gallego</h1>
<p>Full Stack Developer Jr. — .NET, C#, React, PostgreSQL</p>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jeronimo-gallego-n)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jerogallego099@gmail.com)

</div>

---

## About

Full Stack Developer Jr. with 2 years across academic and personal projects, focused on .NET/C#, React and PostgreSQL. I care about design decisions I can justify, not defaults: in Natillera I split business events from financial movements specifically to avoid polymorphic relations and data-integrity loss, and documented what I deliberately left as technical debt (concurrency control) instead of pretending it doesn't exist.

---

## Best Work

**[MindLens](https://github.com/Riwi-io-Medellin/187-mindlens)** — Backend Developer, hackathon, team of 3 (frontend, backend, cloud engineer)
Clinical journaling platform for psychologists. Modeled the data flow from audio ingestion to S3, exposed the APIs consumed by the frontend, and implemented vector similarity search with pgvector (cosine distance) to track a patient's emotional evolution across weekly reports.
`ASP.NET Core` `PostgreSQL` `pgvector` `AWS S3`

**Natillera** — Full Stack Developer, individual project, headed to production with real users
Platform for managing a collective savings fund with real money. Designed the data model to keep business events and financial transactions separate, added JWT-based authorization restricting write access to a single admin role, and planned daily serverless jobs for interest calculation and late-payment detection.
`ASP.NET Core` `React` `PostgreSQL` `JWT`

**[Kepler Ticket Receptionist](https://github.com/JeritoBa/events_ticket)** — Full Stack Developer, individual module within a larger team project (ticket sales & scanning system)
Built the reception module for concert and cinema seat reservations.
`Laravel` `Blade` `MySQL`

---

## Current Focus

- Implementing optimistic concurrency control (RowVersion pattern) on Natillera's financial entities
- Deepening ASP.NET Core and EF Core, particularly around transactional integrity (Unit of Work) and concurrency
- Writing unit tests for financial logic in Natillera (currently the main gap in that project)

---

## Stack

**Backend:** ASP.NET Core, C#, Laravel
**Frontend:** React
**Database:** PostgreSQL, pgvector
**Infra:** Docker, GitHub Actions, AWS S3

---

## GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=jeritoba&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jeritoba&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />

</div>
