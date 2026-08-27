# Oguz Kaan Dere

### Software Engineer · Java & Spring · React & TypeScript · Android Products

I am a software engineer based in **Düsseldorf, Germany**, with four years of professional experience across enterprise frontend systems, Java/JavaScript full-stack development, and hospital information software.

I build products with explicit domain rules, resilient data flows, typed interfaces, and reviewable technical decisions. My current work spans **Java microservices**, **React architecture**, **native Android development**, controlled AI/document workflows, and deterministic interactive systems.

[Portfolio](https://okdere.com) · [LinkedIn](https://www.linkedin.com/in/oguz-kaan-dere) · [Email](mailto:ogzkaann96@gmail.com) · [LeetCode](https://leetcode.com/oguzkaan/)

**Based in:** Düsseldorf, Germany  
**Open to:** Full-stack, Java/backend, frontend, implementation-oriented, AI-product, and MedTech software roles

---

## Featured work

### [LedgerFlow](https://github.com/ogzkaann/ledgerflow-banking-platform) — resilient banking platform

A complete educational banking platform demonstrating a durable, eventually consistent transfer workflow across independently deployable Java services.

**Engineering focus:** immutable account ledgers, reservations and compensation, transactional outboxes, idempotent consumers, Kafka workflows, PostgreSQL-owned service data, Redis-backed protective controls, Keycloak authorization, structured observability, and a role-aware React operations console.

**Quality proof:** OpenAPI and AsyncAPI contracts, Testcontainers integration suites, real Kafka/four-database end-to-end verification, Playwright browser journeys, CodeQL, SBOM generation, GitHub Actions, a documented production-readiness boundary, release checklist, recruiter demo flow, and a transfer load-testing plan.

**Stack:** Java 25, Spring Boot, Spring Cloud Gateway, Kafka, PostgreSQL, Redis, Keycloak, React, TypeScript, Docker, Playwright

### [Tip Tracker — Earnings Log](https://github.com/ogzkaann/tip-tracker-showcase) — Android earnings and shift ledger

A proprietary, offline-first Android product being prepared for Google Play, with a public engineering showcase for recruiter and portfolio review. It helps delivery couriers and other shift workers record work, understand user-configured compensation, reconcile pay periods, and track savings goals without requiring an account.

**Engineering focus:** fast accessible shift entry, hourly/per-delivery/hybrid compensation, effective-dated pay and adjustment rules, deterministic bonus and pay-period calculations, gross-payment reconciliation, itemized earnings, Room migrations, calendar history, insights, savings goals, and local PDF/CSV export.

**Privacy and quality:** English, German, and Turkish UI; app-private Room/DataStore persistence; no analytics, ads, account, subscription, cloud sync, or network dependency; explicit non-destructive migrations; unit and instrumentation coverage across financial rules, migrations, Compose flows, and exports.

**Public proof:** the showcase repository includes product screenshots, architecture and engineering-decision notes, testing strategy, privacy documentation, and small illustrative code excerpts without exposing the proprietary production source tree.

**Stack:** Kotlin, Jetpack Compose, Material 3, Room, DataStore, Hilt, Coroutines, Flow, Android CI

### [Physical Ops Simulator](https://github.com/ogzkaann/physical-ops-simulator) — 3D operations simulation platform

A browser-based discrete-event simulation platform for modeling physical service operations, starting with cafés and quick-service restaurants while keeping the core reusable for retail, clinics, warehouses, and other service environments.

**Engineering focus:** editable 3D venue geometry, operational stations and recipe DAGs, persisted scenarios and workforce constraints, deterministic SimPy queues, obstacle-aware pathfinding, spatial movement and congestion, FastAPI contracts, and renderer-independent simulation truth.

**Current proof:** Phases 1–7 are complete, including a reusable café fixture, customer/order/queue simulation, qualified-staff scheduling, travel and contention metrics, route preview/debug overlays, architecture documentation, end-to-end coverage, and frontend/backend quality gates. Live 3D run visualization, comparative heatmaps, and automated optimization remain explicit roadmap work.

**Stack:** React, TypeScript, Three.js, React Three Fiber, Zustand, Python 3.13, FastAPI, SimPy, Pydantic, Playwright, pytest

### [Swarm Script](https://github.com/ogzkaann/swarm-script) · [Live demo](https://swarm-script.vercel.app/)

A tactical automation roguelite where players program three autonomous combat robots with a small rule language and watch their logic fight through a deterministic arena run.

**Engineering focus:** tokenizer and recursive-descent parser, typed AST, source diagnostics, budgeted interpreter without `eval`, fixed-step simulation in a Web Worker, Monaco editing, Phaser rendering, Playwright verification, and a documented deterministic replay design.

**Stack:** React, TypeScript, Phaser 4, Monaco Editor, Web Workers, Vite, Vitest, Playwright

### [Germany Path Finder](https://github.com/ogzkaann/germany-path-finder) · [Live demo](https://germany-path-finder.vercel.app/)

A local-first RAG decision-support tool for Germany residence and career-path research.

**Engineering focus:** curated official sources, PDF ingestion, citations, BYOK model access, IndexedDB persistence, conservative uncertainty handling, and separation between evidence, AI explanation, and user decisions. Current evidence-integrity work defines freshness metadata, exact citation locations, contradictory-source handling, and portable decision exports.

### [Weather with Shaders](https://github.com/ogzkaann/yet-another-weather-app-but-with-shaders) · [Live demo](https://ogzkaann.github.io/yet-another-weather-app-but-with-shaders/)

A minimalist weather application where live forecast data drives a custom WebGL atmosphere.

**Engineering focus:** typed Open-Meteo integration, abortable and deduplicated requests, race protection, stale-while-revalidate caching, accessible search, deterministic procedural scenes, reduced-motion support, and GPU cleanup.

---

## Game work

### Night Soup — cozy cooking mystery

A Godot 2D rural-gothic narrative game set in a rain-soaked Oregon diner. The current Night 1 vertical slice includes cooking, customer dialogue, evidence collection, deduction, save/continue checkpoints, settings persistence, and multiple outcomes.

**Stack:** Godot 4, GDScript, data-driven dialogue, deterministic cooking systems, headless verification

### Kurye Patronu — courier life and progression vertical slice

A portrait-first Godot mobile game where the player starts as a walking courier, progresses through physically represented vehicles, licenses and better delivery platforms, and improves their home and daily life inside an offline fictional city.

**Systems:** unified playable delivery city with route alternatives and manual on-foot 3D navigation, transport-specific travel, multi-package carrying and routing, timed delivery-performance pressure, world time and needs, persistent career applications, equipment and home progression, debt and achievements, contextual delivery encounters, onboarding, and versioned save migration.

**Current status:** playable vertical slice in active development with Android device builds verified through an automated debug-APK workflow; the private repository is not presented as a finished commercial release.

**Stack:** Godot 4.7, GDScript, 3D SubViewport scenes, offline graph routing, data-driven progression, Android export, GitHub Actions

### [Schleimer](https://github.com/ogzkaann/schleimer) · [Live demo](https://schleimer.vercel.app/)

A short persuasion game where deterministic local rules score the interview and optional AI generates only the boss dialogue.

---

## Engineering approach

- Model important behavior with explicit domain types, state machines, and deterministic rules.
- Keep UI, domain logic, persistence, external services, and rendering independently testable.
- Design for failure through validation, idempotency, cancellation, retries, race protection, and clear recovery paths.
- Use AI as a constrained component with sources, schemas, uncertainty, and human review.
- Ship with tests, CI, documentation, accessibility checks, and honest scope boundaries.

---

## Technical stack

**Backend:** Java, Spring Boot, Spring Cloud, Kafka, Python, FastAPI, SimPy, Node.js, NestJS, Fastify, REST, OpenAPI, Maven  
**Frontend:** React, Angular, Vue.js, TypeScript, Next.js, Vite, Three.js, React Three Fiber, HTML, CSS  
**Android:** Kotlin, Jetpack Compose, Room, DataStore, Hilt, Coroutines, Flow  
**Data & infrastructure:** PostgreSQL, Oracle, PL/SQL, Redis, Flyway, Docker, Keycloak  
**AI & documents:** RAG, OCR, Tesseract.js, PDF.js, BYOK integrations, structured extraction  
**Graphics & games:** Godot, Unity, Phaser, WebGL2, GLSL, Monaco Editor, Web Workers  
**Delivery & testing:** GitHub Actions, Testcontainers, Playwright, Vitest, JUnit, pytest, CodeQL, Vercel

---

## Experience snapshot

- **Full-Stack / Frontend Developer — Ekinoks Software:** enterprise Angular and TypeScript applications, complex UI modules, API integration, debugging, and iterative delivery.
- **Full-Stack Developer — Fonet Software:** Java/JavaScript hospital information systems backed by Oracle and PL/SQL.
- **Independent Product Builder:** Java platforms, native Android products, local-first AI tools, document workflows, simulation systems, and interactive products.
- **Game Development — ATOM / METU:** Unity prototypes, gameplay systems, incubation work, and game jams.

---

## Open-source contribution

**Godot Engine — Turkish Localization Contributor**  
87+ technical Turkish translations for the official Godot Editor through Weblate, focused on consistent editor terminology.  
[View contribution profile](https://hosted.weblate.org/user/oguzkdere/)
