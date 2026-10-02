# Hi, I'm Ravi Poonia

**Full-stack product engineer, 8+ years.** I build complete products, not single layers. I've repeatedly owned the mobile app, the web/admin dashboard and the API that serves both for the same product, plus desktop apps and the release pipelines that ship them.

Strongest in **React / Next.js, React Native / Expo and Node.js (NestJS, Express)**. My differentiator is **integration work**: connecting platforms to large third-party systems over legacy XML and REST, with webhooks, sync jobs and reconciliation where correctness and idempotency matter more than speed.

🌍 Based in India · open to remote roles
📫 [ravipoonia7@gmail.com](mailto:ravipoonia7@gmail.com) · [LinkedIn](https://linkedin.com/in/ravi-poonia) · [Codementor](https://www.codementor.io/@ravipoonia)

---

## 🚚 Building now: [Transport Book](https://transportbook.app)

A fleet and transport management product for Indian transport businesses: trips, billing, party ledgers, bank reconciliation, fuel cards, job cards and live vehicle tracking. I lead engineering and wrote most of it. One TypeScript monorepo, six apps, used by real transport companies.

| App | Stack |
| --- | --- |
| Desktop ([Microsoft Store](https://apps.microsoft.com/detail/9NCXNXW5SXSR)) | Electron + React + MUI, offline-first SQLite with background sync |
| Web ([my.transportbook.app](https://my.transportbook.app)) | The desktop renderer built for the browser, talking to the server over WebSockets |
| Mobile + driver apps | Expo / React Native, offline outbox, background location, OTA updates |
| Server | Node.js + Express, MongoDB and Turso (libSQL), Redis, OpenTelemetry |
| Website | Vite + React with SSR, release and download portal |

Engineering highlights:

- **Offline-first sync and conflict handling**: devices work without a network and converge later through a change log, per-device checkpoints and conflict-safe IDs.
- **Live data migration**: moving tenants from MongoDB to per-org Turso databases with a freeze, copy, verify and switch cutover; production-to-dev syncs that write only row diffs.
- **One business layer, two runtimes**: a driver-neutral data layer and shared controllers that run unchanged on desktop (better-sqlite3) and server (Turso).
- **Integrations**: bank statement import and reconciliation suggestions, fuel-card providers, GST e-invoice / e-way bill JSON, cost-aware Google Maps caching, WebRTC peer file transfer.
- **Release engineering**: GitHub Actions pipelines across `develop` → beta → production for Microsoft Store, Android, iOS/TestFlight and EAS OTA, plus server deploys and preview channels.
- **Documentation habit**: architecture notes and workspace guides written before large changes, so the next engineer can find their way around.

## 💼 Experience

**Full Stack Developer, Hotstar** · Remote · 2023 – 2026
CMS and CRM teams. Built a context-aware AI chatbot pipeline (Python/FastAPI, OpenAI, Pandas) with PGVector RAG for internal query resolution; Node.js, Next.js, GraphQL and PostgreSQL microservices with Grafana observability.

**Full Stack Developer, Centric3** · Remote · 2021 – 2023
Web, mobile, desktop and backend work for startup and enterprise clients in travel/rental and B2B commerce. OTA-standard XML and REST integrations with third-party platforms, pricing/discount management portals, NestJS and GraphQL services, Electron and React Native apps.

**Full Stack Developer, Digital Trons** · Ahmedabad · 2019 – 2020
Led and mentored the mobile and web teams (React, Angular, React Native), built Node.js backends and owned CI/CD and multi-environment releases.

**React Native Developer, Levaral** · Rajkot · 2018
Cross-platform iOS/Android apps; an architecture rework cut app load time by about 3 s; Crashlytics-driven stability work.

## 🧭 Domains I've shipped in

Travel and rental reservations (inventory, rate engines, distribution integrations) · logistics and transport (fleet tracking, dispatch, offline field apps) · on-demand delivery marketplaces (customer, driver and ops apps on one backend) · B2B commerce (shared component libraries) · real-estate ERP (multi-role portals) · social and media platforms (feeds, subscriptions, back offices)

## 🛠 Tech

**Frontend:** React · Next.js · TypeScript · Redux Toolkit · Tailwind · MUI · Angular
**Mobile & desktop:** React Native · Expo · EAS / OTA · Fastlane · Electron
**Backend:** Node.js · NestJS · Express · GraphQL · REST · WebSockets · Python (FastAPI)
**Data:** PostgreSQL · Prisma · MongoDB · SQLite · Turso · Redis · PGVector
**Delivery:** Docker · GitHub Actions · AWS · GCP · Firebase · Grafana · OpenTelemetry

## 🌱 Open source

- [pubkey/rxdb#4405](https://github.com/pubkey/rxdb/pull/4405): fixed Firebase replication issues (merged)
