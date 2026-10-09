<!-- GitHub Profile README | Guneet Toppo -->

# Guneet Toppo

**Backend & systems engineering — Go, C++, TypeScript.**
Final-year Computer Engineering @ Delhi Technological University (2023–2027).

I care about the parts of a system that have to stay correct under load and failure: event logs
with consumer offsets, webhook delivery with dead-letter queues, and a key/value server written
against raw sockets in C++.

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guneettoppo_23cs160@dtu.ac.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guneettoppo2004)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/guneettoppo)

---

## Featured projects

| Project | What it does | Stack |
| :-- | :-- | :-- |
| **[EventForge](https://github.com/guneettoppo/eventforge)** | Kafka-style event streaming platform: durable log storage, consumer offsets, retry and dead-letter queues, live WebSocket dashboard. Ships as a single Go binary with no external dependencies. | `Go` `WebSockets` `React` `SQLite` |
| **[FlashKV](https://github.com/guneettoppo/FlashKV)** | Multi-threaded in-memory key/value server written from scratch in C++ against raw POSIX sockets. Speaks RESP, so `redis-cli` and `redis-benchmark` drive it directly — TTLs, pipelining, one detached thread per client. | `C++` `POSIX sockets` `RESP` `pthreads` |
| **[Everhook](https://github.com/guneettoppo/Everhook)** | Self-hosted webhook delivery engine: publish an event once, fan it out to every matching endpoint with retries, HMAC signing, per-subscriber rate limiting and a dead-letter queue for exhausted deliveries. | `TypeScript` `Fastify` `Postgres` `Redis` |
| **[Vync](https://github.com/guneettoppo/Vsync)** | Screen recorder that uploads while it records — chunks leave the machine as they are produced, get assembled server-side, and come back as a shareable link. [Live demo](https://vsync-9j37.vercel.app/) | `Next.js` `Electron` `Prisma` `Neon` |
| **[DocLens](https://github.com/guneettoppo/DocLens)** | Document sharing with page-level readership analytics and self-destruct links: see which pages each viewer actually read, with viewer attribution, view caps and expiry windows. [Live demo](https://doc-lens-six.vercel.app/) | `Next.js` `Prisma` `Neon` `Vercel Blob` |
| **[RatesLab](https://github.com/guneettoppo/RatesLab)** | 60+ years of US Treasury yield data (1962 → today) in SQLite, served through a Streamlit dashboard: par → spot bootstrapping, level / slope / curvature tracking, inversion-to-recession scorecard, bond math lab. | `Python` `SQLite` `Streamlit` |

Also on here: [Vera](https://github.com/guneettoppo/vera-bot) — grounded merchant-messaging engine (magicpin *Build Vera Better* challenge) · [PulseDesk](https://github.com/guneettoppo/forge2main) — multi-tenant support desk with organization-scoped queries · [PixiAI](https://github.com/guneettoppo/PixiAI) — AI image editor on a Fabric.js canvas · [ZeroPass](https://github.com/guneettoppo/zeropass) — passwordless file sharing.

---

## Toolbox

#### 💻 Languages
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

#### 🧩 Frameworks & runtime
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

#### 🛢️ Data & storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=neon&logoColor=black)

#### ⚙️ Infrastructure & tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=guneettoppo&show_icons=true&hide_border=true&bg_color=0D1117&title_color=E53E3E&text_color=FAFAF9&icon_color=E53E3E&rank_icon=github" />
  <img height="165" alt="Guneet's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=guneettoppo&show_icons=true&hide_border=true&bg_color=FAFAF9&title_color=E53E3E&text_color=111111&icon_color=E53E3E&rank_icon=github" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=guneettoppo&layout=compact&langs_count=8&hide_border=true&exclude_repo=btech_project,forge2main&bg_color=0D1117&title_color=E53E3E&text_color=FAFAF9" />
  <img height="165" alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guneettoppo&layout=compact&langs_count=8&hide_border=true&exclude_repo=btech_project,forge2main&bg_color=FAFAF9&title_color=E53E3E&text_color=111111" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=guneettoppo&hide_border=true&background=0D1117&ring=E53E3E&fire=E53E3E&currStreakLabel=E53E3E&sideLabels=FAFAF9&dates=8B949E&currStreakNum=FAFAF9&sideNums=FAFAF9" />
  <img alt="Commit streak" src="https://streak-stats.demolab.com?user=guneettoppo&hide_border=true&background=FAFAF9&ring=E53E3E&fire=E53E3E&currStreakLabel=E53E3E&sideLabels=111111&dates=555555&currStreakNum=111111&sideNums=111111" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/guneettoppo/guneettoppo/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/guneettoppo/guneettoppo/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/guneettoppo/guneettoppo/output/github-snake.svg" />
</picture>

---

> Learn. Build. Ship. Repeat.
