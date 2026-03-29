# PADELIN POS Starter

A desktop-first POS and reception starter for PADELIN.

## What is included

- Next.js app structure
- premium navy UI inspired by the current PADELIN website
- login page starter
- dashboard
- POS screen
- products
- orders
- customers
- reports
- settings
- Prisma schema for a real relational backend

## Install

```bash
npm install
cp .env.example .env
npm run dev
```

## Recommended production stack

- Next.js
- PostgreSQL
- Prisma
- Supabase Auth or NextAuth
- Vercel

## First real implementation steps

1. Connect PostgreSQL
2. Run Prisma migrations
3. Replace login starter with real auth
4. Build server actions for orders and payments
5. Add receipt generation
6. Add inventory mutation logic
7. Protect admin routes

## Routes

- `/login`
- `/dashboard`
- `/pos`
- `/orders`
- `/products`
- `/customers`
- `/reports`
- `/settings`

## Notes

This starter is intentionally clean and repo-ready.
It focuses first on the visual system and product structure so you can drop it into a new GitHub repository and continue implementation immediately.
