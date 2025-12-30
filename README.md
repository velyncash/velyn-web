# velyn-web

![ci](https://github.com/velyncash/velyn-web/actions/workflows/ci.yml/badge.svg)

Velyn.Cash web frontend (web + mobile-ready).  
UI: clean minimal glass (white/pink).  
Auth: username/password + PIN.  
Modules: dashboard, payments, cards, budgeting, analytics, security, settings.

---

## Scope

This repository contains **UI + client flows only**:
- Routing, layouts, components, screens
- Client-side state and UX interactions
- API consumption via `NEXT_PUBLIC_API_BASE_URL`

Backend services live in **`velyn-api`**.

---

## Tech Stack

- Next.js (App Router) + TypeScript  
- TailwindCSS + shadcn/ui  
- Mobile-first layout (bottom navigation)

---

## Routes

Public:
- `/` — landing
- `/auth/signup` — sign up
- `/auth/signin` — sign in
- `/auth/pin` — PIN verify

Protected UI:
- `/app/dashboard`
- `/app/payments`
- `/app/cards`
- `/app/budgeting`
- `/app/analytics`
- `/app/security`
- `/app/settings`

---

## Commands

```bash
npm run dev       # local dev
npm run build     # production build
npm run start     # run production server
npm run lint      # lint checks
npm run typecheck # TypeScript checks
