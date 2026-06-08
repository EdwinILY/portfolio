# Portfolio — Astro 6

## Commands
| Action | Command |
|---|---|
| Dev server (port 4321) | `pnpm dev` |
| Production build (→ `dist/`) | `pnpm build` |
| Preview production build | `pnpm preview` |
| Install deps | `pnpm install` |

## Package manager
- **pnpm** only. No npm/yarn.

## Project structure
```
src/
  pages/       — route pages (.astro)
  layouts/     — page layout wrappers
  components/  — reusable Astro/HTML components
  assets/      — images, SVGs, static imports
public/        — raw static files (favicon etc.)
```

## Conventions
- Starter template; no integrations, SSR adapter, content collections, or test framework yet.
- `.astro/types.d.ts` is auto-generated — do not edit.
- `dist/` and `.astro/` are gitignored.
- No linter or typecheck script configured. `tsconfig.json` extends `astro/tsconfigs/strict`.
