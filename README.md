# Aaharvatika

A mess management platform connecting **Admins**, **Messwalas** (mess owners), **Kitchen Staff** and **Students**.

> **Status:** Repository foundation only. No application features are implemented yet.

## Repository layout

| Path        | Purpose                                                                 |
|-------------|-------------------------------------------------------------------------|
| `frontend/` | One React + TypeScript + Vite app containing all four dashboards        |
| `backend/`  | One Express + TypeScript API (modular monolith) with Prisma/PostgreSQL  |
| `docs/`     | Product, architecture, database and API documentation                   |

This is an **npm workspaces** monorepo: run `npm install` once at the root to install
dependencies for both `frontend` and `backend`.

## Tech stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS, React Router, TanStack Query
- **Backend:** Node.js, Express, TypeScript, REST, Zod
- **Database:** PostgreSQL, Prisma ORM

## Prerequisites

- Node.js >= 22
- npm >= 10
- PostgreSQL (running locally)

## Getting started

_Setup instructions will be added as the backend and frontend are initialized._

## Documentation

- [Product Requirements](docs/PRD.md)
- [Architecture](docs/ARCHITECTURE.md)
- [Database](docs/DATABASE.md)
- [API Documentation](docs/API_DOCUMENTATION.md)
