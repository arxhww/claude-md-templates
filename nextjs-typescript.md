# [Project] (Next.js, TypeScript)

## Commands
- install: `pnpm install`
- dev: `pnpm dev`
- test: `pnpm test`
- lint: `pnpm lint && pnpm typecheck`

## Conventions
- App Router; server components by default, add 'use client' only when needed
- Strict TypeScript, no any; validate external input with zod
- Data fetching in server components or route handlers, not in useEffect
- Styles: [Tailwind/CSS modules]; reuse components in src/components
- Env vars via src/env.ts only

## Do not
- Do not touch files outside the task scope.
- Do not disable tests or lint rules to make a check pass.
- Do not add a dependency without asking.

## Definition of done
- Tests pass, lint clean, types clean, diff is minimal.
