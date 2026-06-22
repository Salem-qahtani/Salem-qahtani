<!--
  GitHub Profile README — Salem Al-Qahtani (@Salem-qahtani)

  Portfolio button removed for now (no personal portfolio yet). To restore later
  in the same style, re-add this to the header buttons and the Connect section:
    <a href="PORTFOLIO_URL"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="portfolio" /></a>

  Note: StadiumHub repo is currently private — the repo link will 404 for visitors
  until you flip it public. Live link set to "coming soon" until Railway deploy is up.
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6D28D9,50:7C3AED,100:4F46E5&height=210&section=header&text=Salem%20Al-Qahtani&fontSize=54&fontColor=ffffff&fontAlignY=36&desc=Software%20Engineer%20%C2%B7%20Full-Stack%20Developer&descSize=18&descAlignY=56&animation=fadeIn" alt="header" />

<a href="https://github.com/Salem-qahtani">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=23&duration=3000&pause=800&color=A855F7&center=true&vCenter=true&width=760&lines=Software+Engineering+Student+%40+King+Saud+University;Full-Stack+Developer+%7C+Real-Time+Systems;Building+production-grade+web+applications;Turning+complex+problems+into+clean+architecture" alt="typing" />
</a>

<br/>

<img src="https://img.shields.io/badge/King_Saud_University-Software_Engineering-6D28D9?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=1A1B27" alt="King Saud University - Software Engineering" />
<img src="https://img.shields.io/badge/Riyadh,_Saudi_Arabia-4F46E5?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=1A1B27" alt="Riyadh, Saudi Arabia" />

<br/><br/>

<a href="https://www.linkedin.com/in/salem-al-qahtani-417369371/"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
<a href="mailto:salem.aqahtani8@gmail.com"><img src="https://img.shields.io/badge/Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
<a href="https://github.com/Salem-qahtani"><img src="https://img.shields.io/badge/GitHub-1A1B27?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>

</div>

---

## About

> Software Engineering student at **King Saud University**, building production-grade, full-stack web applications with a product-engineering mindset.

- **Software engineering first** — I care about clean architecture, maintainable systems, and code that scales beyond the demo.
- **Full-stack development** — end-to-end ownership across modern React / TypeScript frontends and type-safe Express + TypeScript backends.
- **Real-time & product engineering** — WebSocket messaging, transactional booking flows, auth, and persistence designed for real users, not just localhost.
- **Data & backend architecture** — relational data modeling with PostgreSQL + Prisma, JWT-based auth, and server-side role & ownership enforcement.

**Open To** &nbsp;·&nbsp; Software Engineering Internships &nbsp;·&nbsp; Full-Stack / Backend / Frontend Roles &nbsp;·&nbsp; Open-Source Collaboration &nbsp;·&nbsp; Freelance Web Projects

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Tech Stack

**Languages**

<img src="https://go-skill-icons.vercel.app/api/icons?i=java,js,ts&theme=dark" alt="languages" />

**Backend &amp; Databases**

<img src="https://go-skill-icons.vercel.app/api/icons?i=nodejs,postgres,mysql&theme=dark" alt="backend" />

**Frontend**

<img src="https://go-skill-icons.vercel.app/api/icons?i=react,vite,html,css&theme=dark" alt="frontend" />

**Cloud, DevOps &amp; Tooling**

<img src="https://go-skill-icons.vercel.app/api/icons?i=cloudflare,netlify,railway,git,github,linux,vscode&theme=dark" alt="devops" />

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Featured Projects

<details open>
<summary><b>StadiumHub — Full-Stack Stadium Reservation Platform</b></summary>

<br/>

A full-stack platform that connects stadium **owners** with match **organizers**. Owners list their stadiums and open time slots; organizers browse availability and book reservations. Rebuilt from the ground up and significantly extended from a prior university team project — with full solo ownership of both the frontend and backend.

| | |
|:--|:--|
| **Stack** | React · TypeScript · Vite (frontend) · Express · TypeScript (backend) · PostgreSQL 17 · Prisma 7 (`@prisma/adapter-pg`) · JWT · Socket.io |
| **Scale** | Two-role system (owner / organizer) · 4 core models (User, Stadium, Slot, Reservation) · full CRUD across stadiums, slots & reservations |
| **Performance** | Transaction-based concurrency control to prevent double-booking · date-windowed slot queries (next 7 days, past slots filtered out) |
| **Security** | bcrypt password hashing · JWT auth with `protect` middleware · server-side role + ownership verification on every protected route |
| **Impact** | Solo from-scratch rebuild — migrated MongoDB → PostgreSQL and JavaScript → TypeScript to deepen backend and type-safety fundamentals |
| **Repository** | [Salem-qahtani/StadiumHub](https://github.com/Salem-qahtani/StadiumHub) *(private)* |
| **Live** | Deploying to Railway — coming soon |

Designed around two user roles that drive the entire data model. Every protected controller follows a consistent **role-check → lookup → ownership-verification** pattern, and reservations use database transactions to safely handle concurrent bookings. Real-time owner–organizer messaging via **Socket.io** is the next major feature, with messages persisted through Prisma.

</details>

<details>
<summary><b>Motion Designer Portfolio — Freelance Client Site</b></summary>

<br/>

A polished, responsive portfolio site delivered for a freelance client (motion designer) with a focus on smooth presentation and fast media delivery.

| | |
|:--|:--|
| **Stack** | React 18 · Vite 5 · CSS Modules · Cloudinary |
| **Scale** | Multi-section single-page portfolio with optimized media gallery |
| **Performance** | Cloudinary-backed asset pipeline for responsive, optimized media |
| **Security** | Static deployment with managed delivery via Netlify CDN |
| **Impact** | Shipped, client-facing freelance deliverable deployed to production |
| **Repository** | [Salem-qahtani/abdelrhman-potofolio](https://github.com/Salem-qahtani/abdelrhman-potofolio) |
| **Live** | [Live Site](https://abdelrhman-potofolio.netlify.app/) |

Built component-first with CSS Modules for scoped styling and Vite for a fast build pipeline, deployed on Netlify.

</details>

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Salem-qahtani&bg_color=0D1117&color=A855F7&line=7C3AED&point=ffffff&area=true&area_color=6D28D9&hide_border=true&custom_title=Contribution%20Graph" alt="activity-graph" />

</div>

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> Contribution Snake

<!-- Requires the Platane/snk GitHub Action committing to an `output` branch. -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Salem-qahtani/Salem-qahtani/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Salem-qahtani/Salem-qahtani/output/github-contribution-grid-snake.svg" />
  <img alt="snake animation" src="https://raw.githubusercontent.com/Salem-qahtani/Salem-qahtani/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="28"> Current Focus

```yaml
Salem:
  learning:
    - Socket.io & real-time messaging architecture
    - Advanced TypeScript patterns & system design
  building:
    - StadiumHub — real-time messaging + owner & organizer dashboards
    - Digital Deal — a real-time multiplayer card game
    - Railway deployment (full-stack)
  exploring:
    - WebSockets & real-time state synchronization
    - Advanced TypeScript patterns & system design
  open_to:
    - Software Engineering Internships
    - Full-Stack / Backend / Frontend roles
    - Open-source collaboration & freelance projects
```

---

## Connect

<div align="center">

<a href="mailto:salem.aqahtani8@gmail.com"><img src="https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" alt="gmail" /></a>
<a href="https://www.linkedin.com/in/salem-al-qahtani-417369371/"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
<a href="https://github.com/Salem-qahtani"><img src="https://img.shields.io/badge/GitHub-1A1B27?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>

</div>

---

<div align="center">

> *"Build it like it's already in production — clean, scalable, and built to last."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,50:7C3AED,100:6D28D9&height=140&section=footer" alt="footer" />

</div>
