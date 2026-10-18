# Hi, I'm Le Cong Thien 👋

**Full-stack Developer** · Hoi An, Vietnam · Building production e-commerce, web platforms and growth tooling

<p align="left">
  <img src="https://img.shields.io/badge/Frontend-React%20%7C%20Next.js%20%7C%20TypeScript-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Backend-Node.js%20%7C%20PostgreSQL-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Payments-Stripe%20%7C%20PayPal%20%7C%20Klarna-635bff?style=flat-square" />
  <img src="https://img.shields.io/badge/DevOps-Docker%20%7C%20Kubernetes%20%7C%20CI%2FCD-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Mobile-SwiftUI-F05138?style=flat-square" />
  <img src="https://img.shields.io/badge/Growth-Technical%20SEO%20%7C%20Tracking-16a34a?style=flat-square" />
</p>

<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind,nodejs,express,python,postgres,redis,docker,kubernetes,githubactions,swift,figma" />
</p>

## About

I build and ship user-facing products end to end — from UI and checkout flows to APIs,
deployment and the SEO/analytics that bring users in. I currently work on a production
e-commerce platform with an international team, in English, on a microservices stack.

I work test-first with code review on every PR, and use AI assistants to move faster
on prototyping and reviews.

## What I work on

- **Frontend** — Next.js (App Router, SSR), React, TypeScript, responsive UI and interaction design
- **Backend** — Node.js / Express REST services, PostgreSQL, background workers, payment integrations
- **DevOps** — Docker, Kubernetes, GitHub Actions CI/CD, staging → production releases
- **Growth engineering** — technical SEO, structured data, Core Web Vitals, first-party event tracking
- **Quality** — Vitest, Playwright E2E, ESLint / Prettier, pre-commit hooks
- **Mobile** — native iOS apps with SwiftUI
- **Automation & AI** — scrapers, crawlers and AI-assisted tools for internal workflows
- **Games** — real-time multiplayer on Cloudflare Workers / Durable Objects

## Selected work

| Project | Summary |
|---|---|
| **E-commerce platform** (company) | Own the storefront end to end on a **Next.js + TypeScript** frontend backed by **Node.js / Java microservices on Kubernetes**. Drove the move from a monolith toward services, shipped the AI-powered personalization flow that is the product's core conversion path, and designed the checkout, pricing and promotion logic. Built the measurement layer (server-side conversion tracking) and the technical SEO foundation that made the site crawlable and rankable. 300+ merged PRs. |
| **Influencer commerce platform** | Designed and built solo a **Node.js / Express + PostgreSQL** platform in a layered clean architecture, with a **React** admin app, containerized and deployed on **Kubernetes**. Covers campaign and coupon attribution, multi-provider payouts, social account verification and event-driven notifications — built to be extended with new providers without touching core logic. |
| **Client websites & SEO** | Build and rank websites for hospitality and service businesses on **Next.js**, with bilingual content, booking flows and Lighthouse 100. **[Serena Retreat](https://www.serenaretreat.com/en)**: a new domain grew to 12.1k impressions, 300+ organic clicks and 22k Google Maps views in under 5 months. My own sites rank **#1 on Google** for *"naver marketing hội an"* ([navermarketingagency.com](https://www.navermarketingagency.com/)) and *"dịch vụ naver hội an"* ([congthienagency.com](https://www.congthienagency.com/vi)), and are cited in Google's AI Overviews. [thietkewebsitehoian.com](https://www.thietkewebsitehoian.com/) ranks on page one for *"thiết kế website hội an"*. Organic traffic turns into paying clients. |
| **Tracking Base System** | Architected a first-party event pipeline in **TypeScript** with an ingestion API, **Redis**-backed worker and **PostgreSQL** as the source of truth. Guarantees one real-world event → one conversion through idempotent IDs and deduplication, then fans out to Meta, Google Ads and TikTok — keeping attribution reliable when browser pixels are blocked. |
| **Tasket** | Native iOS app in **Swift / SwiftUI / SwiftData** with a **WidgetKit** extension sharing one data store. Modeled day-based task chains with automatic carry-over and truthful history; CI builds every PR with **GitHub Actions**. |
| **Lead-generation pipeline** | Two production tools running 24/7 on an Ubuntu VPS. A **Google Maps scraper** (**Node.js / Express + Puppeteer**) with a web UI and CLI, a multi-job queue, polygon/grid area scanning, live logs and checkpoint/resume so interrupted jobs continue where they stopped. A **website email crawler** (**TypeScript + Playwright**) that dedupes URLs, checks homepage and contact pages over HTTP, falls back to a headless browser for JS-rendered sites and scores each email by confidence. Both have session auth, rate limiting and **robots.txt**-aware crawling; tested with **Jest / Supertest**. |
| **[CongThienWorld](https://cong-thien-world-explore-the-hoi-an.vercel.app)** | A browser game for exploring Hoi An's old town, built with **Next.js + Phaser 3 + TypeScript** and playable on mobile. Five 2400×1600 map areas, 6 multi-step quest lines, 8 NPCs with dialogue and 3 mini-games (bánh xèo cooking, a night fishing tour, floating lantern wishes), with progress saved locally. All maps, NPCs and quests are defined as data, so new content is added without code changes. [Source](https://github.com/CongThienDev/CongThienWorld---Explore-The-Hoi-An-Map) |
| **Games** | **[Võ Lâm Chợ Trời](https://vo-lam-cho-troi.vo-lam-cho-troi.workers.dev/)**: real-time multiplayer brawler on **Cloudflare Workers + Durable Objects**, with a room module shared by client and server and client-side movement prediction. **[One Breath](https://diving-game2d.vercel.app/)**: 2D freediving vertical slice with depth-based breath, air tanks and an underwater camera. |

## Contact

🌐 [congthienagency.com](https://www.congthienagency.com) · 💼 [LinkedIn](https://www.linkedin.com/in/lecongthien/) · ✉️ [congthienjob@gmail.com](mailto:congthienjob@gmail.com)
