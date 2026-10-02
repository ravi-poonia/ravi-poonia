# Hi, I'm Ravi Poonia

Full-stack engineer (8+ years) building **React Native, React, Electron and Node.js** products end to end — from the offline database on a user's device to the server, CI/CD and release pipeline. Based in New Delhi, open to **remote** roles.

📫 ravipoonia7@gmail.com · [Codementor](https://www.codementor.io/@ravipoonia)

## What I'm building: [Transport Book](https://transportbook.app)

A fleet and transport management product for Indian transport businesses — trips, billing, party ledgers, bank reconciliation, fuel cards, job cards and live vehicle tracking. I lead its engineering and wrote most of the code: one TypeScript monorepo, six apps, shipped to real customers.

| App | Stack |
| --- | --- |
| Desktop ([Microsoft Store](https://apps.microsoft.com/detail/9NCXNXW5SXSR)) | Electron + React + MUI, offline-first SQLite with background sync |
| Web ([my.transportbook.app](https://my.transportbook.app)) | The desktop renderer built for the browser, talking to the server over WebSockets |
| Mobile + Driver apps | Expo / React Native, offline outbox, background location, OTA updates |
| Server | Node.js + Express, MongoDB and Turso (libSQL), Redis, OpenTelemetry |
| Website | Vite + React with server-side rendering, release and download portal |

Problems I've worked on:

- **Offline-first sync**: devices work without a network and converge later through a change log, per-device checkpoints and conflict-safe IDs.
- **Database migration**: moving tenants from MongoDB to per-org Turso databases with a freeze, copy, verify and switch cutover, then cutting write costs by writing row diffs only.
- **Shared business layer**: one driver-neutral data layer and one set of controllers that run unchanged on desktop (better-sqlite3) and server (Turso).
- **Multi-tenant auth**: tenant boundary taken only from the JWT.
- **Release engineering**: GitHub Actions pipelines for Microsoft Store, Android, iOS/TestFlight and EAS OTA releases, plus server deploys and preview channels.
- **Integrations**: bank statement imports and reconciliation suggestions, fuel-card providers, GST e-invoice / e-way bill JSON, Google Maps with cost-aware caching, WebRTC peer file transfer.

## Previously

- **Full Stack Developer, Hotstar** (Oct 2023 – Jun 2026): React / Next.js / Node.js, plus a context-aware AI chatbot using Python (FastAPI), OpenAI and PGVector RAG.

## Open source

- [pubkey/rxdb#4405](https://github.com/pubkey/rxdb/pull/4405): fixed Firebase replication issues (merged).

## Tech

TypeScript · JavaScript · React · React Native · Expo · Next.js · Electron · Node.js · Express · NestJS · MongoDB · PostgreSQL · SQLite · Turso · Redis · Python / FastAPI · GitHub Actions · Firebase · OpenTelemetry
