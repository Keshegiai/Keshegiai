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

Food retail platform for a Kazakhstani producer — customer storefront, admin back office,
and a native Android build, all from one TypeScript codebase.

- SSR storefront on TanStack Start with the full catalog served from Postgres across six
  merchandising surfaces (ready meals, raw kits, semi-ready, market, meat, vegetables);
- admin panel for catalog, branches, staff, and orders — MFA-gated staff management with an
  append-only audit log;
- order pricing is server-authoritative: delivery fees, minimum-order rules, and promo codes
  are computed by a single Postgres RPC, never recalculated in the client;
- row-level security on every public table, verified by SQL policy tests that run against a
  real Supabase project in CI;
- Supabase Edge Functions for privileged operations — image upload, staff invites, MFA reset,
  SMS auth;
- Capacitor wraps the same web build into a signed Android release;
- images served through Supabase render transforms with `srcset` — the market page dropped
  from 15 MB of imagery to 437 KB;
- five GitHub Actions workflows: CI, frontend deploy to VPS, gated migrations, Edge Function
  deploys, and mobile release.

**Stack:** React 19, TanStack Start / Router / Query, TypeScript, Tailwind CSS v4,
Supabase (Postgres, RLS, Edge Functions), Capacitor, Vitest, Sentry, Nginx + systemd, GitHub Actions

> In active development.

---

### Healthcare Appointment Platform

Appointment booking and clinic management, built as three coordinated surfaces.

- patient-facing mobile app for booking and appointment history;
- admin panel for clinics, doctors, and schedules;
- Go backend with a modular monolith architecture;
- OpenAPI-first REST contract shared across clients;
- containerised deployment with CI on GitHub Actions.

**Stack:** Go, Next.js, Flutter, PostgreSQL, Docker, OpenAPI

> In active development.

---

### Amanat Business World

Multilingual corporate website for a business services company in Kazakhstan.

- responsive company website;
- Russian, Kazakh, and English localization;
- service pages and lead collection;
- technical SEO and analytics integration;
- production deployment.

**Stack:** Next.js, TypeScript, Tailwind CSS

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
- PostgreSQL schema design driven entirely by versioned migrations — no manual dashboard edits
- Row-level security policies, `security definer` RPC boundaries, and SQL tests that assert them
- Server-authoritative business rules: pricing, validation, and money math live in the database

**Application architecture**
- Modular monolith boundaries in Go; feature-sliced frontends in TypeScript
- SSR with route-level data loading and query hydration (TanStack Start, React Query)
- REST contracts defined OpenAPI-first, with types generated from the schema and drift-checked in CI

**Security**
- Authentication and authorization with role-based access and enforced MFA for privileged roles
- Append-only audit logging, rate limiting, CSP and security headers verified before deploy
- Secret hygiene enforced by CI guards that fail the build on secrets leaking into client bundles

**Performance**
- Bundle budgets and chunk-composition guards enforced as CI steps, not as review comments
- Image pipelines with CDN transforms, `srcset`, and responsive variants
- Query optimization and read models tuned for the access patterns that actually run

**Delivery**
- Test strategy layered across unit, component, integration against a real database, and SQL policy tests
- GitHub Actions pipelines: gated migrations, edge deploys, VPS releases, signed mobile builds
- Docker, Nginx, and systemd on self-managed infrastructure

---

# 📊 GitHub Activity

<p align="center">
  <img
    width="700"
    src="https://streak-stats.demolab.com?user=Keshegiai&theme=github-dark-blue&hide_border=true&locale=en&short_numbers=false&starting_year=2022&card_width=700"
    alt="Aidyn's GitHub contribution streak"
  />
</p>
