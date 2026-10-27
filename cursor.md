# Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **UI:** React
- **Package manager:** npm

## Core Dependencies

- **next** — Next.js App Router
- **react / react-dom** — UI
- **dotenv** — extra env loading if needed (Next.js also loads `.env.local`)

## Development Tools

- **typescript** — TypeScript compiler
- **@types/node**, **@types/react**, **@types/react-dom** — type definitions

## Project Structure

```
cursorsadi/
├── src/
│   └── app/
│       ├── layout.tsx     # Root layout
│       ├── page.tsx       # Home page
│       └── globals.css
├── .env.local             # Environment variables (not committed)
├── next.config.ts
├── tsconfig.json
├── package.json
└── cursor.md
```

## Scripts

| Command         | Description                    |
|-----------------|--------------------------------|
| `npm run dev`   | Next.js development server     |
| `npm run build` | Production build               |
| `npm start`     | Run production server          |

## Conventions

- App Router lives in `src/app/`
- Use ES modules (`import` / `export`)
- Env vars go in `.env.local` (`NEXT_PUBLIC_` prefix for client)
- Target Node.js 20+
