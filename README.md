# my-turborepo

A study project for learning [Turborepo](https://turborepo.com), generated with `create-turbo`. The code is the unmodified starter template: two Next.js apps that share a UI library and tooling configuration.

## What's inside

| Path | Description |
|---|---|
| `apps/web` | Next.js app, served on port 3000 |
| `apps/docs` | Next.js app, served on port 3001 |
| `packages/ui` | Shared React components (`button`, `card`, `code`) |
| `packages/eslint-config` | Shared ESLint configuration |
| `packages/typescript-config` | Shared TypeScript configuration |

## Getting started

You need Node.js 24 or later and pnpm.

```bash
pnpm install
pnpm dev
```

Then open <http://localhost:3000> and <http://localhost:3001>.

## Scripts

Run these from the repository root:

| Command | Description |
|---|---|
| `pnpm dev` | Start every app in development mode |
| `pnpm build` | Build all apps and packages |
| `pnpm lint` | Lint all apps and packages |
| `pnpm check-types` | Check types across the monorepo |
| `pnpm format` | Format TypeScript and Markdown files with Prettier |
