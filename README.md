<div align="center">

# Nexa

**A gaming platform in one app: social feed, discussions, game store and item marketplace.**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Status](https://img.shields.io/badge/status-work_in_progress-orange?style=flat-square)

</div>

## About

Nexa is a learning project: a full-stack Next.js app that combines a Steam-like game store with a social network for players. I'm building it milestone by milestone, and each milestone should end with a working app and a commit.

> **Status:** early stage. Right now the app has the base layout, fonts, a sticky top bar with search and placeholder pages for each section. Most of the features below are planned, not built yet.

## Planned features

- **Accounts & profiles**: email/password sign-up, editable profile with avatar, bio and game library, following other players
- **Feed**: posts with images and optional polls, optimistic likes, comments
- **Discussions**: communities and threads sorted by best or newest, with replies
- **Game store**: catalog with tag filters and sorting kept in the URL; "buying" adds a game to your library (no real payments)
- **Marketplace**: virtual credit, item listings with a rarity filter, purchases that run inside a database transaction
- **News**: read-only articles

## Tech stack

| Area | Tech |
| --- | --- |
| Framework | Next.js 16 (App Router), React 19, TypeScript |
| Styling | Tailwind CSS 4 |
| Planned | SQLite + Drizzle ORM, Better Auth, Zod, deployment on Vercel |

## Getting started

```bash
npm install
npm run dev     # http://localhost:3000
npm run build   # production build
npm run lint
```

## Roadmap

- [x] Project setup and assets
- [ ] App shell: top bar, sidebar, mobile navigation, one route per section
- [ ] Feed from static data, then from the database
- [ ] Database (Drizzle + SQLite) and accounts (Better Auth)
- [ ] Discussions, game store, marketplace, news
- [ ] Deployment, tests, CI, accessibility and performance pass
