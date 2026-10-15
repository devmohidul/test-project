# Test Project

## Tech stack

This project is a **Node.js** application built with **TypeScript** and **Next.js**.

| Layer | Choice | Role |
| --- | --- | --- |
| Runtime | Node.js | JavaScript runtime for local development and production |
| Language | TypeScript | Typed JavaScript across app, API routes, and tooling |
| Framework | Next.js | App routing, React UI, server components, and API/server logic |

## Stack notes

- **Node.js** is the runtime. Use a current LTS release for local work and deployment.
- **TypeScript** is the source language. Prefer `.ts` / `.tsx` over plain JavaScript.
- **Next.js** is the web framework. Use the App Router, TypeScript throughout, and co-locate UI with server-side code as needed.

## Conventions

- Keep application code in the Next.js project structure (for example `app/`, `components/`, `lib/`).
- Share types and utilities in TypeScript modules rather than duplicating JS helpers.
- Prefer server-side work in Next.js (Server Components, Route Handlers) unless a client component is required.
