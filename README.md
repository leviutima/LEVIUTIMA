# Levi Utima

**Full-stack developer — Go & TypeScript.** I build production systems end to end: Next.js and Expo on the front, Go and NestJS on the back. Clean Architecture, SOLID, TDD.

Based in São Paulo, Brazil (UTC-3) — available for remote work worldwide.

[![Email](https://img.shields.io/badge/-Email-333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:leviutima.profissional@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/levi-yuki-utima-7b3187289/)

---

## Cave Mode

A life management app that brings finances, diet, goals, and health tracking into one place — built solo, front to back.

**Mobile** — Expo / React Native, structured in Feature-Sliced Design, with a monochrome design language built on a custom token system.

**API** — NestJS following Clean Architecture, with PostgreSQL, Prisma, and Docker. Domain logic isolated from framework and transport, so the business rules stay testable and the delivery layer stays replaceable.

**Auth** — email/password plus Google and Apple sign-in over OAuth2 with PKCE, treated as the first vertical rather than an afterthought bolted on later.

The interesting problem here isn't any single feature — it's keeping four unrelated domains (money, food, goals, health) in one product without the codebase collapsing into a shared-everything mess. That's what the architecture is for.

*In active development.*

---

## create-fsd-app

A CLI that scaffolds front-end projects (Vite, Next.js, Expo) pre-structured in **Feature-Sliced Design**, with architecture linting built in — so the structure stays enforced as the codebase grows, instead of decaying after month three.

Built because most front-end projects don't fail on syntax; they fail on structure nobody agreed on.

→ [github.com/leviutima/create-fsd-app](https://github.com/leviutima/create-fsd-app)

---

## Stack

**Languages** — Go · TypeScript · JavaScript

**Front-end** — React · Next.js · Astro · Vite · TanStack Query · Zustand · React Hook Form · Zod · Tailwind CSS

**Mobile** — Expo · React Native

**Back-end** — Go · NestJS · Node.js · PostgreSQL · Prisma · sqlc · pgx · Docker

**Auth & Security** — Keycloak · OAuth2 with PKCE

**Architecture** — Clean Architecture · SOLID · TDD · Feature-Sliced Design · Microservices

**AI & Automation** — AI orchestration for workflow automation

---

## How I work

I care about the seams — the boundaries between modules, the contract between front and back, the decisions that are cheap now and expensive in six months. That's why I write in Go and TypeScript, structure back-ends around Clean Architecture, and built a tool to keep front-end structure from drifting.

I work independently and communicate in writing by default — async-friendly across time zones.

