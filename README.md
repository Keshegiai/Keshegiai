<div align="center">

# Hi, I'm Aidyn Almassov 👋

### Software Engineer from Almaty, Kazakhstan

Frontend · Backend · Mobile Development

</div>

---

## 🚀 About Me

I build production-ready web, backend, and mobile applications.

Currently working on:

- **SOBRANO** — a food retail platform: SSR storefront, admin back office, Supabase/Postgres, and an Android build from the same codebase;
- a **healthcare appointment platform** — Go backend, Next.js admin panel, Flutter mobile app, PostgreSQL, Docker, OpenAPI, and GitHub Actions.

---

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,html,css,go,postgres,supabase,flutter,dart,docker,git,githubactions,figma&perline=8" />
</p>

---

## 💼 Selected Work

### SOBRANO

Food retail platform — customer storefront, admin back office, and a native Android build,
all from a single TypeScript codebase.

- server-rendered storefront on TanStack Start, with the catalog served from Postgres across
  six merchandising surfaces (ready meals, raw kits, semi-ready, market, meat, vegetables);
- admin panel for catalog, branches, staff, and order management;
- server-authoritative order pricing — delivery fees, minimum-order rules, and promo codes are
  computed in the database, so the client never recalculates money;
- role-based access control enforced at the data layer and covered by automated tests in CI;
- shared domain types across web and mobile, generated from the database schema;
- Android build produced from the same codebase via Capacitor;
- CI/CD on GitHub Actions: test suite, versioned migrations, backend function deploys,
  web releases, and signed mobile builds.

**Stack:** React 19, TanStack Start / Router / Query, TypeScript, Tailwind CSS v4,
Supabase (Postgres, Edge Functions), Capacitor, Vitest, GitHub Actions

> In active development.

---

### Healthcare Appointment Platform

Appointment booking and clinic management, built as three coordinated surfaces.

- patient-facing mobile app for booking and appointment history;
- admin panel for clinics, doctors, and schedules;
- Go backend with a modular monolith architecture;
- OpenAPI-first REST contract shared across all clients;
- scheduling and availability logic resolved server-side;
- containerised deployment with CI on GitHub Actions.

**Stack:** Go, Next.js, Flutter, PostgreSQL, Docker, OpenAPI

> In active development.

---

### Diploma Management Platform

Platform for managing diploma projects and academic workflows.

- role-based dashboards;
- project stages and task management;
- file uploads and notifications;
- Kanban workflow;
- frontend integration with a Go REST API.

**Stack:** Next.js, React, TypeScript, TanStack Query, Go

> Product and client repositories are private.

---

## ⚙️ Engineering Focus

**Data layer**
- PostgreSQL schema design driven entirely by versioned migrations
- Business rules — pricing, validation, money math — resolved server-side rather than in clients
- Query optimization and read models shaped around real access patterns

**Application architecture**
- Modular monolith boundaries in Go; feature-sliced frontends in TypeScript
- SSR with route-level data loading and query hydration (TanStack Start, React Query)
- REST contracts defined OpenAPI-first, with types generated from the schema and drift-checked in CI

**Access control**
- Role-based authorization applied consistently across web, mobile, and API surfaces
- Authorization rules covered by automated tests rather than manual review

**Performance**
- Bundle budgets and chunk-composition checks enforced as CI steps, not as review comments
- Image pipelines with CDN transforms, `srcset`, and responsive variants
- Caching and data-loading strategy tuned per route

**Delivery**
- Layered test strategy: unit, component, and integration tests against a real database
- GitHub Actions pipelines for migrations, deploys, and signed mobile builds
- Docker-based deployment on self-managed infrastructure

---

# 📊 GitHub Activity

<p align="center">
  <img
    width="700"
    src="https://streak-stats.demolab.com?user=Keshegiai&theme=github-dark-blue&hide_border=true&locale=en&short_numbers=false&starting_year=2022&card_width=700"
    alt="Aidyn's GitHub contribution streak"
  />
</p>
